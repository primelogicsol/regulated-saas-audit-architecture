# Audit Architecture

A regulated SaaS audit architecture should preserve user activity, system changes, evidence links, approval decisions, and data governance events.

## Core Audit Events

- User login
- Record creation
- Record update
- Evidence upload
- Review comment
- Approval event
- Export event
- Permission change
- Submission status change

## Required Event Fields

- Event ID
- Actor ID
- Actor role
- Timestamp
- Action type
- Target object
- Previous value summary
- New value summary
- Reason or comment
- Evidence link where applicable

## Design Principle

Audit records should support accountability, review, reconstruction, and defensible decision history.
