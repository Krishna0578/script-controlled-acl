# Project Design Phase

Project Title: Script-Controlled ACL

## Design Overview

The project design defines the ServiceNow table, user roles and ACL rules required to control access to Institution Details.

## Access Flow

Institution Details Table → User Role Assigned → ACL Rule Triggered → Script Condition Checked → Access Granted or Denied

## Components

- **Table:** Institution Details
- **Roles:** Admin, Manager, Staff
- **Operations Controlled:** Create, Read, Write, Delete
- **ACL:** Controls access based on user roles and conditions
- **Script:** Checks the user's role and record conditions before allowing access

## Access Control

- **Admin:** Full access
- **Manager:** Read and Write access
- **Staff:** Read-only access
- **Unauthorized users:** Access denied
