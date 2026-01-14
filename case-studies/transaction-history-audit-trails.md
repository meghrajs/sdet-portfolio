# Transaction History & Audit Trails

## Context
Built a transaction history view that groups purchases and refunds under parent transactions to improve financial clarity and reduce support back-and-forth.

## My Role
- Designed data shape for grouping refunds under the original payment
- Added backend logic to return clean JSON for UI expansion/accordion views
- Ensured auditability and consistency for vendor/customer support use-cases

## Testing & Reliability (SDET Angle)
- Tested grouping rules and edge cases (partial refunds, multiple refunds, canceled subscriptions)
- Validated pagination/sorting integrity
- Used logging + deterministic fixtures to reproduce issues quickly

## Outcomes
- Better support workflows (faster resolution, fewer disputes)
- Cleaner reporting and financial audit readiness
