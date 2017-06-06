## Error Codes & Responses

---

***HTTP Status Codes***

Code | Text | Description
--- | --- | ---
200 | OK | Success!
304 | Not Modified | There was no new data to return.
400 | Bad Request | The request was invalid or cannot be otherwise served.
401 | Unauthorized | Missing or incorrect authentication credentials.
403 | Forbidden | N/A
404 | Not Found | The URI requested is invalid or the resource requested does not exists.
500 | Internal Server Error | Something is broken.
502 | Bad Gateway | Server is down or being upgraded.

***Error Messages***

When API returns error messages, it does so in JSON format. For example, an error might look like this:
```
  {
    "code": 404,
    "message": "Resource not found"
  }
```
