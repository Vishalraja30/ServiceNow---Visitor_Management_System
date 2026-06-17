# Visitor Management System - ServiceNow

A Visitor Management System developed on the ServiceNow platform to automate visitor registration, approval, check-in, and check-out processes. The application eliminates manual visitor logs and provides efficient visitor tracking through automated workflows, notifications, reports, and dashboards.

## Features

* Visitor Registration and Request Submission
* Employee Host Management
* Automated Request Status Assignment
* Visitor Approval and Rejection Workflow
* Visitor Check-In and Check-Out Tracking
* Automatic Check-In and Check-Out Time Recording
* Visit Date Validation
* Working Hours Validation
* Email Notifications using Flow Designer
* Dynamic Field Visibility using UI Policies
* Reports and Dashboard for Visitor Analytics

## Technologies Used

* ServiceNow Scoped Application
* Custom Tables
* Client Scripts
* UI Policies
* Business Rules
* UI Actions
* Flow Designer
* Reports
* Dashboards

## Database Design

### Employee Table

* Employee ID
* Employee Name
* Email
* Phone Number
* Department
* Designation
* Location
* Status

### Visitor Table

* Visitor Name
* Phone Number
* Email
* Company Name
* Visit Date
* Employee Host (Reference)
* Purpose of Visit
* Status
* Check In Time
* Check Out Time

## Workflow

Visitor Request Submitted
→ Requested
→ Approved / Rejected
→ Checked In
→ Checked Out

## Key Functionalities

### Client Scripts

* Automatically assigns "Requested" status during submission.
* Prevents selection of past visit dates.

### UI Policies

* Displays Check In Time after visitor check-in.
* Displays Check Out Time after visitor check-out.

### Business Rules

* Validates appointment scheduling during office hours.
* Handles server-side validations.

### UI Actions

* Approve
* Reject
* Check In
* Check Out

### Flow Designer

Automated email notifications for:

* Request Submitted
* Approved
* Rejected
* Checked In
* Checked Out



## Dashboard

Visitor Management Dashboard provides real-time insights into visitor activities and request statuses.

## Project Outcome

This application improves visitor tracking, reduces manual effort, enhances security, and provides administrators with complete visibility into visitor activities through automated workflows and reporting.
