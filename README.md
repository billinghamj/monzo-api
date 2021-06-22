<table>
	<thead>
		<tr>
			<th>Method</th>
			<th>Path</th>
		</tr>
	</thead>
	<tbody>
		<tr><th colspan="2">service.api.3dsecure-challenge</th></tr>
		<tr><td>PUT</td><td>3dsecure-challenge/challenge/attempt</td></tr>
		<tr><td>PUT</td><td>3dsecure-challenge/challenge/cancel</td></tr>
		<tr><th colspan="2">service.api.account-closure</th></tr>
		<tr><td>PUT</td><td>account-closure/chat-with-us</td></tr>
		<tr><td>GET</td><td>account-closure/check-eligibility</td></tr>
		<tr><td>PUT</td><td>account-closure/close</td></tr>
		<tr><td>PUT</td><td>account-closure/submit-feedback</td></tr>
		<tr><th colspan="2">service.api.account-interest</th></tr>
		<tr><td>GET</td><td>account-interest/{account_id}</td></tr>
		<tr><th colspan="2">service.api.account-settings</th></tr>
		<tr><td>GET</td><td>account-settings</td></tr>
		<tr><td>PUT</td><td>account-settings</td></tr>
		<tr><th colspan="2">service.api.accounting-integration</th></tr>
		<tr><td>POST</td><td>accounting-integration/auth-callback</td></tr>
		<tr><td>POST</td><td>accounting-integration/auth-url</td></tr>
		<tr><td>DELETE</td><td>accounting-integration/delete</td></tr>
		<tr><td>GET</td><td>accounting-integration/list</td></tr>
		<tr><th colspan="2">service.api.accounts</th></tr>
		<tr><td>GET</td><td>accounts</td></tr>
		<tr><th colspan="2">service.api.accounts-aggregator</th></tr>
		<tr><td>PUT</td><td>accounts-aggregator/customize</td></tr>
		<tr><td>PUT</td><td>accounts-aggregator/home-cards/{id}/dismiss</td></tr>
		<tr><td>GET</td><td>accounts-aggregator/v2</td></tr>
		<tr><th colspan="2">service.api.accounts</th></tr>
		<tr><td>GET</td><td>accounts/main-account</td></tr>
		<tr><th colspan="2">service.api.ach</th></tr>
		<tr><td>DELETE</td><td>ach/account</td></tr>
		<tr><td>GET</td><td>ach/accounts</td></tr>
		<tr><td>PUT</td><td>ach/originate-credit</td></tr>
		<tr><td>PUT</td><td>ach/originate-debit</td></tr>
		<tr><th colspan="2">service.api.affordability-questionnaire</th></tr>
		<tr><td>PUT</td><td>affordability-questionnaire/affordability-questions-v2</td></tr>
		<tr><td>GET</td><td>affordability-questionnaire/affordability-questions?version=3</td></tr>
		<tr><th colspan="2">service.api.analytics</th></tr>
		<tr><td>POST</td><td>analytics/track</td></tr>
		<tr><th colspan="2">service.api.api</th></tr>
		<tr><td>GET</td><td>api/v2/incidents/unresolved.json</td></tr>
		<tr><th colspan="2">service.api.attachment</th></tr>
		<tr><td>POST</td><td>attachment/deregister</td></tr>
		<tr><td>POST</td><td>attachment/register</td></tr>
		<tr><td>POST</td><td>attachment/upload</td></tr>
		<tr><th colspan="2">service.api.authentication-session</th></tr>
		<tr><td>GET</td><td>authentication-session/list</td></tr>
		<tr><td>POST</td><td>authentication-session/refresh</td></tr>
		<tr><td>DELETE</td><td>authentication-session/revoke</td></tr>
		<tr><td>POST</td><td>authentication-session/upgrade</td></tr>
		<tr><th colspan="2">service.api.bacs-direct-debits</th></tr>
		<tr><td>PUT</td><td>bacs-direct-debits/instructions/{direct_debit_id}/cancel</td></tr>
		<tr><td>PUT</td><td>bacs-direct-debits/payment/{bacs_payment_id}/attempt</td></tr>
		<tr><th colspan="2">service.api.balance</th></tr>
		<tr><td>GET</td><td>balance</td></tr>
		<tr><td>GET</td><td>balance/graph</td></tr>
		<tr><th colspan="2">service.api.bills-pot</th></tr>
		<tr><td>DELETE</td><td>bills-pot/for/{scheme}/{payment_id}</td></tr>
		<tr><td>PUT</td><td>bills-pot/pay/{scheme}/{payment_id}/from/{pot_id}</td></tr>
		<tr><td>GET</td><td>bills-pot/pots/{pot_id}/left-to-pay</td></tr>
		<tr><td>PUT</td><td>bills-pot/pots/{pot_id}/payments</td></tr>
		<tr><th colspan="2">service.api.borrowing-ob-income-verification</th></tr>
		<tr><td>PUT</td><td>borrowing-ob-income-verification/connect</td></tr>
		<tr><td>GET</td><td>borrowing-ob-income-verification/providers</td></tr>
		<tr><td>PUT</td><td>borrowing-ob-income-verification/skip</td></tr>
		<tr><th colspan="2">service.api.budget-assessments</th></tr>
		<tr><td>PUT</td><td>budget-assessments/retrieve-screen</td></tr>
		<tr><td>PUT</td><td>budget-assessments/retrieve-screen/{screen_id}</td></tr>
		<tr><td>PUT</td><td>budget-assessments/submit</td></tr>
		<tr><th colspan="2">service.api.business-annual-confirmation</th></tr>
		<tr><td>PUT</td><td>business-annual-confirmation/confirm</td></tr>
		<tr><th colspan="2">service.api.business-images</th></tr>
		<tr><td>DELETE</td><td>business-images/image</td></tr>
		<tr><td>PUT</td><td>business-images/register</td></tr>
		<tr><td>POST</td><td>business-images/upload</td></tr>
		<tr><th colspan="2">service.api.business-invoice</th></tr>
		<tr><td>GET</td><td>business-invoice/account-allowance</td></tr>
		<tr><td>GET</td><td>business-invoice/invoices</td></tr>
		<tr><td>PUT</td><td>business-invoice/invoices</td></tr>
		<tr><td>DELETE</td><td>business-invoice/invoices/{id}</td></tr>
		<tr><td>GET</td><td>business-invoice/invoices/{id}</td></tr>
		<tr><td>PATCH</td><td>business-invoice/invoices/{id}</td></tr>
		<tr><td>PUT</td><td>business-invoice/invoices/{id}/cancel</td></tr>
		<tr><td>PUT</td><td>business-invoice/invoices/{id}/download</td></tr>
		<tr><td>PUT</td><td>business-invoice/invoices/{id}/duplicate</td></tr>
		<tr><td>PUT</td><td>business-invoice/invoices/{id}/finalise</td></tr>
		<tr><td>PUT</td><td>business-invoice/invoices/{id}/items</td></tr>
		<tr><td>DELETE</td><td>business-invoice/invoices/{id}/items/{itemId}</td></tr>
		<tr><td>PATCH</td><td>business-invoice/invoices/{id}/items/{itemId}</td></tr>
		<tr><td>PUT</td><td>business-invoice/invoices/{id}/pay</td></tr>
		<tr><td>PUT</td><td>business-invoice/invoices/{id}/preview</td></tr>
		<tr><td>PUT</td><td>business-invoice/invoices/{id}/send</td></tr>
		<tr><td>GET</td><td>business-invoice/options</td></tr>
		<tr><th colspan="2">service.api.business-member</th></tr>
		<tr><td>PUT</td><td>business-member/card-order/create</td></tr>
		<tr><td>GET</td><td>business-member/card-order/options</td></tr>
		<tr><td>PUT</td><td>business-member/invites/accept</td></tr>
		<tr><td>PUT</td><td>business-member/invites/cancel</td></tr>
		<tr><td>POST</td><td>business-member/invites/create</td></tr>
		<tr><td>GET</td><td>business-member/invites/read</td></tr>
		<tr><td>PUT</td><td>business-member/invites/reject</td></tr>
		<tr><td>PUT</td><td>business-member/legal-documents/accept</td></tr>
		<tr><td>GET</td><td>business-member/legal-documents/read</td></tr>
		<tr><td>GET</td><td>business-member/overview</td></tr>
		<tr><th colspan="2">service.api.business-onboarding</th></tr>
		<tr><td>GET</td><td>business-onboarding/actions</td></tr>
		<tr><td>PUT</td><td>business-onboarding/actions/skip</td></tr>
		<tr><td>GET</td><td>business-onboarding/list</td></tr>
		<tr><th colspan="2">service.api.business-plans</th></tr>
		<tr><td>GET</td><td>business-plans/active</td></tr>
		<tr><td>PUT</td><td>business-plans/active/switch</td></tr>
		<tr><td>GET</td><td>business-plans/features-hub</td></tr>
		<tr><td>GET</td><td>business-plans/switch/details</td></tr>
		<tr><th colspan="2">service.api.business-profile</th></tr>
		<tr><td>GET</td><td>business-profile</td></tr>
		<tr><td>GET</td><td>business-profile/dynamic-profile/screen</td></tr>
		<tr><td>POST</td><td>business-profile/microenterprise-view-params</td></tr>
		<tr><td>PATCH</td><td>business-profile/update</td></tr>
		<tr><th colspan="2">service.api.business-signup</th></tr>
		<tr><td>POST</td><td>business-signup/cancel</td></tr>
		<tr><td>PUT</td><td>business-signup/card-order/create</td></tr>
		<tr><td>GET</td><td>business-signup/card-order/options</td></tr>
		<tr><td>GET</td><td>business-signup/card-order/status</td></tr>
		<tr><td>PUT</td><td>business-signup/card/activate</td></tr>
		<tr><td>GET</td><td>business-signup/check-criteria</td></tr>
		<tr><td>GET</td><td>business-signup/company/controllers</td></tr>
		<tr><td>PUT</td><td>business-signup/company/controllers</td></tr>
		<tr><td>GET</td><td>business-signup/company/details</td></tr>
		<tr><td>GET</td><td>business-signup/company/search</td></tr>
		<tr><td>PUT</td><td>business-signup/company/select</td></tr>
		<tr><td>PUT</td><td>business-signup/confirm-identity</td></tr>
		<tr><td>PUT</td><td>business-signup/legal-documents/accept</td></tr>
		<tr><td>GET</td><td>business-signup/legal-documents/documents</td></tr>
		<tr><td>GET</td><td>business-signup/plans/available</td></tr>
		<tr><td>PUT</td><td>business-signup/plans/select</td></tr>
		<tr><td>GET</td><td>business-signup/profile</td></tr>
		<tr><td>PUT</td><td>business-signup/profile</td></tr>
		<tr><td>PUT</td><td>business-signup/profile/address</td></tr>
		<tr><td>GET</td><td>business-signup/profile/address/search</td></tr>
		<tr><td>PUT</td><td>business-signup/profile/commit</td></tr>
		<tr><td>GET</td><td>business-signup/profile/industry/options</td></tr>
		<tr><td>POST</td><td>business-signup/skip-stage</td></tr>
		<tr><td>POST</td><td>business-signup/start</td></tr>
		<tr><td>GET</td><td>business-signup/status</td></tr>
		<tr><th colspan="2">service.api.business-tax-residency</th></tr>
		<tr><td>GET</td><td>business-tax-residency/declaration</td></tr>
		<tr><td>POST</td><td>business-tax-residency/declaration</td></tr>
		<tr><td>GET</td><td>business-tax-residency/uk-residency</td></tr>
		<tr><td>POST</td><td>business-tax-residency/uk-residency</td></tr>
		<tr><td>PUT</td><td>business-tax-residency/uk-residency</td></tr>
		<tr><th colspan="2">service.api.card-designs</th></tr>
		<tr><td>GET</td><td>card-designs/available</td></tr>
		<tr><th colspan="2">service.api.card-dispatch</th></tr>
		<tr><td>GET</td><td>card-dispatch/status</td></tr>
		<tr><th colspan="2">service.api.card-order</th></tr>
		<tr><td>PUT</td><td>card-order/{accountId}/first-card/create</td></tr>
		<tr><td>GET</td><td>card-order/{accountId}/options</td></tr>
		<tr><td>PUT</td><td>card-order/{accountId}/quote</td></tr>
		<tr><th colspan="2">service.api.card-replacement</th></tr>
		<tr><td>POST</td><td>card-replacement/activate</td></tr>
		<tr><td>GET</td><td>card-replacement/delivery-countries</td></tr>
		<tr><td>PUT</td><td>card-replacement/delivery-estimate</td></tr>
		<tr><td>GET</td><td>card-replacement/international-price</td></tr>
		<tr><td>POST</td><td>card-replacement/order</td></tr>
		<tr><td>PUT</td><td>card-replacement/quote</td></tr>
		<tr><td>PUT</td><td>card-replacement/report</td></tr>
		<tr><th colspan="2">service.api.card-security-code-challenge</th></tr>
		<tr><td>GET</td><td>card-security-code-challenge/details</td></tr>
		<tr><td>POST</td><td>card-security-code-challenge/skip</td></tr>
		<tr><td>POST</td><td>card-security-code-challenge/submit</td></tr>
		<tr><th colspan="2">service.api.card</th></tr>
		<tr><td>POST</td><td>card/activate</td></tr>
		<tr><td>GET</td><td>card/list</td></tr>
		<tr><td>PUT</td><td>card/retrieve-pan</td></tr>
		<tr><td>PUT</td><td>card/toggle</td></tr>
		<tr><th colspan="2">service.api.cass</th></tr>
		<tr><td>GET</td><td>cass/documents/account-closure-instruction</td></tr>
		<tr><td>GET</td><td>cass/documents/current-account-switch-agreement</td></tr>
		<tr><td>GET</td><td>cass/suggest_dates</td></tr>
		<tr><td>POST</td><td>cass/switches/create</td></tr>
		<tr><td>GET</td><td>cass/switches/status</td></tr>
		<tr><td>POST</td><td>cass/switches/{switch_id}/complete</td></tr>
		<tr><td>GET</td><td>cass/switches/{switch_id}/payments</td></tr>
		<tr><td>GET</td><td>cass/validate_account</td></tr>
		<tr><th colspan="2">service.api.categories</th></tr>
		<tr><td>GET</td><td>categories</td></tr>
		<tr><td>PUT</td><td>categories</td></tr>
		<tr><td>PUT</td><td>categories/archive</td></tr>
		<tr><td>GET</td><td>categories/suggestions</td></tr>
		<tr><td>PUT</td><td>categories/update</td></tr>
		<tr><th colspan="2">service.api.charge-in-signup</th></tr>
		<tr><td>GET</td><td>charge-in-signup/{charge_id}/display</td></tr>
		<tr><td>GET</td><td>charge-in-signup/{charge_id}/status</td></tr>
		<tr><th colspan="2">service.api.charities</th></tr>
		<tr><td>GET</td><td>charities</td></tr>
		<tr><td>PUT</td><td>charities/authorize/start-donations</td></tr>
		<tr><td>PUT</td><td>charities/authorize/stop-donations</td></tr>
		<tr><th colspan="2">service.api.chat-customer-survey</th></tr>
		<tr><td>PUT</td><td>chat-customer-survey/{survey_id}</td></tr>
		<tr><td>PUT</td><td>chat-customer-survey/{survey_id}/respond</td></tr>
		<tr><th colspan="2">service.api.chat-flow</th></tr>
		<tr><td>PUT</td><td>chat-flow/v2/begin</td></tr>
		<tr><th colspan="2">service.api.chat-user-presence</th></tr>
		<tr><td>PUT</td><td>chat-user-presence/typing-stopped</td></tr>
		<tr><th colspan="2">service.api.chat</th></tr>
		<tr><td>GET</td><td>chat/eligibility</td></tr>
		<tr><td>PUT</td><td>chat/files/complete</td></tr>
		<tr><td>POST</td><td>chat/files/upload</td></tr>
		<tr><td>PUT</td><td>chat/lifecycle</td></tr>
		<tr><td>GET</td><td>chat/messages</td></tr>
		<tr><td>PUT</td><td>chat/messages</td></tr>
		<tr><td>PUT</td><td>chat/messages/mark-as-read</td></tr>
		<tr><td>PUT</td><td>chat/select-option</td></tr>
		<tr><td>PUT</td><td>chat/select-transactions</td></tr>
		<tr><td>GET</td><td>chat/status</td></tr>
		<tr><th colspan="2">service.api.config</th></tr>
		<tr><td>GET</td><td>config</td></tr>
		<tr><th colspan="2">service.api.confirmation-of-payee</th></tr>
		<tr><td>PUT</td><td>confirmation-of-payee/validate</td></tr>
		<tr><th colspan="2">service.api.contact-discovery</th></tr>
		<tr><td>POST</td><td>contact-discovery/query</td></tr>
		<tr><td>GET</td><td>contact-discovery/user/{id}</td></tr>
		<tr><td>POST</td><td>contact-discovery/users</td></tr>
		<tr><th colspan="2">service.api.contexts</th></tr>
		<tr><td>GET</td><td>contexts</td></tr>
		<tr><th colspan="2">service.api.credit-tracker</th></tr>
		<tr><td>GET</td><td>credit-tracker/consent</td></tr>
		<tr><td>PUT</td><td>credit-tracker/consent</td></tr>
		<tr><td>GET</td><td>credit-tracker/help</td></tr>
		<tr><td>GET</td><td>credit-tracker/summary</td></tr>
		<tr><th colspan="2">service.api.customer-support-authentication</th></tr>
		<tr><td>PUT</td><td>customer-support-authentication/authenticate</td></tr>
		<tr><th colspan="2">service.api.dynamic-form</th></tr>
		<tr><td>DELETE</td><td>dynamic-form/files/delete</td></tr>
		<tr><td>PUT</td><td>dynamic-form/files/upload</td></tr>
		<tr><td>PUT</td><td>dynamic-form/responses/create</td></tr>
		<tr><td>GET</td><td>dynamic-form/responses/read</td></tr>
		<tr><td>PUT</td><td>dynamic-form/responses/submit</td></tr>
		<tr><th colspan="2">service.api.dynamic-payment-flow</th></tr>
		<tr><td>PUT</td><td>dynamic-payment-flow/dynamic-flow</td></tr>
		<tr><th colspan="2">service.api.e2e-encryption</th></tr>
		<tr><td>GET</td><td>e2e-encryption/jwk/ec</td></tr>
		<tr><th colspan="2">service.api.energy-switch</th></tr>
		<tr><td>POST</td><td>energy-switch/initiate</td></tr>
		<tr><td>PUT</td><td>energy-switch/meter-point-location</td></tr>
		<tr><td>GET</td><td>energy-switch/meter-point-locations</td></tr>
		<tr><td>GET</td><td>energy-switch/quotes</td></tr>
		<tr><td>POST</td><td>energy-switch/reminder</td></tr>
		<tr><td>GET</td><td>energy-switch/reminder/options</td></tr>
		<tr><th colspan="2">service.api.external-accounts</th></tr>
		<tr><td>GET</td><td>external-accounts/account/{external_account_id}</td></tr>
		<tr><td>PUT</td><td>external-accounts/account/{external_account_id}/disconnect</td></tr>
		<tr><td>GET</td><td>external-accounts/account/{external_account_id}/transactions/history</td></tr>
		<tr><td>GET</td><td>external-accounts/account/{external_account_id}/transactions/updated</td></tr>
		<tr><td>GET</td><td>external-accounts/account/{external_account_id}/transactions/{transaction_id}</td></tr>
		<tr><td>PATCH</td><td>external-accounts/account/{external_account_id}/transactions/{transaction_id}</td></tr>
		<tr><td>PUT</td><td>external-accounts/connect</td></tr>
		<tr><td>GET</td><td>external-accounts/providers</td></tr>
		<tr><th colspan="2">service.api.external-cards</th></tr>
		<tr><td>GET</td><td>external-cards</td></tr>
		<tr><td>PUT</td><td>external-cards/auth/callback</td></tr>
		<tr><td>POST</td><td>external-cards/auth/url</td></tr>
		<tr><td>DELETE</td><td>external-cards/{card_id}</td></tr>
		<tr><td>GET</td><td>external-cards/{card_id}</td></tr>
		<tr><td>GET</td><td>external-cards/{card_id}/transactions</td></tr>
		<tr><th colspan="2">service.api.external-payment-requests</th></tr>
		<tr><td>PUT</td><td>external-payment-requests</td></tr>
		<tr><td>DELETE</td><td>external-payment-requests/{id}</td></tr>
		<tr><td>GET</td><td>external-payment-requests/{id}</td></tr>
		<tr><td>PUT</td><td>external-payment-requests/{id}/mark-paid</td></tr>
		<tr><th colspan="2">service.api.external-payments</th></tr>
		<tr><td>PUT</td><td>external-payments/legal-documents/accept</td></tr>
		<tr><td>GET</td><td>external-payments/legal-documents/read</td></tr>
		<tr><td>GET</td><td>external-payments/legal-documents/status</td></tr>
		<tr><td>POST</td><td>external-payments/pay</td></tr>
		<tr><td>GET</td><td>external-payments/providers</td></tr>
		<tr><th colspan="2">service.api.faster-payments</th></tr>
		<tr><td>POST</td><td>faster-payments/create</td></tr>
		<tr><th colspan="2">service.api.fcm</th></tr>
		<tr><td>POST</td><td>fcm/register</td></tr>
		<tr><th colspan="2">service.api.feed</th></tr>
		<tr><td>GET</td><td>feed</td></tr>
		<tr><td>POST</td><td>feed/mark-read</td></tr>
		<tr><td>DELETE</td><td>feed/{id}</td></tr>
		<tr><th colspan="2">service.api.feedback</th></tr>
		<tr><td>POST</td><td>feedback/create</td></tr>
		<tr><th colspan="2">service.api.fees-and-allowances</th></tr>
		<tr><td>GET</td><td>fees-and-allowances/allowance</td></tr>
		<tr><td>GET</td><td>fees-and-allowances/changes-summary</td></tr>
		<tr><td>GET</td><td>fees-and-allowances/home</td></tr>
		<tr><td>PUT</td><td>fees-and-allowances/home/banner/{id}/dismiss</td></tr>
		<tr><td>GET</td><td>fees-and-allowances/increase-allowances</td></tr>
		<tr><th colspan="2">service.api.fincrime-ban-flow</th></tr>
		<tr><td>POST</td><td>fincrime-ban-flow/banned-screen/seen</td></tr>
		<tr><td>POST</td><td>fincrime-ban-flow/defund-details/create</td></tr>
		<tr><td>GET</td><td>fincrime-ban-flow/defund-details/latest</td></tr>
		<tr><td>POST</td><td>fincrime-ban-flow/recently-unbanned-screen/seen</td></tr>
		<tr><th colspan="2">service.api.frontend-view</th></tr>
		<tr><td>POST</td><td>frontend-view/action</td></tr>
		<tr><td>GET</td><td>frontend-view/read/{id}</td></tr>
		<tr><th colspan="2">service.api.future-transactions</th></tr>
		<tr><td>GET</td><td>future-transactions</td></tr>
		<tr><th colspan="2">service.api.get-paid-early</th></tr>
		<tr><td>PUT</td><td>get-paid-early/{transaction_id}/pay-now</td></tr>
		<tr><th colspan="2">service.api.help</th></tr>
		<tr><td>GET</td><td>help/content/categories</td></tr>
		<tr><td>GET</td><td>help/content/categories/{id}</td></tr>
		<tr><td>GET</td><td>help/content/related-articles/{id}</td></tr>
		<tr><td>GET</td><td>help/content/search</td></tr>
		<tr><td>GET</td><td>help/content/topics/{id}</td></tr>
		<tr><td>GET</td><td>help/home</td></tr>
		<tr><td>POST</td><td>help/transaction-dispute/action</td></tr>
		<tr><td>GET</td><td>help/transaction-dispute/{transactionId}</td></tr>
		<tr><th colspan="2">service.api.identity-challenge</th></tr>
		<tr><td>POST</td><td>identity-challenge/register-identity-document</td></tr>
		<tr><td>POST</td><td>identity-challenge/register-selfie-video</td></tr>
		<tr><td>POST</td><td>identity-challenge/request-file-upload</td></tr>
		<tr><td>GET</td><td>identity-challenge/status</td></tr>
		<tr><td>POST</td><td>identity-challenge/submit</td></tr>
		<tr><th colspan="2">service.api.identity-verification</th></tr>
		<tr><td>POST</td><td>identity-verification/register-identity-document</td></tr>
		<tr><td>POST</td><td>identity-verification/register-selfie-video</td></tr>
		<tr><td>POST</td><td>identity-verification/request-file-upload</td></tr>
		<tr><td>GET</td><td>identity-verification/status</td></tr>
		<tr><td>POST</td><td>identity-verification/submit</td></tr>
		<tr><th colspan="2">service.api.inbox</th></tr>
		<tr><td>GET</td><td>inbox</td></tr>
		<tr><td>PUT</td><td>inbox/dismiss</td></tr>
		<tr><td>PUT</td><td>inbox/mark-as-received</td></tr>
		<tr><td>PUT</td><td>inbox/mark-as-seen</td></tr>
		<tr><td>PUT</td><td>inbox/mark-as-tapped</td></tr>
		<tr><th colspan="2">service.api.income-declaration</th></tr>
		<tr><td>PUT</td><td>income-declaration</td></tr>
		<tr><th colspan="2">service.api.instalment-loan</th></tr>
		<tr><td>POST</td><td>instalment-loan/applications</td></tr>
		<tr><td>POST</td><td>instalment-loan/applications/submit</td></tr>
		<tr><td>GET</td><td>instalment-loan/decline-screen</td></tr>
		<tr><td>GET</td><td>instalment-loan/destination</td></tr>
		<tr><td>GET</td><td>instalment-loan/eligibility</td></tr>
		<tr><td>PUT</td><td>instalment-loan/loan-purpose</td></tr>
		<tr><td>GET</td><td>instalment-loan/loan-purpose-screen</td></tr>
		<tr><td>PATCH</td><td>instalment-loan/loans/{loan_id}/personalize</td></tr>
		<tr><td>GET</td><td>instalment-loan/loans/{loan_id}/repayment</td></tr>
		<tr><td>PUT</td><td>instalment-loan/loans/{loan_id}/repayment</td></tr>
		<tr><td>POST</td><td>instalment-loan/loans/{loan_id}/upload-image</td></tr>
		<tr><td>GET</td><td>instalment-loan/schedules</td></tr>
		<tr><th colspan="2">service.api.internal-transfer</th></tr>
		<tr><td>PUT</td><td>internal-transfer/create</td></tr>
		<tr><td>GET</td><td>internal-transfer/details</td></tr>
		<tr><th colspan="2">service.api.labs</th></tr>
		<tr><td>PUT</td><td>labs/disable</td></tr>
		<tr><td>PUT</td><td>labs/enable</td></tr>
		<tr><td>GET</td><td>labs/features</td></tr>
		<tr><th colspan="2">service.api.legal-documents</th></tr>
		<tr><td>GET</td><td>legal-documents/accepted</td></tr>
		<tr><th colspan="2">service.api.login</th></tr>
		<tr><td>POST</td><td>login/authorize</td></tr>
		<tr><td>POST</td><td>login/logout</td></tr>
		<tr><td>POST</td><td>login/token</td></tr>
		<tr><th colspan="2">service.api.mastercard-mdes</th></tr>
		<tr><td>POST</td><td>mastercard-mdes/google-pay/digitization-data</td></tr>
		<tr><td>POST</td><td>mastercard-mdes/google-pay/signup-digitization-data</td></tr>
		<tr><th colspan="2">service.api.merchant</th></tr>
		<tr><td>GET</td><td>merchant/search?user_location=0</td></tr>
		<tr><td>POST</td><td>merchant/{merchant_id}/propose-edit</td></tr>
		<tr><th colspan="2">service.api.monzo-flex</th></tr>
		<tr><td>PUT</td><td>monzo-flex/application/complete</td></tr>
		<tr><td>PUT</td><td>monzo-flex/application/start</td></tr>
		<tr><td>GET</td><td>monzo-flex/{id}/feed</td></tr>
		<tr><td>GET</td><td>monzo-flex/{id}/manage</td></tr>
		<tr><th colspan="2">service.api.monzo-paid-onboarding</th></tr>
		<tr><td>GET</td><td>monzo-paid-onboarding/features</td></tr>
		<tr><th colspan="2">service.api.nearby</th></tr>
		<tr><td>POST</td><td>nearby/create-token</td></tr>
		<tr><td>GET</td><td>nearby/resolve-token</td></tr>
		<tr><th colspan="2">service.api.news</th></tr>
		<tr><td>GET</td><td>news/active</td></tr>
		<tr><td>PUT</td><td>news/dismiss</td></tr>
		<tr><th colspan="2">service.api.oauth2</th></tr>
		<tr><td>POST</td><td>oauth2/token</td></tr>
		<tr><th colspan="2">service.api.open-banking-external-redirects</th></tr>
		<tr><td>POST</td><td>open-banking-external-redirects/submit</td></tr>
		<tr><th colspan="2">service.api.overdraft-application</th></tr>
		<tr><td>PUT</td><td>overdraft-application/accept-agreements</td></tr>
		<tr><td>PUT</td><td>overdraft-application/application/resume</td></tr>
		<tr><td>PUT</td><td>overdraft-application/application/start</td></tr>
		<tr><td>GET</td><td>overdraft-application/poll-stage</td></tr>
		<tr><td>PUT</td><td>overdraft-application/set-limit</td></tr>
		<tr><td>GET</td><td>overdraft-application/stage/agreements</td></tr>
		<tr><td>PUT</td><td>overdraft-application/stage/complete</td></tr>
		<tr><td>GET</td><td>overdraft-application/stage/decline-reason</td></tr>
		<tr><td>GET</td><td>overdraft-application/stage/introduction</td></tr>
		<tr><td>GET</td><td>overdraft-application/stage/introduction-v2</td></tr>
		<tr><td>GET</td><td>overdraft-application/stage/limit-selection</td></tr>
		<tr><th colspan="2">service.api.overdraft</th></tr>
		<tr><td>GET</td><td>overdraft/credit-agreements</td></tr>
		<tr><td>POST</td><td>overdraft/deactivate</td></tr>
		<tr><td>GET</td><td>overdraft/fee-breakdown</td></tr>
		<tr><td>PUT</td><td>overdraft/limit</td></tr>
		<tr><td>PUT</td><td>overdraft/pay-early</td></tr>
		<tr><td>GET</td><td>overdraft/status</td></tr>
		<tr><th colspan="2">service.api.p2p</th></tr>
		<tr><td>POST</td><td>p2p/react</td></tr>
		<tr><td>POST</td><td>p2p/recipients</td></tr>
		<tr><td>POST</td><td>p2p/transfer</td></tr>
		<tr><th colspan="2">service.api.partner-push-auth</th></tr>
		<tr><td>POST</td><td>partner-push-auth/integrations/user/issue</td></tr>
		<tr><th colspan="2">service.api.pay-anyone</th></tr>
		<tr><td>PUT</td><td>pay-anyone/cancel</td></tr>
		<tr><td>PUT</td><td>pay-anyone/create</td></tr>
		<tr><th colspan="2">service.api.payee</th></tr>
		<tr><td>PUT</td><td>payee/create/fps</td></tr>
		<tr><td>PUT</td><td>payee/create/p2p</td></tr>
		<tr><td>GET</td><td>payee/list</td></tr>
		<tr><td>PUT</td><td>payee/merge</td></tr>
		<tr><td>GET</td><td>payee/sort-code</td></tr>
		<tr><td>POST</td><td>payee/upload-image</td></tr>
		<tr><td>GET</td><td>payee/validate</td></tr>
		<tr><td>DELETE</td><td>payee/{id}</td></tr>
		<tr><td>PUT</td><td>payee/{id}</td></tr>
		<tr><td>PUT</td><td>payee/{id}/accounts/fps</td></tr>
		<tr><td>PUT</td><td>payee/{id}/profile-image</td></tr>
		<tr><td>PUT</td><td>payee/{payee_id}/accounts/fps/{external_id}</td></tr>
		<tr><td>DELETE</td><td>payee/{payee_id}/favorite</td></tr>
		<tr><td>PUT</td><td>payee/{payee_id}/favorite</td></tr>
		<tr><th colspan="2">service.api.payment-limit</th></tr>
		<tr><td>GET</td><td>payment-limit/limits</td></tr>
		<tr><th colspan="2">service.api.payment-request</th></tr>
		<tr><td>PUT</td><td>payment-request/bill-splitting/create</td></tr>
		<tr><td>GET</td><td>payment-request/bill-splitting/list</td></tr>
		<tr><td>GET</td><td>payment-request/bill-splitting/{id}</td></tr>
		<tr><td>PUT</td><td>payment-request/bill-splitting/{id}/cancel</td></tr>
		<tr><td>PUT</td><td>payment-request/bill-splitting/{id}/send-reminder</td></tr>
		<tr><td>PUT</td><td>payment-request/create</td></tr>
		<tr><td>GET</td><td>payment-request/{id}</td></tr>
		<tr><td>PUT</td><td>payment-request/{id}/cancel</td></tr>
		<tr><td>PUT</td><td>payment-request/{id}/decline</td></tr>
		<tr><td>PUT</td><td>payment-request/{id}/pay</td></tr>
		<tr><th colspan="2">service.api.payments</th></tr>
		<tr><td>PUT</td><td>payments/update</td></tr>
		<tr><th colspan="2">service.api.phone</th></tr>
		<tr><td>POST</td><td>phone/send-code</td></tr>
		<tr><th colspan="2">service.api.pin-recovery</th></tr>
		<tr><td>PUT</td><td>pin-recovery/cancel</td></tr>
		<tr><td>POST</td><td>pin-recovery/retrieve</td></tr>
		<tr><td>POST</td><td>pin-recovery/start</td></tr>
		<tr><td>GET</td><td>pin-recovery/status</td></tr>
		<tr><th colspan="2">service.api.pin</th></tr>
		<tr><td>POST</td><td>pin/allowed</td></tr>
		<tr><td>POST</td><td>pin/read</td></tr>
		<tr><th colspan="2">service.api.plans</th></tr>
		<tr><td>PUT</td><td>plans</td></tr>
		<tr><td>GET</td><td>plans/active</td></tr>
		<tr><td>GET</td><td>plans/active/cancel</td></tr>
		<tr><td>PUT</td><td>plans/active/cancel</td></tr>
		<tr><td>GET</td><td>plans/available</td></tr>
		<tr><th colspan="2">service.api.pots</th></tr>
		<tr><td>GET</td><td>pots/closed/{context_id}</td></tr>
		<tr><td>GET</td><td>pots/interest-statement</td></tr>
		<tr><td>GET</td><td>pots/interest-statement/available-tax-years</td></tr>
		<tr><td>PUT</td><td>pots/legal-documents/accept/v2</td></tr>
		<tr><td>GET</td><td>pots/legal-documents/documents/v2</td></tr>
		<tr><td>GET</td><td>pots/national-insurance-number/check-if-submitted</td></tr>
		<tr><td>PUT</td><td>pots/national-insurance-number/submit</td></tr>
		<tr><td>PUT</td><td>pots/reopen/{pot_id}</td></tr>
		<tr><td>POST</td><td>pots/upload-image</td></tr>
		<tr><td>PUT</td><td>pots/v2</td></tr>
		<tr><td>GET</td><td>pots/v2?show_deleted=true</td></tr>
		<tr><td>DELETE</td><td>pots/{id}</td></tr>
		<tr><td>PUT</td><td>pots/{id}/deposit/v2</td></tr>
		<tr><td>GET</td><td>pots/{id}/details</td></tr>
		<tr><td>PATCH</td><td>pots/{id}/v2</td></tr>
		<tr><td>PUT</td><td>pots/{id}/withdraw/v2</td></tr>
		<tr><th colspan="2">service.api.previous-addresses</th></tr>
		<tr><td>PUT</td><td>previous-addresses</td></tr>
		<tr><th colspan="2">service.api.profile</th></tr>
		<tr><td>GET</td><td>profile</td></tr>
		<tr><td>PUT</td><td>profile/address</td></tr>
		<tr><td>GET</td><td>profile/address/search</td></tr>
		<tr><td>POST</td><td>profile/email/send</td></tr>
		<tr><td>PUT</td><td>profile/email/update</td></tr>
		<tr><td>PUT</td><td>profile/phone/update-number</td></tr>
		<tr><th colspan="2">service.api.pusher</th></tr>
		<tr><td>POST</td><td>pusher/auth</td></tr>
		<tr><th colspan="2">service.api.referral</th></tr>
		<tr><td>GET</td><td>referral/copy</td></tr>
		<tr><td>GET</td><td>referral/referral-tracker-copy</td></tr>
		<tr><th colspan="2">service.api.review-prompt</th></tr>
		<tr><td>PUT</td><td>review-prompt/dismiss-trustpilot-prompt</td></tr>
		<tr><td>GET</td><td>review-prompt/trustpilot-link</td></tr>
		<tr><th colspan="2">service.api.salaries</th></tr>
		<tr><td>GET</td><td>salaries/home</td></tr>
		<tr><td>PUT</td><td>salaries/select</td></tr>
		<tr><td>PUT</td><td>salaries/source</td></tr>
		<tr><td>GET</td><td>salaries/suggestions</td></tr>
		<tr><td>PUT</td><td>salaries/{salary_id}/deselect</td></tr>
		<tr><td>PUT</td><td>salaries/{salary_id}/sort/create</td></tr>
		<tr><td>GET</td><td>salaries/{salary_id}/sort/destinations</td></tr>
		<tr><td>PUT</td><td>salaries/{salary_id}/sort/{sort_id}/update</td></tr>
		<tr><th colspan="2">service.api.salary-sorter</th></tr>
		<tr><td>GET</td><td>salary-sorter/{transaction_id}/destinations</td></tr>
		<tr><td>PUT</td><td>salary-sorter/{transaction_id}/forget</td></tr>
		<tr><td>PUT</td><td>salary-sorter/{transaction_id}/sort</td></tr>
		<tr><td>PUT</td><td>salary-sorter/{transaction_id}/update</td></tr>
		<tr><th colspan="2">service.api.scheduled-payments</th></tr>
		<tr><td>POST</td><td>scheduled-payments/series/fps</td></tr>
		<tr><td>PUT</td><td>scheduled-payments/series/fps/{series_id}</td></tr>
		<tr><td>POST</td><td>scheduled-payments/series/pot-deposit</td></tr>
		<tr><td>POST</td><td>scheduled-payments/series/pot-withdrawal</td></tr>
		<tr><td>PUT</td><td>scheduled-payments/series/{series_id}/cancel</td></tr>
		<tr><th colspan="2">service.api.sdk_click</th></tr>
		<tr><td>POST</td><td>sdk_click</td></tr>
		<tr><th colspan="2">service.api.secure-token</th></tr>
		<tr><td>POST</td><td>secure-token/enrol/pin</td></tr>
		<tr><th colspan="2">service.api.self-disclosure</th></tr>
		<tr><td>PUT</td><td>self-disclosure/disclosure</td></tr>
		<tr><th colspan="2">service.api.session</th></tr>
		<tr><td>POST</td><td>session</td></tr>
		<tr><th colspan="2">service.api.signup-account-offering</th></tr>
		<tr><td>GET</td><td>signup-account-offering/applications</td></tr>
		<tr><td>GET</td><td>signup-account-offering/list</td></tr>
		<tr><td>PUT</td><td>signup-account-offering/selection</td></tr>
		<tr><th colspan="2">service.api.signup</th></tr>
		<tr><td>PUT</td><td>signup/affordability-questions/skip</td></tr>
		<tr><td>PUT</td><td>signup/help</td></tr>
		<tr><td>POST</td><td>signup/initial-topup/skip</td></tr>
		<tr><td>POST</td><td>signup/joint-account/cancel</td></tr>
		<tr><td>POST</td><td>signup/joint-account/card-order/create</td></tr>
		<tr><td>GET</td><td>signup/joint-account/card-order/options</td></tr>
		<tr><td>POST</td><td>signup/joint-account/start</td></tr>
		<tr><td>GET</td><td>signup/joint-account/status</td></tr>
		<tr><td>POST</td><td>signup/legal-documents/accept</td></tr>
		<tr><td>POST</td><td>signup/legal-documents/accept-list</td></tr>
		<tr><td>GET</td><td>signup/legal-documents/documents</td></tr>
		<tr><td>POST</td><td>signup/marketing/subscribe</td></tr>
		<tr><td>PUT</td><td>signup/monzo-paid-plan-definition-selection/set</td></tr>
		<tr><td>GET</td><td>signup/negative-prepaid-balance-status</td></tr>
		<tr><td>PUT</td><td>signup/notifications</td></tr>
		<tr><td>POST</td><td>signup/overdraft-opt-in/skip</td></tr>
		<tr><td>POST</td><td>signup/personal-account/card-order/create</td></tr>
		<tr><td>GET</td><td>signup/personal-account/card-order/options</td></tr>
		<tr><td>POST</td><td>signup/personal-account/card-order/reorder</td></tr>
		<tr><td>GET</td><td>signup/personal-account/card-order/status</td></tr>
		<tr><td>POST</td><td>signup/personal-account/card/activate</td></tr>
		<tr><td>POST</td><td>signup/personal-account/skip-stage</td></tr>
		<tr><td>POST</td><td>signup/personal-account/start</td></tr>
		<tr><td>GET</td><td>signup/personal-account/status</td></tr>
		<tr><td>POST</td><td>signup/personal-account/tax-identification-number</td></tr>
		<tr><td>GET</td><td>signup/profile</td></tr>
		<tr><td>PUT</td><td>signup/profile</td></tr>
		<tr><td>PUT</td><td>signup/profile/address</td></tr>
		<tr><td>GET</td><td>signup/profile/address/search</td></tr>
		<tr><td>POST</td><td>signup/profile/commit</td></tr>
		<tr><td>POST</td><td>signup/profile/phone/send</td></tr>
		<tr><td>POST</td><td>signup/profile/phone/verify</td></tr>
		<tr><td>PUT</td><td>signup/provision-mdes/skip</td></tr>
		<tr><td>POST</td><td>signup/secure-token/skip</td></tr>
		<tr><td>PUT</td><td>signup/signup-prompt/complete</td></tr>
		<tr><td>PUT</td><td>signup/user-survey/complete</td></tr>
		<tr><td>GET</td><td>signup/user-survey/read</td></tr>
		<tr><td>PUT</td><td>signup/user-survey/skip</td></tr>
		<tr><th colspan="2">service.api.special-offers</th></tr>
		<tr><td>GET</td><td>special-offers/listings</td></tr>
		<tr><td>GET</td><td>special-offers/listings/home</td></tr>
		<tr><td>GET</td><td>special-offers/memberships/{provider}/me</td></tr>
		<tr><td>PUT</td><td>special-offers/{provider}/accept-terms</td></tr>
		<tr><td>GET</td><td>special-offers/{provider}/options</td></tr>
		<tr><th colspan="2">service.api.spending-breakdown</th></tr>
		<tr><td>GET</td><td>spending-breakdown/periods</td></tr>
		<tr><td>GET</td><td>spending-breakdown/periods/current?enable_upcoming_amounts=true</td></tr>
		<tr><td>PUT</td><td>spending-breakdown/periods/overrides</td></tr>
		<tr><td>GET</td><td>spending-breakdown/periods/{period_id}/transactions</td></tr>
		<tr><td>GET</td><td>spending-breakdown/periods/{period_id}?enable_upcoming_amounts=true</td></tr>
		<tr><td>GET</td><td>spending-breakdown/report</td></tr>
		<tr><td>GET</td><td>spending-breakdown/targets</td></tr>
		<tr><td>PUT</td><td>spending-breakdown/targets</td></tr>
		<tr><td>GET</td><td>spending-breakdown/transactions-to-start-period</td></tr>
		<tr><th colspan="2">service.api.statement-of-fees</th></tr>
		<tr><td>GET</td><td>statement-of-fees/accounts/{account_id}/periods</td></tr>
		<tr><td>GET</td><td>statement-of-fees/accounts/{account_id}/periods/{start_date}/{end_date}</td></tr>
		<tr><td>GET</td><td>statement-of-fees/accounts/{account_id}/statements</td></tr>
		<tr><td>GET</td><td>statement-of-fees/statements/{statement_id}</td></tr>
		<tr><th colspan="2">service.api.statement</th></tr>
		<tr><td>GET</td><td>statement/options/{id}</td></tr>
		<tr><td>PUT</td><td>statement/{account_id}</td></tr>
		<tr><th colspan="2">service.api.stripe</th></tr>
		<tr><td>GET</td><td>stripe/cards</td></tr>
		<tr><td>POST</td><td>stripe/cards</td></tr>
		<tr><td>POST</td><td>stripe/three_d_secure</td></tr>
		<tr><td>POST</td><td>stripe/top_up</td></tr>
		<tr><th colspan="2">service.api.subscriptions</th></tr>
		<tr><td>GET</td><td>subscriptions</td></tr>
		<tr><td>PUT</td><td>subscriptions/create</td></tr>
		<tr><td>PUT</td><td>subscriptions/edit</td></tr>
		<tr><td>GET</td><td>subscriptions/{subscription_id}</td></tr>
		<tr><td>PUT</td><td>subscriptions/{subscription_id}/resume</td></tr>
		<tr><td>PUT</td><td>subscriptions/{subscription_id}/stop</td></tr>
		<tr><th colspan="2">service.api.summary</th></tr>
		<tr><td>GET</td><td>summary/external-account/{external_account_id}</td></tr>
		<tr><td>PUT</td><td>summary/external-account/{external_account_id}/settings</td></tr>
		<tr><th colspan="2">service.api.tabs</th></tr>
		<tr><td>GET</td><td>tabs</td></tr>
		<tr><td>POST</td><td>tabs</td></tr>
		<tr><td>GET</td><td>tabs/{tab_id}</td></tr>
		<tr><td>PUT</td><td>tabs/{tab_id}/finish</td></tr>
		<tr><td>PUT</td><td>tabs/{tab_id}/items/add</td></tr>
		<tr><td>DELETE</td><td>tabs/{tab_id}/items/{item_id}</td></tr>
		<tr><td>PUT</td><td>tabs/{tab_id}/leave</td></tr>
		<tr><td>PUT</td><td>tabs/{tab_id}/participants/add</td></tr>
		<tr><td>PUT</td><td>tabs/{tab_id}/pay-all</td></tr>
		<tr><td>PUT</td><td>tabs/{tab_id}/send-reminder</td></tr>
		<tr><td>GET</td><td>tabs/{tab_id}/subscriptions</td></tr>
		<tr><td>PUT</td><td>tabs/{tab_id}/subscriptions/add</td></tr>
		<tr><td>DELETE</td><td>tabs/{tab_id}/subscriptions/{subscription_id}</td></tr>
		<tr><th colspan="2">service.api.tax-residency</th></tr>
		<tr><td>POST</td><td>tax-residency/no-tin</td></tr>
		<tr><td>PUT</td><td>tax-residency/no-tin</td></tr>
		<tr><td>GET</td><td>tax-residency/start-link</td></tr>
		<tr><td>GET</td><td>tax-residency/status</td></tr>
		<tr><td>POST</td><td>tax-residency/submit</td></tr>
		<tr><td>PUT</td><td>tax-residency/submit</td></tr>
		<tr><td>GET</td><td>tax-residency/submitted-residencies</td></tr>
		<tr><td>POST</td><td>tax-residency/update-self-certification</td></tr>
		<tr><td>POST</td><td>tax-residency/update-tin</td></tr>
		<tr><th colspan="2">service.api.topup</th></tr>
		<tr><td>GET</td><td>topup/status</td></tr>
		<tr><th colspan="2">service.api.transaction-dispute-form</th></tr>
		<tr><td>PUT</td><td>transaction-dispute-form/submit/atm</td></tr>
		<tr><td>PUT</td><td>transaction-dispute-form/submit/goods-and-services</td></tr>
		<tr><th colspan="2">service.api.transaction-export-integrations</th></tr>
		<tr><td>POST</td><td>transaction-export-integrations/auth-code</td></tr>
		<tr><td>PUT</td><td>transaction-export-integrations/create-session</td></tr>
		<tr><td>PUT</td><td>transaction-export-integrations/disconnect</td></tr>
		<tr><td>GET</td><td>transaction-export-integrations/integrations</td></tr>
		<tr><td>PUT</td><td>transaction-export-integrations/start</td></tr>
		<tr><td>PUT</td><td>transaction-export-integrations/stop</td></tr>
		<tr><th colspan="2">service.api.transaction-export</th></tr>
		<tr><td>PUT</td><td>transaction-export/csv</td></tr>
		<tr><td>PUT</td><td>transaction-export/qif</td></tr>
		<tr><th colspan="2">service.api.transaction-widgets</th></tr>
		<tr><td>GET</td><td>transaction-widgets/{transaction_id}</td></tr>
		<tr><th colspan="2">service.api.transactions</th></tr>
		<tr><td>POST</td><td>transactions/update-metadata</td></tr>
		<tr><td>PATCH</td><td>transactions/{transaction_id}</td></tr>
		<tr><td>GET</td><td>transactions/{transaction_id}?expand[]=merchant</td></tr>
		<tr><th colspan="2">service.api.transferwise</th></tr>
		<tr><td>POST</td><td>transferwise/account</td></tr>
		<tr><td>POST</td><td>transferwise/account-requirements</td></tr>
		<tr><td>POST</td><td>transferwise/auth</td></tr>
		<tr><td>POST</td><td>transferwise/auth-callback</td></tr>
		<tr><td>GET</td><td>transferwise/quote</td></tr>
		<tr><td>POST</td><td>transferwise/quote</td></tr>
		<tr><td>GET</td><td>transferwise/supported-currencies</td></tr>
		<tr><td>POST</td><td>transferwise/transfer</td></tr>
		<tr><td>GET</td><td>transferwise/transfer-requirements</td></tr>
		<tr><td>GET</td><td>transferwise/user</td></tr>
		<tr><td>GET</td><td>transferwise/v1.1/quotes/{id}/account-requirements</td></tr>
		<tr><td>POST</td><td>transferwise/v1.1/quotes/{id}/account-requirements</td></tr>
		<tr><td>POST</td><td>transferwise/v1/account</td></tr>
		<tr><td>POST</td><td>transferwise/v1/transfer-requirements</td></tr>
		<tr><td>GET</td><td>transferwise/v2/account</td></tr>
		<tr><td>POST</td><td>transferwise/v2/accounts</td></tr>
		<tr><td>GET</td><td>transferwise/v2/quote</td></tr>
		<tr><td>PATCH</td><td>transferwise/v2/quote</td></tr>
		<tr><td>POST</td><td>transferwise/v2/quote</td></tr>
		<tr><td>GET</td><td>transferwise/v2/supported-currencies</td></tr>
		<tr><th colspan="2">service.api.trip</th></tr>
		<tr><td>GET</td><td>trip/{trip_id}</td></tr>
		<tr><th colspan="2">service.api.universal-authentication</th></tr>
		<tr><td>PUT</td><td>universal-authentication/authenticate</td></tr>
		<tr><td>PUT</td><td>universal-authentication/cancel</td></tr>
		<tr><td>GET</td><td>universal-authentication/config</td></tr>
		<tr><th colspan="2">service.api.user-images</th></tr>
		<tr><td>DELETE</td><td>user-images/image</td></tr>
		<tr><td>PUT</td><td>user-images/register</td></tr>
		<tr><td>POST</td><td>user-images/upload</td></tr>
		<tr><th colspan="2">service.api.user-settings</th></tr>
		<tr><td>GET</td><td>user-settings</td></tr>
		<tr><td>PUT</td><td>user-settings</td></tr>
		<tr><td>PUT</td><td>user-settings/gambling-block/disable</td></tr>
		<tr><td>PUT</td><td>user-settings/gambling-block/enable</td></tr>
		<tr><td>PUT</td><td>user-settings/overdraft-notifications</td></tr>
		<tr><th colspan="2">service.api.user-survey</th></tr>
		<tr><td>GET</td><td>user-survey/{survey_id}</td></tr>
		<tr><td>PUT</td><td>user-survey/{survey_id}/submit</td></tr>
		<tr><th colspan="2">service.api.user-transaction-controls</th></tr>
		<tr><td>GET</td><td>user-transaction-controls/merchant-blocks/list</td></tr>
		<tr><td>GET</td><td>user-transaction-controls/merchant-blocks/unblock</td></tr>
		<tr><th colspan="2">service.api.virtual-cards</th></tr>
		<tr><td>GET</td><td>virtual-cards</td></tr>
		<tr><td>PUT</td><td>virtual-cards/card</td></tr>
		<tr><td>PUT</td><td>virtual-cards/card/delete</td></tr>
		<tr><td>PUT</td><td>virtual-cards/card/update</td></tr>
		<tr><th colspan="2">service.api.web-auth</th></tr>
		<tr><td>POST</td><td>web-auth/authorize</td></tr>
		<tr><th colspan="2">service.api.webview-validation</th></tr>
		<tr><td>PUT</td><td>webview-validation/validate</td></tr>
	</tbody>
</table>
