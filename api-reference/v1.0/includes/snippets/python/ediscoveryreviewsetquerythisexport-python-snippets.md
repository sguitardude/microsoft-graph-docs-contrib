---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)

request_body = ExportPostRequestBody(
	output_name = "Export reviewset query via API",
	description = "Export for the Contoso investigation 2",
	export_options = ExportOptions.OriginalFiles | ExportOptions.Tags,
	export_structure = ExportFileStructure.Directory,
)

await graph_client.security.cases.ediscovery_cases.by_ediscovery_case_id('ediscoveryCase-id').review_sets.by_ediscovery_review_set_id('ediscoveryReviewSet-id').queries.by_ediscovery_review_set_query_id('ediscoveryReviewSetQuery-id').microsoft_graph_security_export.post(request_body)


```