# Changelog

## Unreleased

- Configure public booking rules and bilingual, ordered visit reasons in the administrator panel; check and hold the complete duration for each reason.
- Store a size-limited validated clinic logo and expose it on a public, clinic-scoped image route; reuse clinic schedule closures.

- Render the reception accept action with the primary button style.
- Highlight available dates by week and group times by morning and afternoon. Require a validated international or Spanish phone number.
- Configure public page logo, color and bilingual text from reception settings; show the requested time in confirmation and email.

- Add a standalone static public booking and confirmation widget and clinic-bound, single-use ALTCHA v2 challenges. Public request clients must now provide an ALTCHA solution.

- Reception chooses professional, optional cabinet and duration, with per-reason defaults and clinic-wide conflict rechecks; patient contact fields are prefilled and matching contacts suggested.
- Show a permission-scoped count of confirmed pending requests in navigation.

- Refresh locked rows before evaluating request decisions or dispatch state.

- Queue encrypted confirmation and rejection emails in the request transaction and send only after commit.

- Add paginated reception inbox with explicit patient selection, acceptance and rejection.
- Exclude expired requests from the inbox and refuse decisions after expiration.

- Add optional, disabled-by-default online booking requests for one clinic calendar.
- Add transaction-scoped booking locks and recheck active agenda appointments.
- Add expiring confirmation tokens, reception decisions and retention cleanup.
- Add shared pseudonymous abuse counters and TLS-only email delivery.
- Document the concurrent agenda writer limitation tracked by issue #905.
