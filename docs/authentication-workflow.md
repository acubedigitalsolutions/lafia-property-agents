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

Agents log in using:

- Email Address
- Password

If the credentials are correct:

- Access is granted to the Agent Dashboard.

If incorrect:

- Display "Invalid email or password."

---

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
