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
		<tr><th colspan="2">service.api.account-settings</th></tr>
		<tr><td>GET</td><td>account-settings</td></tr>
		<tr><td>PUT</td><td>account-settings</td></tr>
		<tr><th colspan="2">service.api.account-tour</th></tr>
		<tr><td>GET</td><td>account-tour</td></tr>
		<tr><td>PUT</td><td>account-tour/skip</td></tr>
		<tr><th colspan="2">service.api.accounts</th></tr>
		<tr><td>GET</td><td>accounts</td></tr>
		<tr><th colspan="2">service.api.affordability-check</th></tr>
		<tr><td>PUT</td><td>affordability-check/opt-in</td></tr>
		<tr><th colspan="2">service.api.analytics</th></tr>
		<tr><td>POST</td><td>analytics/track</td></tr>
		<tr><th colspan="2">service.api.apns</th></tr>
		<tr><td>POST</td><td>apns/clear_tokens</td></tr>
		<tr><td>POST</td><td>apns/register</td></tr>
		<tr><th colspan="2">service.api.attachment</th></tr>
		<tr><td>POST</td><td>attachment/deregister</td></tr>
		<tr><td>POST</td><td>attachment/register</td></tr>
		<tr><td>POST</td><td>attachment/upload</td></tr>
		<tr><th colspan="2">service.api.bacs-direct-debits</th></tr>
		<tr><td>GET</td><td>bacs-direct-debits/instructions</td></tr>
		<tr><td>PUT</td><td>bacs-direct-debits/instructions/{direct_debit_id}/cancel</td></tr>
		<tr><td>PUT</td><td>bacs-direct-debits/instructions/{direct_debit_id}/redirect</td></tr>
		<tr><td>PUT</td><td>bacs-direct-debits/payment/{bacs_payment_id}/attempt</td></tr>
		<tr><th colspan="2">service.api.banner</th></tr>
		<tr><td>GET</td><td>banner/active</td></tr>
		<tr><td>PUT</td><td>banner/dismiss</td></tr>
		<tr><th colspan="2">service.api.balance</th></tr>
		<tr><td>GET</td><td>balance</td></tr>
		<tr><td>GET</td><td>balance/graph</td></tr>
		<tr><td>GET</td><td>balance/limits</td></tr>
		<tr><th colspan="2">service.api.branches</th></tr>
		<tr><td>GET</td><td>branches</td></tr>
		<tr><th colspan="2">service.api.card-dispatch</th></tr>
		<tr><td>GET</td><td>card-dispatch/status</td></tr>
		<tr><th colspan="2">service.api.card-replacement</th></tr>
		<tr><td>POST</td><td>card-replacement/activate</td></tr>
		<tr><td>POST</td><td>card-replacement/order</td></tr>
		<tr><th colspan="2">service.api.card-security-code-challenge</th></tr>
		<tr><td>GET</td><td>card-security-code-challenge/details</td></tr>
		<tr><td>POST</td><td>card-security-code-challenge/skip</td></tr>
		<tr><td>POST</td><td>card-security-code-challenge/submit</td></tr>
		<tr><th colspan="2">service.api.card</th></tr>
		<tr><td>POST</td><td>card/activate</td></tr>
		<tr><td>GET</td><td>card/list</td></tr>
		<tr><td>GET</td><td>card/pan</td></tr>
		<tr><td>PUT</td><td>card/toggle</td></tr>
		<tr><th colspan="2">service.api.cash-referrals</th></tr>
		<tr><td>GET</td><td>cash-referrals/active</td></tr>
		<tr><td>PUT</td><td>cash-referrals/claim</td></tr>
		<tr><td>PUT</td><td>cash-referrals/{referral}/redeem</td></tr>
		<tr><th colspan="2">service.api.cass</th></tr>
		<tr><td>GET</td><td>cass/documents/account-closure-instruction</td></tr>
		<tr><td>GET</td><td>cass/documents/current-account-switch-agreement</td></tr>
		<tr><td>GET</td><td>cass/suggest_dates</td></tr>
		<tr><td>POST</td><td>cass/switches/create</td></tr>
		<tr><td>GET</td><td>cass/switches/status</td></tr>
		<tr><td>POST</td><td>cass/switches/{switch_id}/complete</td></tr>
		<tr><td>GET</td><td>cass/switches/{switch_id}/payments</td></tr>
		<tr><td>GET</td><td>cass/validate_account</td></tr>
		<tr><th colspan="2">service.api.chat-customer-survey</th></tr>
		<tr><td>PUT</td><td>chat-customer-survey/{survey_id}</td></tr>
		<tr><th colspan="2">service.api.chat-user-selection</th></tr>
		<tr><td>GET</td><td>chat-user-selection/query-urgency</td></tr>
		<tr><th colspan="2">service.api.chat</th></tr>
		<tr><td>PUT</td><td>chat/files/complete</td></tr>
		<tr><td>POST</td><td>chat/files/upload</td></tr>
		<tr><td>GET</td><td>chat/messages</td></tr>
		<tr><td>PUT</td><td>chat/messages</td></tr>
		<tr><td>PUT</td><td>chat/messages/mark-as-read</td></tr>
		<tr><td>GET</td><td>chat/status</td></tr>
		<tr><th colspan="2">service.api.config</th></tr>
		<tr><td>GET</td><td>config</td></tr>
		<tr><th colspan="2">service.api.contact-discovery</th></tr>
		<tr><td>GET</td><td>contact-discovery/query</td></tr>
		<tr><td>GET</td><td>contact-discovery/user/{id}</td></tr>
		<tr><td>GET</td><td>contact-discovery/users</td></tr>
		<tr><th colspan="2">service.api.credit-builder</th></tr>
		<tr><td>GET</td><td>credit-builder/report</td></tr>
		<tr><th colspan="2">service.api.crowdfunding-investment</th></tr>
		<tr><td>GET</td><td>crowdfunding-investment/splash-screen</td></tr>
		<tr><th colspan="2">service.api.customer-support-authentication</th></tr>
		<tr><td>PUT</td><td>customer-support-authentication/authenticate</td></tr>
		<tr><th colspan="2">service.api.energy-switch</th></tr>
		<tr><td>POST</td><td>energy-switch/initiate</td></tr>
		<tr><td>GET</td><td>energy-switch/quotes</td></tr>
		<tr><th colspan="2">service.api.extended-authentication</th></tr>
		<tr><td>POST</td><td>extended-authentication/sms-otp/send</td></tr>
		<tr><td>POST</td><td>extended-authentication/sms-otp/verify</td></tr>
		<tr><td>GET</td><td>extended-authentication/status</td></tr>
		<tr><th colspan="2">service.api.faster-payments</th></tr>
		<tr><td>POST</td><td>faster-payments/create</td></tr>
		<tr><th colspan="2">service.api.fcm</th></tr>
		<tr><td>POST</td><td>fcm/register</td></tr>
		<tr><th colspan="2">service.api.feed</th></tr>
		<tr><td>GET</td><td>feed</td></tr>
		<tr><td>POST</td><td>feed</td></tr>
		<tr><td>POST</td><td>feed/mark-read</td></tr>
		<tr><td>DELETE</td><td>feed/{id}</td></tr>
		<tr><th colspan="2">service.api.feedback</th></tr>
		<tr><td>POST</td><td>feedback/create</td></tr>
		<tr><th colspan="2">service.api.frontend-view</th></tr>
		<tr><td>GET</td><td>frontend-view/action</td></tr>
		<tr><td>GET</td><td>frontend-view/read/{id}</td></tr>
		<tr><th colspan="2">service.api.geocode</th></tr>
		<tr><td>GET</td><td>geocode/postal-code-lookup</td></tr>
		<tr><th colspan="2">service.api.golden-ticket</th></tr>
		<tr><td>GET</td><td>golden-ticket/list</td></tr>
		<tr><td>GET</td><td>golden-ticket/{id}</td></tr>
		<tr><td>PUT</td><td>golden-ticket/{id}/claim</td></tr>
		<tr><th colspan="2">service.api.help</th></tr>
		<tr><td>GET</td><td>help/content/categories</td></tr>
		<tr><td>GET</td><td>help/content/categories/{id}</td></tr>
		<tr><td>GET</td><td>help/content/related-articles/{id}</td></tr>
		<tr><td>GET</td><td>help/content/search</td></tr>
		<tr><td>GET</td><td>help/content/trending</td></tr>
		<tr><td>GET</td><td>help/home</td></tr>
		<tr><td>POST</td><td>help/transaction-dispute/action</td></tr>
		<tr><td>GET</td><td>help/transaction-dispute/{transactionId}</td></tr>
		<tr><td>GET</td><td>help/transactions/{transactionId}</td></tr>
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
		<tr><th colspan="2">service.api.inbound-p2p</th></tr>
		<tr><td>GET</td><td>inbound-p2p/username/{username}</td></tr>
		<tr><th colspan="2">service.api.income-declaration</th></tr>
		<tr><td>PUT</td><td>income-declaration</td></tr>
		<tr><th colspan="2">service.api.instalment-loan</th></tr>
		<tr><td>POST</td><td>instalment-loan/applications</td></tr>
		<tr><td>POST</td><td>instalment-loan/applications/submit</td></tr>
		<tr><td>GET</td><td>instalment-loan/eligibility</td></tr>
		<tr><td>GET</td><td>instalment-loan/loans</td></tr>
		<tr><td>GET</td><td>instalment-loan/loans/{loan_id}</td></tr>
		<tr><td>GET</td><td>instalment-loan/loans/{loan_id}/credit-agreement</td></tr>
		<tr><td>GET</td><td>instalment-loan/loans/{loan_id}/repayment</td></tr>
		<tr><td>PUT</td><td>instalment-loan/loans/{loan_id}/repayment</td></tr>
		<tr><td>GET</td><td>instalment-loan/schedules</td></tr>
		<tr><th colspan="2">service.api.intercom</th></tr>
		<tr><td>GET</td><td>intercom/tokens/{intercom_app_id}</td></tr>
		<tr><th colspan="2">service.api.internal-transfer</th></tr>
		<tr><td>PUT</td><td>internal-transfer/create</td></tr>
		<tr><th colspan="2">service.api.invite</th></tr>
		<tr><td>PUT</td><td>invite</td></tr>
		<tr><th colspan="2">service.api.labs</th></tr>
		<tr><td>PUT</td><td>labs/disable</td></tr>
		<tr><td>PUT</td><td>labs/enable</td></tr>
		<tr><td>GET</td><td>labs/features</td></tr>
		<tr><th colspan="2">service.api.legal-documents</th></tr>
		<tr><td>GET</td><td>legal-documents/accepted</td></tr>
		<tr><th colspan="2">service.api.mastercard-mdes</th></tr>
		<tr><td>POST</td><td>mastercard-mdes/apple-pay/digitization-data</td></tr>
		<tr><td>POST</td><td>mastercard-mdes/challenge</td></tr>
		<tr><td>POST</td><td>mastercard-mdes/google-pay/digitization-data</td></tr>
		<tr><td>POST</td><td>mastercard-mdes/google-pay/signup-digitization-data</td></tr>
		<tr><th colspan="2">service.api.merchant</th></tr>
		<tr><td>GET</td><td>merchant/search</td></tr>
		<tr><td>POST</td><td>merchant/{merchant_id}/propose-edit</td></tr>
		<tr><th colspan="2">service.api.monzo-helper</th></tr>
		<tr><td>PUT</td><td>monzo-helper/simple-greeting/ack</td></tr>
		<tr><td>PUT</td><td>monzo-helper/simple-greeting/greet</td></tr>
		<tr><th colspan="2">service.api.nearby</th></tr>
		<tr><td>POST</td><td>nearby/create-token</td></tr>
		<tr><td>GET</td><td>nearby/resolve-token</td></tr>
		<tr><th colspan="2">service.api.news</th></tr>
		<tr><td>GET</td><td>news</td></tr>
		<tr><td>GET</td><td>news/active</td></tr>
		<tr><td>PUT</td><td>news/dismiss</td></tr>
		<tr><th colspan="2">service.api.oauth2</th></tr>
		<tr><td>POST</td><td>oauth2/authorize</td></tr>
		<tr><td>GET</td><td>oauth2/clients</td></tr>
		<tr><td>POST</td><td>oauth2/clients</td></tr>
		<tr><td>DELETE</td><td>oauth2/clients/{client_id}</td></tr>
		<tr><td>GET</td><td>oauth2/clients/{client_id}</td></tr>
		<tr><td>PATCH</td><td>oauth2/clients/{client_id}</td></tr>
		<tr><td>GET</td><td>oauth2/clients/{client_id}/collaborators</td></tr>
		<tr><td>PATCH</td><td>oauth2/clients/{client_id}/collaborators</td></tr>
		<tr><td>POST</td><td>oauth2/clients/{client_id}/submit</td></tr>
		<tr><td>POST</td><td>oauth2/logout</td></tr>
		<tr><td>POST</td><td>oauth2/token</td></tr>
		<tr><th colspan="2">service.api.overdraft</th></tr>
		<tr><td>PUT</td><td>overdraft/bounce-payments</td></tr>
		<tr><td>GET</td><td>overdraft/credit-agreements</td></tr>
		<tr><td>POST</td><td>overdraft/credit-agreements</td></tr>
		<tr><td>GET</td><td>overdraft/eligibility</td></tr>
		<tr><td>PUT</td><td>overdraft/limit</td></tr>
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
		<tr><td>GET</td><td>payee/list</td></tr>
		<tr><td>GET</td><td>payee/sort-code</td></tr>
		<tr><td>GET</td><td>payee/validate</td></tr>
		<tr><td>PUT</td><td>payee/{id}/accounts/fps</td></tr>
		<tr><td>DELETE</td><td>payee/{id}</td></tr>
		<tr><th colspan="2">service.api.payment-limit</th></tr>
		<tr><td>GET</td><td>payment-limit/limits</td></tr>
		<tr><th colspan="2">service.api.payment-request</th></tr>
		<tr><td>PUT</td><td>payment-request/bill-splitting/create</td></tr>
		<tr><td>GET</td><td>payment-request/bill-splitting/list</td></tr>
		<tr><td>GET</td><td>payment-request/bill-splitting/{id}</td></tr>
		<tr><td>PUT</td><td>payment-request/{id}/decline</td></tr>
		<tr><td>PUT</td><td>payment-request/{id}/pay</td></tr>
		<tr><td>PUT</td><td>payment-request/create</td></tr>
		<tr><th colspan="2">service.api.payments</th></tr>
		<tr><td>PUT</td><td>payments/update</td></tr>
		<tr><th colspan="2">service.api.phone</th></tr>
		<tr><td>POST</td><td>phone/check-code</td></tr>
		<tr><td>POST</td><td>phone/send-code</td></tr>
		<tr><th colspan="2">service.api.pin-recovery</th></tr>
		<tr><td>PUT</td><td>pin-recovery/cancel</td></tr>
		<tr><td>POST</td><td>pin-recovery/retrieve</td></tr>
		<tr><td>POST</td><td>pin-recovery/start</td></tr>
		<tr><td>GET</td><td>pin-recovery/status</td></tr>
		<tr><th colspan="2">service.api.pin</th></tr>
		<tr><td>POST</td><td>pin/read</td></tr>
		<tr><td>POST</td><td>pin/sms</td></tr>
		<tr><td>GET</td><td>pin/sms_blocked</td></tr>
		<tr><th colspan="2">service.api.ping</th></tr>
		<tr><td>GET</td><td>ping/whoami</td></tr>
		<tr><th colspan="2">service.api.pots</th></tr>
		<tr><td>GET</td><td>pots</td></tr>
		<tr><td>PUT</td><td>pots</td></tr>
		<tr><td>GET</td><td>pots/committed/deposit-suggestion</td></tr>
		<tr><td>GET</td><td>pots/constraints</td></tr>
		<tr><td>PUT</td><td>pots/legal-documents/accept</td></tr>
		<tr><td>GET</td><td>pots/legal-documents/documents</td></tr>
		<tr><td>DELETE</td><td>pots/{id}</td></tr>
		<tr><td>GET</td><td>pots/{id}</td></tr>
		<tr><td>PATCH</td><td>pots/{id}</td></tr>
		<tr><td>PUT</td><td>pots/{id}/deposit</td></tr>
		<tr><td>GET</td><td>pots/{id}/details</td></tr>
		<tr><td>PUT</td><td>pots/{id}/withdraw</td></tr>
		<tr><th colspan="2">service.api.prepaid-migration-whitelist</th></tr>
		<tr><td>GET</td><td>prepaid-migration-whitelist</td></tr>
		<tr><th colspan="2">service.api.prepaid-refund</th></tr>
		<tr><td>GET</td><td>prepaid-refund/form</td></tr>
		<tr><th colspan="2">service.api.previous-addresses</th></tr>
		<tr><td>GET</td><td>previous-addresses</td></tr>
		<tr><td>PUT</td><td>previous-addresses</td></tr>
		<tr><th colspan="2">service.api.profile</th></tr>
		<tr><td>GET</td><td>profile</td></tr>
		<tr><td>PUT</td><td>profile/address</td></tr>
		<tr><td>GET</td><td>profile/address/search</td></tr>
		<tr><td>PUT</td><td>profile/phone/update-number</td></tr>
		<tr><td>POST</td><td>profile/update_address</td></tr>
		<tr><th colspan="2">service.api.pusher</th></tr>
		<tr><td>POST</td><td>pusher/auth</td></tr>
		<tr><th colspan="2">service.api.referral</th></tr>
		<tr><td>GET</td><td>referral/copy</td></tr>
		<tr><td>GET</td><td>referral/referral-tracker-copy</td></tr>
		<tr><th colspan="2">service.api.salary</th></tr>
		<tr><td>GET</td><td>salary/generate-salary-email</td></tr>
		<tr><th colspan="2">service.api.scheduled-payments</th></tr>
		<tr><td>GET</td><td>scheduled-payments/series</td></tr>
		<tr><td>POST</td><td>scheduled-payments/series/fps</td></tr>
		<tr><td>PUT</td><td>scheduled-payments/series/fps/{series_id}</td></tr>
		<tr><td>POST</td><td>scheduled-payments/series/pot-deposit</td></tr>
		<tr><td>POST</td><td>scheduled-payments/series/pot-withdrawal</td></tr>
		<tr><td>DELETE</td><td>scheduled-payments/series/{series_id}</td></tr>
		<tr><th colspan="2">service.api.secure-token</th></tr>
		<tr><td>POST</td><td>secure-token/enrol/inactive</td></tr>
		<tr><td>POST</td><td>secure-token/enrol/p2p_token_upgrade</td></tr>
		<tr><td>POST</td><td>secure-token/enrol/pin</td></tr>
		<tr><th colspan="2">service.api.self-disclosure</th></tr>
		<tr><td>PUT</td><td>self-disclosure/disclosure</td></tr>
		<tr><th colspan="2">service.api.signup</th></tr>
		<tr><td>PUT</td><td>signup/add-money/done</td></tr>
		<tr><td>PUT</td><td>signup/enable-p2p/enable</td></tr>
		<tr><td>PUT</td><td>signup/enable-p2p/skip</td></tr>
		<tr><td>POST</td><td>signup/initial-topup/skip</td></tr>
		<tr><td>PUT</td><td>signup/invite-friends/complete</td></tr>
		<tr><td>PUT</td><td>signup/invite-friends/skip</td></tr>
		<tr><td>POST</td><td>signup/joint-account/cancel</td></tr>
		<tr><td>POST</td><td>signup/joint-account/card-order/create</td></tr>
		<tr><td>GET</td><td>signup/joint-account/card-order/options</td></tr>
		<tr><td>POST</td><td>signup/joint-account/start</td></tr>
		<tr><td>GET</td><td>signup/joint-account/status</td></tr>
		<tr><td>POST</td><td>signup/legal-documents/accept</td></tr>
		<tr><td>GET</td><td>signup/legal-documents/documents</td></tr>
		<tr><td>POST</td><td>signup/marketing/subscribe</td></tr>
		<tr><td>GET</td><td>signup/negative-prepaid-balance-status</td></tr>
		<tr><td>PUT</td><td>signup/notifications</td></tr>
		<tr><td>PUT</td><td>signup/notify-friends</td></tr>
		<tr><td>PUT</td><td>signup/notify-friends/skip</td></tr>
		<tr><td>POST</td><td>signup/overdraft-maybe/skip</td></tr>
		<tr><td>POST</td><td>signup/overdraft-opt-in/skip</td></tr>
		<tr><td>PUT</td><td>signup/personalised-signup/complete</td></tr>
		<tr><td>POST</td><td>signup/personal-account/card-order/create</td></tr>
		<tr><td>GET</td><td>signup/personal-account/card-order/options</td></tr>
		<tr><td>POST</td><td>signup/personal-account/card-order/reorder</td></tr>
		<tr><td>GET</td><td>signup/personal-account/card-order/status</td></tr>
		<tr><td>POST</td><td>signup/personal-account/card/activate</td></tr>
		<tr><td>POST</td><td>signup/personal-account/skip-stage</td></tr>
		<tr><td>POST</td><td>signup/personal-account/start</td></tr>
		<tr><td>GET</td><td>signup/personal-account/status</td></tr>
		<tr><td>GET</td><td>signup/profile</td></tr>
		<tr><td>PUT</td><td>signup/profile</td></tr>
		<tr><td>PUT</td><td>signup/profile/address</td></tr>
		<tr><td>GET</td><td>signup/profile/address/search</td></tr>
		<tr><td>POST</td><td>signup/profile/commit</td></tr>
		<tr><td>POST</td><td>signup/profile/phone/send</td></tr>
		<tr><td>POST</td><td>signup/profile/phone/verify</td></tr>
		<tr><td>PUT</td><td>signup/provision-mdes/skip</td></tr>
		<tr><td>POST</td><td>signup/secure-token/enrol</td></tr>
		<tr><td>POST</td><td>signup/secure-token/skip</td></tr>
		<tr><td>PUT</td><td>signup/signup-prompt/complete</td></tr>
		<tr><th colspan="2">service.api.spending-breakdown</th></tr>
		<tr><td>GET</td><td>spending-breakdown/periods</td></tr>
		<tr><td>GET</td><td>spending-breakdown/periods/current</td></tr>
		<tr><td>PUT</td><td>spending-breakdown/periods/overrides</td></tr>
		<tr><td>PUT</td><td>spending-breakdown/periods/set-start-transaction</td></tr>
		<tr><td>GET</td><td>spending-breakdown/periods/{period_id}</td></tr>
		<tr><td>GET</td><td>spending-breakdown/periods/{period_id}/transactions</td></tr>
		<tr><td>GET</td><td>spending-breakdown/report</td></tr>
		<tr><td>GET</td><td>spending-breakdown/targets</td></tr>
		<tr><td>PUT</td><td>spending-breakdown/targets</td></tr>
		<tr><td>GET</td><td>spending-breakdown/transactions-to-start-period</td></tr>
		<tr><th colspan="2">service.api.spread-the-cost</th></tr>
		<tr><td>POST</td><td>spread-the-cost/applications</td></tr>
		<tr><td>POST</td><td>spread-the-cost/applications/submit</td></tr>
		<tr><td>GET</td><td>spread-the-cost/loans</td></tr>
		<tr><td>GET</td><td>spread-the-cost/loans/{loan_id}</td></tr>
		<tr><td>GET</td><td>spread-the-cost/loans/{loan_id}/credit-agreement</td></tr>
		<tr><td>GET</td><td>spread-the-cost/schedules</td></tr>
		<tr><th colspan="2">service.api.statement</th></tr>
		<tr><td>GET</td><td>statement/options/{id}</td></tr>
		<tr><td>GET</td><td>statement/{account_id}</td></tr>
		<tr><th colspan="2">service.api.stripe</th></tr>
		<tr><td>GET</td><td>stripe/cards</td></tr>
		<tr><td>POST</td><td>stripe/cards</td></tr>
		<tr><td>POST</td><td>stripe/inbound_p2p/charge</td></tr>
		<tr><td>POST</td><td>stripe/inbound_p2p/create</td></tr>
		<tr><td>POST</td><td>stripe/three_d_secure</td></tr>
		<tr><td>POST</td><td>stripe/top_up</td></tr>
		<tr><th colspan="2">service.api.subscriptions</th></tr>
		<tr><td>GET</td><td>subscriptions</td></tr>
		<tr><td>PUT</td><td>subscriptions/create</td></tr>
		<tr><td>PUT</td><td>subscriptions/edit</td></tr>
		<tr><td>GET</td><td>subscriptions/{subscription_id}</td></tr>
		<tr><td>PUT</td><td>subscriptions/{subscription_id}/resume</td></tr>
		<tr><td>PUT</td><td>subscriptions/{subscription_id}/stop</td></tr>
		<tr><th colspan="2">service.api.tabs</th></tr>
		<tr><td>GET</td><td>tabs</td></tr>
		<tr><td>POST</td><td>tabs</td></tr>
		<tr><td>PUT</td><td>tabs/{tab_id}/close</td></tr>
		<tr><td>PUT</td><td>tabs/{tab_id}/finish</td></tr>
		<tr><td>GET</td><td>tabs/{tab_id}/items</td></tr>
		<tr><td>PUT</td><td>tabs/{tab_id}/items</td></tr>
		<tr><td>PUT</td><td>tabs/{tab_id}/items/add</td></tr>
		<tr><td>DELETE</td><td>tabs/{tab_id}/items/{item_id}</td></tr>
		<tr><td>PUT</td><td>tabs/{tab_id}/leave</td></tr>
		<tr><td>PUT</td><td>tabs/{tab_id}/participants/add</td></tr>
		<tr><td>PUT</td><td>tabs/{tab_id}/pay-all</td></tr>
		<tr><td>PUT</td><td>tabs/{tab_id}/send-reminder</td></tr>
		<tr><th colspan="2">service.api.targets</th></tr>
		<tr><td>GET</td><td>targets</td></tr>
		<tr><td>PUT</td><td>targets</td></tr>
		<tr><th colspan="2">service.api.tax-residency</th></tr>
		<tr><td>POST</td><td>tax-residency/no-tin</td></tr>
		<tr><td>GET</td><td>tax-residency/status</td></tr>
		<tr><td>POST</td><td>tax-residency/submit</td></tr>
		<tr><td>POST</td><td>tax-residency/update-self-certification</td></tr>
		<tr><td>POST</td><td>tax-residency/update-tin</td></tr>
		<tr><th colspan="2">service.api.topup</th></tr>
		<tr><td>GET</td><td>topup/limits</td></tr>
		<tr><td>GET</td><td>topup/status</td></tr>
		<tr><th colspan="2">service.api.transaction-export</th></tr>
		<tr><td>GET</td><td>transaction-export/csv</td></tr>
		<tr><td>GET</td><td>transaction-export/qif</td></tr>
		<tr><th colspan="2">service.api.transaction-widgets</th></tr>
		<tr><td>GET</td><td>transaction-widgets/{transaction_id}</td></tr>
		<tr><th colspan="2">service.api.transactions</th></tr>
		<tr><td>GET</td><td>transactions</td></tr>
		<tr><td>POST</td><td>transactions/update-metadata</td></tr>
		<tr><td>PATCH</td><td>transactions/{transaction_id}</td></tr>
		<tr><th colspan="2">service.api.transferwise</th></tr>
		<tr><td>POST</td><td>transferwise/account</td></tr>
		<tr><td>GET</td><td>transferwise/account-requirements</td></tr>
		<tr><td>POST</td><td>transferwise/auth</td></tr>
		<tr><td>POST</td><td>transferwise/auth-callback</td></tr>
		<tr><td>GET</td><td>transferwise/quote</td></tr>
		<tr><td>POST</td><td>transferwise/quote</td></tr>
		<tr><td>GET</td><td>transferwise/supported-currencies</td></tr>
		<tr><td>POST</td><td>transferwise/transfer</td></tr>
		<tr><td>GET</td><td>transferwise/transfer-requirements</td></tr>
		<tr><td>GET</td><td>transferwise/user</td></tr>
		<tr><th colspan="2">service.api.trip</th></tr>
		<tr><td>POST</td><td>trip/purpose</td></tr>
		<tr><td>GET</td><td>trip/{trip_id}</td></tr>
		<tr><th colspan="2">service.api.user-images</th></tr>
		<tr><td>DELETE</td><td>user-images/image</td></tr>
		<tr><td>GET</td><td>user-images/profile_picture/{user_id}</td></tr>
		<tr><td>PUT</td><td>user-images/register</td></tr>
		<tr><td>POST</td><td>user-images/upload</td></tr>
		<tr><th colspan="2">service.api.user-settings</th></tr>
		<tr><td>GET</td><td>user-settings</td></tr>
		<tr><td>PUT</td><td>user-settings</td></tr>
		<tr><td>PUT</td><td>user-settings/gambling-block/disable</td></tr>
		<tr><td>PUT</td><td>user-settings/gambling-block/enable</td></tr>
		<tr><th colspan="2">service.api.waitlist</th></tr>
		<tr><td>GET</td><td>waitlist</td></tr>
		<tr><td>POST</td><td>waitlist/signup</td></tr>
		<tr><th colspan="2">service.api.web-auth</th></tr>
		<tr><td>POST</td><td>web-auth/authorize</td></tr>
		<tr><th colspan="2">service.api.webhooks</th></tr>
		<tr><td>GET</td><td>webhooks</td></tr>
		<tr><td>POST</td><td>webhooks</td></tr>
		<tr><td>DELETE</td><td>webhooks/{webhook_id}</td></tr>
		<tr><th colspan="2">service.api.webview-validation</th></tr>
		<tr><td>PUT</td><td>webview-validation/validate</td></tr>
	</tbody>
</table>
