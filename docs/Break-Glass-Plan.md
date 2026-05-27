# Break-Glass Plan

## Purpose

This document defines the break-glass account plan for the PIM privileged access lab. Break-glass accounts are emergency administrator accounts used when normal administrator access is unavailable.

## Why Break-Glass Accounts Matter

If Conditional Access, PIM, MFA, or another identity control causes unexpected access issues, a break-glass account can help regain access to the tenant.

## Lab Break-Glass Account

| Account | Purpose | Daily Use? |
|---|---|---|
| breakglass01 | Emergency tenant access | No |

## Break-Glass Rules

1. Do not use break-glass accounts for daily administration.
2. Use strong passwords.
3. Store credentials securely.
4. Monitor sign-in activity.
5. Keep the number of break-glass accounts limited.
6. Exclude carefully from policies that could cause lockout.
7. Review break-glass access regularly.

## PIM Relationship

PIM helps reduce standing privileged access for normal admin users. Break-glass accounts exist separately for emergency recovery and should be documented carefully.

## Monitoring Notes

Break-glass account activity should be monitored for:

- Successful sign-ins
- Failed sign-ins
- Password changes
- Role changes
- Unusual locations
- Unexpected activity

## Summary

Break-glass accounts reduce the risk of administrative lockout, but they also create risk if not protected. They should be documented, monitored, and rarely used.
