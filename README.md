<table>
	<thead>
		<tr>
			<th>Method</th>
			<th>Path</th>
		</tr>
	</thead>
	<tbody>
		<tr><th colspan="2">service.api.account-settings</th></tr>
		<tr><td>GET</td><td>account-settings</td></tr>
		<tr><td>PUT</td><td>account-settings</td></tr>
		<tr><th colspan="2">service.api.accounts</th></tr>
		<tr><td>GET</td><td>accounts</td></tr>
		<tr><th colspan="2">service.api.analytics</th></tr>
		<tr><td>POST</td><td>analytics/track</td></tr>
		<tr><th colspan="2">service.api.attachment</th></tr>
		<tr><td>POST</td><td>attachment/deregister</td></tr>
		<tr><td>POST</td><td>attachment/register</td></tr>
		<tr><td>POST</td><td>attachment/upload</td></tr>
		<tr><th colspan="2">service.api.bacs-direct-debits</th></tr>
		<tr><td>GET</td><td>bacs-direct-debits/instructions</td></tr>
		<tr><td>PUT</td><td>bacs-direct-debits/instructions/{direct_debit_id}/cancel</td></tr>
		<tr><th colspan="2">service.api.balance</th></tr>
		<tr><td>GET</td><td>balance</td></tr>
		<tr><td>GET</td><td>balance/graph</td></tr>
		<tr><td>GET</td><td>balance/limits</td></tr>
		<tr><th colspan="2">service.api.branches</th></tr>
		<tr><td>GET</td><td>branches</td></tr>
		<tr><th colspan="2">service.api.card-activation</th></tr>
		<tr><td>POST</td><td>card-activation/activate</td></tr>
		<tr><th colspan="2">service.api.card-replacement</th></tr>
		<tr><td>POST</td><td>card-replacement/activate</td></tr>
		<tr><td>POST</td><td>card-replacement/order</td></tr>
		<tr><th colspan="2">service.api.card-security-code-challenge</th></tr>
		<tr><td>GET</td><td>card-security-code-challenge/details</td></tr>
		<tr><td>POST</td><td>card-security-code-challenge/skip</td></tr>
		<tr><td>POST</td><td>card-security-code-challenge/submit</td></tr>
		<tr><th colspan="2">service.api.card</th></tr>
		<tr><td>GET</td><td>card/list</td></tr>
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
		<tr><th colspan="2">service.api.chat-user-selection</th></tr>
		<tr><td>GET</td><td>chat-user-selection/query-urgency</td></tr>
		<tr><th colspan="2">service.api.config</th></tr>
		<tr><td>GET</td><td>config</td></tr>
		<tr><th colspan="2">service.api.contact-discovery</th></tr>
		<tr><td>GET</td><td>contact-discovery/query</td></tr>
		<tr><td>GET</td><td>contact-discovery/users</td></tr>
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
		<tr><th colspan="2">service.api.geocode</th></tr>
		<tr><td>GET</td><td>geocode/postal-code-lookup</td></tr>
		<tr><th colspan="2">service.api.golden-ticket</th></tr>
		<tr><td>GET</td><td>golden-ticket/{id}</td></tr>
		<tr><td>PUT</td><td>golden-ticket/{id}/claim</td></tr>
		<tr><th colspan="2">service.api.help</th></tr>
		<tr><td>GET</td><td>help/content/categories</td></tr>
		<tr><td>GET</td><td>help/content/categories/{id}</td></tr>
		<tr><td>GET</td><td>help/content/search</td></tr>
		<tr><td>GET</td><td>help/content/trending</td></tr>
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
		<tr><th colspan="2">service.api.intercom</th></tr>
		<tr><td>GET</td><td>intercom/tokens/{intercom_app_id}</td></tr>
		<tr><th colspan="2">service.api.merchant</th></tr>
		<tr><td>GET</td><td>merchant/search?user_location=0</td></tr>
		<tr><td>POST</td><td>merchant/{merchant_id}/propose-edit</td></tr>
		<tr><th colspan="2">service.api.news</th></tr>
		<tr><td>GET</td><td>news</td></tr>
		<tr><th colspan="2">service.api.oauth2</th></tr>
		<tr><td>POST</td><td>oauth2/authorize</td></tr>
		<tr><td>GET</td><td>oauth2/clients/{client_id}</td></tr>
		<tr><td>POST</td><td>oauth2/logout</td></tr>
		<tr><td>POST</td><td>oauth2/token</td></tr>
		<tr><th colspan="2">service.api.overdraft</th></tr>
		<tr><td>GET</td><td>overdraft/credit-agreements</td></tr>
		<tr><td>POST</td><td>overdraft/credit-agreements</td></tr>
		<tr><td>PUT</td><td>overdraft/limit</td></tr>
		<tr><td>GET</td><td>overdraft/status</td></tr>
		<tr><th colspan="2">service.api.p2p</th></tr>
		<tr><td>POST</td><td>p2p/recipients</td></tr>
		<tr><td>POST</td><td>p2p/transfer</td></tr>
		<tr><th colspan="2">service.api.payee</th></tr>
		<tr><td>GET</td><td>payee/validate</td></tr>
		<tr><th colspan="2">service.api.payment-limit</th></tr>
		<tr><td>GET</td><td>payment-limit/limits</td></tr>
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
		<tr><td>GET</td><td>pots/listV1</td></tr>
		<tr><td>DELETE</td><td>pots/{id}</td></tr>
		<tr><td>GET</td><td>pots/{id}</td></tr>
		<tr><td>PATCH</td><td>pots/{id}</td></tr>
		<tr><td>PUT</td><td>pots/{id}/deposit</td></tr>
		<tr><td>PUT</td><td>pots/{id}/withdraw</td></tr>
		<tr><th colspan="2">service.api.prepaid-migration-whitelist</th></tr>
		<tr><td>GET</td><td>prepaid-migration-whitelist</td></tr>
		<tr><th colspan="2">service.api.prepaid-refund</th></tr>
		<tr><td>GET</td><td>prepaid-refund/form</td></tr>
		<tr><th colspan="2">service.api.profile</th></tr>
		<tr><td>GET</td><td>profile</td></tr>
		<tr><td>PUT</td><td>profile/address</td></tr>
		<tr><td>GET</td><td>profile/address/search</td></tr>
		<tr><td>POST</td><td>profile/update_address</td></tr>
		<tr><th colspan="2">service.api.scheduled-payments</th></tr>
		<tr><td>GET</td><td>scheduled-payments/series</td></tr>
		<tr><td>POST</td><td>scheduled-payments/series/fps</td></tr>
		<tr><td>DELETE</td><td>scheduled-payments/series/{series_id}</td></tr>
		<tr><th colspan="2">service.api.secure-token</th></tr>
		<tr><td>POST</td><td>secure-token/enrol/pin</td></tr>
		<tr><th colspan="2">service.api.signup</th></tr>
		<tr><td>POST</td><td>signup/initial-topup/skip</td></tr>
		<tr><td>POST</td><td>signup/legal-documents/accept</td></tr>
		<tr><td>GET</td><td>signup/legal-documents/documents</td></tr>
		<tr><td>POST</td><td>signup/marketing/subscribe</td></tr>
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
		<tr><td>POST</td><td>signup/secure-token/skip</td></tr>
		<tr><th colspan="2">service.api.spending-breakdown</th></tr>
		<tr><td>GET</td><td>spending-breakdown/periods</td></tr>
		<tr><td>GET</td><td>spending-breakdown/periods/{period_id}</td></tr>
		<tr><td>GET</td><td>spending-breakdown/periods/{period_id}/transactions</td></tr>
		<tr><th colspan="2">service.api.statement</th></tr>
		<tr><td>GET</td><td>statement/options/{id}</td></tr>
		<tr><td>GET</td><td>statement/{id}</td></tr>
		<tr><th colspan="2">service.api.stripe</th></tr>
		<tr><td>GET</td><td>stripe/cards</td></tr>
		<tr><td>POST</td><td>stripe/cards</td></tr>
		<tr><td>POST</td><td>stripe/inbound_p2p/charge</td></tr>
		<tr><td>POST</td><td>stripe/inbound_p2p/create</td></tr>
		<tr><td>POST</td><td>stripe/three_d_secure</td></tr>
		<tr><td>POST</td><td>stripe/top_up</td></tr>
		<tr><th colspan="2">service.api.targets</th></tr>
		<tr><td>GET</td><td>targets</td></tr>
		<tr><th colspan="2">service.api.tax-residency</th></tr>
		<tr><td>POST</td><td>tax-residency/no-tin</td></tr>
		<tr><td>GET</td><td>tax-residency/status</td></tr>
		<tr><td>POST</td><td>tax-residency/submit</td></tr>
		<tr><td>POST</td><td>tax-residency/update-self-certification</td></tr>
		<tr><td>POST</td><td>tax-residency/update-tin</td></tr>
		<tr><th colspan="2">service.api.topup</th></tr>
		<tr><td>GET</td><td>topup/limits</td></tr>
		<tr><td>GET</td><td>topup/status</td></tr>
		<tr><th colspan="2">service.api.transactions</th></tr>
		<tr><td>GET</td><td>transactions</td></tr>
		<tr><td>POST</td><td>transactions/update-metadata</td></tr>
		<tr><td>PATCH</td><td>transactions/{transaction_id}</td></tr>
		<tr><th colspan="2">service.api.user-images</th></tr>
		<tr><td>DELETE</td><td>user-images/image</td></tr>
		<tr><td>GET</td><td>user-images/profile_picture/{user_id}</td></tr>
		<tr><td>PUT</td><td>user-images/register</td></tr>
		<tr><td>POST</td><td>user-images/upload</td></tr>
		<tr><th colspan="2">service.api.user-settings</th></tr>
		<tr><td>PUT</td><td>user-settings</td></tr>
		<tr><th colspan="2">service.api.waitlist</th></tr>
		<tr><td>GET</td><td>waitlist</td></tr>
		<tr><td>POST</td><td>waitlist/signup</td></tr>
		<tr><th colspan="2">service.api.web-auth</th></tr>
		<tr><td>POST</td><td>web-auth/authorize</td></tr>
		<tr><th colspan="2">service.api.webhooks</th></tr>
		<tr><td>GET</td><td>webhooks</td></tr>
		<tr><td>POST</td><td>webhooks</td></tr>
		<tr><td>DELETE</td><td>webhooks/{webhook_id}</td></tr>
	</tbody>
</table>
