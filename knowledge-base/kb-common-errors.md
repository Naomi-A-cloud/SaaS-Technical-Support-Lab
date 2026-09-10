# Common SaaS Errors

| Error | Meaning | Initial Action |
|---|---|---|
| 400 | Bad Request | Check request parameters |
| 401 | Unauthorized | Check authentication |
| 403 | Forbidden | Check permissions |
| 404 | Not Found | Verify resource or URL |
| 429 | Rate Limited | Check request frequency |
| 500 | Server Error | Review application logs |

## Support Principle

Do not assume the error message identifies the root cause.

Use the error as an investigation starting point and correlate it with:

- User impact
- Application behaviour
- Logs
- Request timestamps
- API responses
- Recent changes