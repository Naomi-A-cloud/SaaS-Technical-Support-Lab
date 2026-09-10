# HTTP Status Code Troubleshooting

## 200 OK

The request was successful.

## 400 Bad Request

The server could not process the request because the request was invalid.

Common causes:

- Invalid parameters
- Incorrect request format
- Missing required information

## 401 Unauthorized

Authentication is required or the authentication credentials are invalid.

Common causes:

- Expired session
- Invalid authentication token
- Missing credentials

## 403 Forbidden

The server understood the request but the user does not have permission to access the resource.

Common causes:

- Missing permissions
- Incorrect role
- Access policy restriction

## 404 Not Found

The requested resource could not be found.

Common causes:

- Incorrect URL
- Deleted resource
- Invalid endpoint

## 429 Too Many Requests

The client has exceeded the allowed request rate.

Common causes:

- Excessive API requests
- Rate limiting
- Automated processes making too many requests

## 500 Internal Server Error

A server-side error occurred while processing the request.

Common causes:

- Application failure
- Backend processing error
- Unexpected server exception

## Support Approach

When investigating HTTP errors:

1. Identify the status code.
2. Identify the affected endpoint.
3. Determine whether the issue affects one or multiple users.
4. Review relevant logs.
5. Attempt to reproduce the issue.
6. Determine whether escalation is required.