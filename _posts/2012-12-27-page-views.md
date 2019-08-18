---
category: Page Views
title: 'Page List'

layout: nil
---

### Common Properties
```
    title: window.location.title
    url: window.location.url
    path: window.location.path
    referrer: window.location.referrer
    search: window.location.search
    
```

* The headers must include a **valid authentication token**.

### Response

Sends back a collection of things.

```Status: 200 OK```
```{
    {
        id: thing_1,
        name: 'My first thing'
    },
    {
        id: thing_2,
        name: 'My second thing'
    }
}```

For errors responses, see the [response status codes documentation](#response-status-codes).