# Admin Dashboard

## Overview

The Admin Dashboard is the central control panel for Lafia Property Agents.

Only authorized administrators can access the Admin Dashboard.

It provides tools for managing agents, memberships, payments, property requests, complaints, news, locations, analytics, and platform settings.

---

# 1. Dashboard Overview

The main dashboard displays:

- Total Registered Agents
- Active Members
- Pending Applications
- Memberships Expiring Within 30 Days
- Expired Memberships
- Suspended Agents
- Featured Agents
- Property Requests
- Open Complaints
- Total Revenue
- Monthly Revenue

The dashboard should provide quick links to important actions.

---

# 2. Agent Management

Administrators can:

- View all agents
- Search agents
- Filter agents by location
- View agent profiles
- Review applications
- Approve applications
- Reject applications
- Request additional information
- Suspend agents
- Reactivate agents
- View agent membership history
- View verification history
- View Trust Score
- View Profile Strength
- View Response Rate
- Manage Featured Agent status

Every important administrative action should be recorded in the Audit Log.

---

# 3. Membership Management

Administrators can:

- View active memberships
- View pending memberships
- View expired memberships
- View suspended memberships
- View membership history
- Confirm successful payments
- Review failed payments
- Renew memberships
- Suspend memberships
- Reactivate memberships
- View Membership IDs
- View Membership Levels
- View Verified Since date
- View Last Verified date

The system automatically updates membership status based on payment and expiry dates.

---

# 4. Financial Dashboard

The Financial Dashboard displays:

- Total Revenue
- Today's Revenue
- Weekly Revenue
- Monthly Revenue
- Annual Revenue
- Membership Revenue
- Featured Agent Revenue
- Successful Payments
- Failed Payments
- Pending Payments
- Refunded Payments

Administrators can:

- Search payments
- Filter payments by date
- View payment details
- View payment reference
- View agent associated with a payment
- Export financial records

Payment records must not be deleted without an appropriate administrative process.

---

# 5. Property Requests

Administrators can:

- View property requests
- Search requests
- Filter requests by location
- Filter requests by property type
- View request details
- Update request status
- Mark requests as completed
- Archive completed requests

Future functionality may allow administrators to assign requests to suitable agents.

---

# 6. Complaints & Reports

Administrators can:

- View complaints
- Search complaints
- Filter complaints by status
- View reported agent
- View complaint details
- Investigate complaints
- Request additional information
- Record investigation findings
- Resolve complaints
- Reject unfounded complaints
- Suspend an agent where appropriate
- Permanently remove an agent where necessary

Complaint statuses:

- New
- Under Review
- Awaiting Information
- Resolved
- Dismissed

All important decisions should be recorded in the Audit Log.

---

# 7. News & Tips

Administrators can:

- Create articles
- Edit articles
- Publish articles
- Save drafts
- Schedule articles
- Unpublish articles
- Delete articles
- Add featured images
- Categorize articles

Possible categories:

- Property Tips
- Land Buying Tips
- Rental Tips
- Legal Awareness
- Market Updates
- Agent News
- Platform News

---

# 8. Location Management

Administrators can:

- Add locations
- Edit locations
- Disable locations
- View locations
- Organize locations by LGA

Location information may include:

- Location Name
- LGA
- State
- Status

Disabled locations should not appear in new agent registration forms or public search filters.

---

# 9. Analytics

The Analytics section displays:

### Agent Analytics

- New registrations
- Approved agents
- Rejected applications
- Active members
- Expired memberships
- Suspended agents
- Membership renewals

### Financial Analytics

- Revenue trends
- Membership revenue
- Featured Agent revenue
- Payment success rate

### Platform Analytics

- Agent profile views
- Agent searches
- Agent contact requests
- Property requests
- Most searched locations
- Most viewed agents
- Most contacted agents

### Performance Analytics

- Average Response Rate
- Average Profile Strength
- Trust Score distribution

Analytics should support date filtering.

---

# 10. Settings

Administrators can manage:

### Membership Settings

- Annual Membership Fee
- Membership Duration
- Renewal Reminder Period

### Featured Agent Settings

- Featured Agent Fee
- Featured Agent Duration

### Platform Settings

- Platform Name
- Logo
- Contact Email
- Contact Phone
- Office Address
- Social Media Accounts

### Notification Settings

- Email notifications
- Membership reminders
- Registration notifications
- Approval notifications
- Payment notifications

### Security Settings

- Administrator access
- Password policies
- Session timeout
- Two-factor authentication

Critical settings should require administrator authorization before changes take effect.

---

# 11. Audit Log

The Audit Log records important administrative and system activities.

Each record should contain:

- Date and Time
- Administrator/User
- Action
- Target Record
- Previous Status
- New Status
- IP Address
- Additional Details

Examples:

| Date | User | Action |
|------|------|--------|
| 07 Aug 2026 | Admin | Approved Agent LPA-0001 |
| 07 Aug 2026 | Admin | Suspended Agent LPA-0015 |
| 07 Aug 2026 | Admin | Published News Article |
| 07 Aug 2026 | Admin | Changed Membership Fee |

Audit records should normally be read-only and should not be editable by ordinary administrators.

---

# Administrator Security

The Admin Dashboard must have strict access control.

Administrators must:

- Use secure authentication
- Have unique accounts
- Use strong passwords
- Have appropriate permissions
- Be able to use two-factor authentication

Administrative actions must be logged.

Unauthorized users must not be able to access administrative functions.

---

# Administrator Roles

The platform may support different administrator permissions in the future.

### Super Administrator

Full access to the platform.

### Administrator

Can manage agents, memberships, complaints, news, locations, and property requests.

### Finance Administrator

Can access financial records and payment information.

### Content Administrator

Can manage News & Tips.

Administrator permissions should follow the principle of least privilege.
