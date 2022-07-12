# IAM - Identity Access Management  
- Create Users and grant access
- Users groups
- Roles
- Control access to AWS resources

## Tips
- Secure root account enabling MFA
- Create users accounts
- Create Admin group for the users and grant access to resources
- Add users to group
---
- IAM is global
- Assign permissions using IAM Policy Documents (JSON)
- The principle of Least Privilege
- By default a user created has NO permissions
- SSO need to create an Identity provider of type SAML(Active Directory) to connect to your Active Directory Federation Service
- Deny Effect overrides any other Allow permission