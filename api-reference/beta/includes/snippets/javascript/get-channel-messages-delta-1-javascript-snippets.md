---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/teams/{id}/channels/{id}/messages/delta')
	.version('beta')
	.top(2)
	.get();

```