
# PIM Role Assignment Plan

## Purpose

This document defines the role assignment plan for the Microsoft Entra PIM privileged access lab. The goal is to reduce standing administrator access by assigning privileged roles as eligible instead of permanently active.

## Role Assignment Strategy

Privileged access should be assigned only when needed and should be limited by time, role, and business need.

## Roles Used in This Lab

| Role | Purpose | Risk Level |
|---|---|---|
| Groups Administrator | Manage groups and group memberships | Medium |
| User Administrator | Manage users and user properties | High |
| Authentication Administrator | Manage authentication methods | High |

## Recommended Lab Role

For the first test, use:

| Test User | Role | Assignment Type |
|---|---|---|
| PIM Test User | Groups Administrator | Eligible |

Groups Administrator is a good first lab role because it demonstrates privileged access without using Global Administrator.

## Assignment Rules

1. Avoid permanent active administrator assignments when possible.
2. Use eligible assignments for privileged access.
3. Require justification during activation.
4. Use time-limited access.
5. Review privileged assignments regularly.
6. Keep break-glass accounts documented and protected.

## Why Eligible Access Matters

Eligible access reduces standing privilege. The user does not have the admin role active all the time. The user must activate the role when needed and provide a reason for activation.

## Evidence to Collect

- PIM role list
- Eligible role assignment
- Role settings
- Activation screen
- Justification screen
- Active role after activation
- Audit history
