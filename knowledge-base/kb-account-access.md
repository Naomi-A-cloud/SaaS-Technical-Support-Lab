# Account Access Troubleshooting

## Common Symptoms

- Unable to log in
- Password reset failure
- MFA failure
- Account locked
- Permission denied

## Investigation Sequence

### Authentication

Confirm that the user can authenticate successfully.

### Account Status

Confirm that the account is active and not locked.

### MFA

Check whether MFA is functioning correctly.

### Permissions

If authentication succeeds but access is denied, check the user's role and permissions.

### Browser

If the problem appears isolated to one environment, test another browser or private browsing session.

## Security Rules

Support engineers should never request:

- Passwords
- MFA codes
- API keys
- Authentication tokens
- Other secrets

## Escalation

Escalate when:

- Multiple users are affected
- Authentication services are unavailable
- Backend errors are identified
- A security-related event is suspected