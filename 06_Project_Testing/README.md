# Project Testing Phase

Project Title: Script-Controlled ACL

The ACL configuration was tested for different user roles to verify that the access rules work correctly.

| Role | Operation | Expected Result | Actual Result |
|---|---|---|---|
| Admin | Delete | Allowed | Allowed |
| Manager | Write | Allowed | Allowed |
| Manager | Delete | Denied | Denied |
| Staff | Read | Allowed | Allowed |
| Staff | Write | Denied | Denied |

## Testing Result

The test results confirm that the configured ACL rules correctly allow or deny access according to the user's role and the defined conditions.
