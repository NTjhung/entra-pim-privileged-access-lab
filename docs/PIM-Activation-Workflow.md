# PIM Activation Workflow

## Purpose

This document explains the privileged role activation workflow used in the Microsoft Entra PIM lab.

## Activation Workflow

1. User signs in to Microsoft Entra admin center.
2. User opens Privileged Identity Management.
3. User views eligible roles.
4. User selects the role to activate.
5. User provides activation justification.
6. User selects activation duration.
7. User activates the role.
8. Role becomes active for a limited time.
9. Activity is captured in audit history.

## Example Activation

| Field | Example |
|---|---|
| User | PIM Test User |
| Role | Groups Administrator |
| Assignment Type | Eligible |
| Activation Duration | 1 hour |
| Justification | Need temporary access to validate group membership changes for IAM lab |
| Result | Role activated temporarily |

## Activation Controls

Recommended controls:

- Require justification
- Require MFA where possible
- Limit activation duration
- Monitor activation history
- Review privileged role assignments regularly

## Why This Matters

Privileged access should not be permanently active unless required. PIM helps reduce unnecessary standing access and creates a record of when privileged access is activated.

## Audit Notes

The activation record should be retained as audit evidence. It helps show who activated privileged access, when it was activated, and why it was needed.
