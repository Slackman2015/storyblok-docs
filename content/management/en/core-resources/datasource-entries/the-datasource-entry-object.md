---
title: The Datasource Entry Object
---

| Property | Description |
|---|---|
| `id` | Numeric Unique ID |
| `name` | The key which will be used to resolve the given value |
| `value` | The actual value for the provided key |
| `datasource_id` | Numeric ID of connected datasource |

;examplearea

Example Object

```json
{ 
  "datasource_entry" : {
    "id": 52,
    "name": "newsletter_text",
    "value": "Subscribe to our newsletter to make sure you don’t miss anything.",
    "datasource_id": ""
  }
}
```