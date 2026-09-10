# Troubleshooting Evidence

## Authentication Investigation

### Evidence

Authentication logs showed:

- Invalid session token
- Authentication rejection
- Later successful authentication

### Interpretation

The evidence supported a browser session issue rather than a platform-wide authentication outage.

---

## MFA Investigation

### Evidence

Authentication logs showed:

`reason=time_drift`

### Interpretation

The customer's authentication device time was not synchronized.

---

## API Investigation

### Evidence

API logs showed:

`HTTP 429 Too Many Requests`

and:

`Rate limit exceeded`

### Interpretation

The API client exceeded the configured request rate.

---

## Application Investigation

### Evidence

Application logs showed:

`HTTP response status=500`

### Interpretation

The issue was server-side and required engineering escalation.

---

## Performance Investigation

### Evidence

Application logs showed:

`duration=3120ms`

### Interpretation

The Reports endpoint showed elevated response latency and required additional investigation.