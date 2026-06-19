# Visitor Management System (VMS) - ServiceNow

## Overview

The Visitor Management System (VMS) is a ServiceNow-based application developed to automate and streamline visitor registration and tracking within an organization. The system enables administrators to manage visitor requests, approve or reject visits, record visitor check-in and check-out activities, send automated email notifications, and monitor visitor statistics through an interactive dashboard.

---

## Features

* Visitor Registration and Management
* Employee Host Management
* Visitor Approval and Rejection Process
* Visitor Check-In and Check-Out Tracking
* Visit Date Validation
* Working Hours Validation
* Automated Email Notifications
* Real-Time Dashboard Monitoring
* Status-Based Visitor Tracking

---

## Technology Stack

* ServiceNow Platform
* Scoped Application
* Custom Tables
* Reference Fields
* Client Scripts
* UI Policies
* UI Actions
* Flow Designer
* Platform Analytics Dashboard

---

## Database Design

### Employee Table

Stores employee information who act as hosts for visitors.

Fields:

* Employee ID
* Employee Name
* Email
* Phone Number
* Department
* Designation
* Location
* Status

### Visitor Table

Stores visitor details and visit information.

Fields:

* Visitor Name
* Phone Number
* Email
* Company Name
* Visit Date
* Employee Host
* Purpose of Visit
* Status
* Check In Time
* Check Out Time

---

## Workflow

Visitor Request Submitted

→ Requested

→ Approved / Rejected

→ Checked In

→ Checked Out

---

## Validations and Automation

### Client Scripts

* Prevent submission of visitor requests with past dates.
* Restrict visit scheduling to official working hours (09:00 AM – 06:00 PM).

### UI Policies

* Display Check In Time when visitor status is Checked In.
* Display Check Out Time when visitor status is Checked Out.
* Make system-generated fields read-only.

### UI Actions

* Approve
* Reject
* Check In
* Check Out

These actions automate visitor status management and visit tracking.

---

## Email Notifications

Implemented using Flow Designer.

Notifications are automatically sent to visitors when:

* A visitor request is submitted.
* A request is approved.
* A request is rejected.
* A visitor is checked in.
* A visitor is checked out.

---

## Dashboard

### Visitor Management System Dashboard

The dashboard provides real-time visibility into visitor activities.

Widgets Included:

* Total Visit Requests
* Approved Requests
* Rejected Requests
* Checked In Visitors Count
* Currently Checked In Visitors
* Checked Out Visitors Count
* Checked Out Visitors List

---

## Project Outcomes

* Reduced manual visitor management activities.
* Improved visitor tracking and monitoring.
* Automated communication through email notifications.
* Enhanced visibility using dashboard analytics.
* Improved data accuracy through client-side validation.

---

## Future Enhancements

* QR Code Based Visitor Check-In
* Visitor Badge Generation
* Multi-Level Approval Workflow
* Visitor Self-Service Portal
* Mobile Application Support
* Advanced Analytics Dashboard
* Integration with Access Control Systems

---

## Author

**Vishal R**

ServiceNow Visitor Management System
