# Requirement Analysis Phase

Project Title: Script-Controlled ACL

## Functional Requirements

- Admin role should have full access (Create, Read, Write and Delete) to the Institution Details table.
- Manager role should have Read and Write access.
- Staff role should have Read-only access.
- Access should be controlled dynamically using script conditions.
- Unauthorized users should be denied access by default.

## Non-Functional Requirements

- The solution should be easy to maintain and extend for new roles.
- Access checks should not noticeably slow down record loading.
- The access control should provide secure and role-based data access.
