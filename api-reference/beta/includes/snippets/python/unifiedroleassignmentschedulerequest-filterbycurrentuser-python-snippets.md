---
description: "Automatically generated file. DO NOT MODIFY"
---

```python



graph_client = GraphServiceClient(credentials, scopes)


result = await graph_client.role_management.directory.role_assignment_schedule_requests.filter_by_current_user_with_on("principal").get()


```