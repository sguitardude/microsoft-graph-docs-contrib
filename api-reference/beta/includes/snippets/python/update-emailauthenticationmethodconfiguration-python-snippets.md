---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = EmailAuthenticationMethodConfiguration(
	odata_type = "#microsoft.graph.emailAuthenticationMethodConfiguration",
	allow_external_id_to_use_email_otp = ExternalEmailOtpState.Disabled,
)

result = await graph_client.policies.authentication_methods_policy.authentication_method_configurations.by_authentication_method_configuration_id('authenticationMethodConfiguration-id').patch(request_body)


```