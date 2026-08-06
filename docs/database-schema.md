# Database Schema

## Tables

1. Users
2. Agents
3. Locations
4. Subscriptions
5. Property Requests
6. Reports
7. Reviews
8. News
9. Settings

---

## Users

- id
- name
- email
- password
- role
- created_at
- updated_at

---

## Agents

- id
- membership_id
- full_name
- phone
- email
- government_id
- profile_photo
- bio
- years_experience
- office_address
- location_id
- approval_status
- membership_status
- member_since
- subscription_expiry
- created_at
- updated_at

---

## Locations

- id
- location_name
- lga
- created_at
- updated_at

---

## Subscriptions

- id
- agent_id
- amount
- payment_reference
- payment_date
- expiry_date
- status
- created_at
- updated_at
