# Experiment 9: Authentication Security Review

## Aim

Review defensive controls that reduce the risk of repeated, unauthorized authentication attempts in an authorized lab.

## Scope and safety

This public report does not include password-guessing commands, target identifiers, wordlists, or credential values. The screenshots are fully redacted to avoid publishing operational details or credentials.

## Requirements

- An isolated lab environment with explicit authorization
- A test account that contains no real or reused credentials
- Access to authentication and security logs

## Procedure

1. Confirm the test environment and account are isolated and approved for the exercise.
2. Review the service's authentication protections and relevant logs without publishing credentials or target details.
3. Document defensive observations, such as whether repeated failures are detected, rate-limited, or alerted on.
4. Remove any test credentials and preserve only sanitized notes.

## Redacted screenshots

The original screenshots contained operational details and credentials, so their contents are withheld in this public copy.

- ![Redacted authentication-review screenshot 1](<Screenshot 2026-11-13 151222.png>)
- ![Redacted authentication-review screenshot 2](<Screenshot 2026-11-13 151312.png>)
- ![Redacted authentication-review screenshot 3](<Screenshot 2026-11-13 152144.png>)

## Result

The exercise emphasizes that authentication services should use unique strong credentials, multi-factor authentication where available, rate limiting, monitoring, and alerting. Raw credential-testing evidence is intentionally not distributed.

## Conclusion

Authentication testing should be authorized, isolated, and focused on improving defenses. Do not test credentials against systems without explicit permission.
