# Browser Troubleshooting

## Purpose

Browser troubleshooting helps determine whether a SaaS issue originates from the customer's local browser environment.

## Standard Checks

1. Confirm the browser version.
2. Test the application in private/incognito mode.
3. Clear cache and cookies.
4. Disable extensions temporarily.
5. Test another supported browser.
6. Confirm JavaScript is enabled.
7. Check whether the issue occurs on another device.

## Diagnostic Logic

If the issue disappears in private browsing, investigate:

- Cached sessions
- Cookies
- Browser extensions
- Stored site data

If the issue occurs across multiple browsers and devices, investigate the SaaS application or backend services.

## Security Consideration

Never ask customers to provide passwords, MFA codes, API secrets, or other credentials during troubleshooting.