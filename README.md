# Community-Family-Management-System---php
📘 USER MANUAL
Halar Memon Jamat Family Management System
1️⃣ Introduction

The Halar Memon Jamat Family Management System is a digital platform designed to manage:

Member Records

Family Details

Membership Applications

Update Requests

PDF Generation

Activity Tracking

Admin Approval Workflows

The system ensures:

Data accuracy

Controlled approvals

Secure record keeping

Transparency between members and admin

2️⃣ User Roles

The system has two main user roles:

🔹 1. Admin

Full system control.

🔹 2. Family Member (Frontend User)

Limited access to their own records.

3️⃣ Admin Panel Manual
3.1 Admin Login

Open Admin Login Page.

Enter:

Username

Password

Click Login.

After login, Admin Dashboard will appear.

3.2 Dashboard Overview

Dashboard shows:

Total Members

Total Families

Pending Applications

Pending Update Requests

Recent Activity Logs

3.3 Add New Member (Direct Entry)

Admin can manually add member:

Go to Members → Add Member

Fill:

Membership No

Name

Father Name

Surname

Education

Business Type

Office Address

Native Place

Mobile 1

Mobile 2

Photo

Add Family Members (if required)

Click Save

Member is instantly active.

3.4 View / Edit Member

Go to Members → List

Click View

Admin can:

Edit details

Add family members

Delete members

Download PDF

3.5 Download Member PDF

Open member details

Click Download PDF

Premium designed PDF will download directly

PDF includes:

Member details

Family details

Official header

Generated date

3.6 New Member Applications (Frontend Submitted)

When frontend user submits new registration:

Go to Applications → Member Applications

View list:

Name

Mobile

Native Place

Status

Date

Review Application

Click View

Admin can:

See full form data

See family members

Approve

Reject

Approve

Membership number auto generated

Data moves to official member table

Application marked Approved

Reject

Enter reason (mandatory)

Status becomes Rejected

Member can view rejection note

3.7 Update Requests (Existing Members)

Family members can request updates.

Example:
“Please update my mobile number to 9876543210”

Admin Process

Go to Update Requests

Review request

Approve or Reject

If Approved:

Admin manually updates member record

Status becomes Approved

If Rejected:

Add admin notes

Status becomes Rejected

3.8 Activity Logs

Admin can monitor system activity:

Go to Activity Logs

Shows:

OTP Sent

OTP Verified

Profile Viewed

Update Requested

Application Approved

Login Attempts

Admin can:

Filter by activity type

Filter by date

Search by member

3.9 Re-Approve Rejected Request

If admin rejected mistakenly:

Open request

Click Re-Approve

Status updates accordingly

4️⃣ Frontend User Manual (Family Member)
4.1 Login

Enter registered mobile number

Receive OTP

Enter OTP

Login successful

4.2 View Profile

After login:

View personal details

View family members

Download PDF copy

4.3 Request Update

If any data is incorrect:

Click Request Update

Enter message:
Example:
“Please update my mobile number to 9822001122”

Submit

Status will show:

Pending

Approved

Rejected

4.4 New Membership Registration

If not already a member:

Open Registration Form

Fill complete details

Add family members

Upload photo

Submit

Status will show:

Pending Approval

Approved

Rejected (with reason)

5️⃣ Membership Number System

Membership number is:

Generated only after Admin approval

Unique

Cannot be edited manually

Example format:
HMJ-2026-001

6️⃣ Security Features

System includes:

OTP login

Role-based access

CSRF protection

Secure photo upload

Activity logging

Admin approval workflow

Transaction-safe database inserts

7️⃣ System Workflow Summary
New Member Flow

Frontend Submit
→ Pending
→ Admin Review
→ Approve
→ Membership Created

Update Request Flow

Member Request
→ Pending
→ Admin Review
→ Approve / Reject

8️⃣ Best Practices for Admin

✔ Review applications carefully
✔ Always add notes when rejecting
✔ Do not share admin login
✔ Monitor activity logs regularly
✔ Backup database regularly

9️⃣ Troubleshooting
OTP Not Received

Check mobile number

Retry after few minutes

PDF Not Downloading

Contact system administrator

Application Not Approved

Check status page
