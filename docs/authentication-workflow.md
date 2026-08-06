# Authentication Workflow

## Overview

This document defines how users authenticate and access the Lafia Property Agents platform.

---

## User Types

The platform supports three user roles:

- Visitor
- Agent
- Administrator

---

## Agent Registration

A new agent provides:

- Full Name
- Phone Number
- Email Address
- Password

The system validates the information and creates an account.

Password must be encrypted before storage.

---

## Agent Login

## Agent Login

Agents can log in after creating an account.

Depending on their application status, they will see different dashboards.

### Account Created

Status: Incomplete

The agent can:

- Complete profile
- Upload profile photo
- Upload government ID
- View registration progress
- Contact support

The agent cannot:

- Receive a Membership ID
- Appear in public search
- Download a membership card
- Download a membership certificate
- Access member-only features

---

### Profile Submitted

Status: Pending Review

The dashboard displays:

"Your application is under review."

The agent can:

- View submitted information
- Edit information if requested by the administrator
- Track application status

---

### Approved

Status: Approved – Payment Required

The dashboard displays a "Pay Membership Fee" button.

The agent cannot access member benefits until payment is confirmed.

---

### Active Member

After successful payment:

The dashboard unlocks:

- Membership ID
- Verified Badge
- Digital Membership Card
- Membership Certificate
- Renewal Section
- Membership Expiry Countdown

## Administrator Login

Administrators log in using:

- Email
- Password

After successful authentication:

- Redirect to the Admin Dashboard.

---

## Forgot Password

The user enters their registered email address.

The system sends a password reset link.

The user creates a new password.

---

## Password Requirements

Passwords must:

- Be at least 8 characters long.
- Contain uppercase and lowercase letters.
- Contain at least one number.
- Contain at least one special character.

---

## Account Security

The system shall:

- Encrypt all passwords.
- Prevent unauthorized access.
- Log users out after a period of inactivity.
- Record login date and time.

---

## Access Control

Visitors:
- Public pages only.

Agents:
- Agent Dashboard only.

Administrators:
- Full access to the Admin Dashboard.

Unauthorized users shall receive an "Access Denied" message.
