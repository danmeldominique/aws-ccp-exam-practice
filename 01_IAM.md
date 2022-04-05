

# Summary

- **Users:** Mapped to pysical user, has password for console.
- **Groups:** Contains users
- **Policies:** JSON that outlines permissions for users/groups
- **Roles:** Similar to IAM user except.
  - No credentials
  - Assummed by anyone who needs permission assigned to role.
- **Security:** MFA and password policy (ie. rotation) for added security on accounts
- **AWS CLI:** Manage services via CLI
- **AWS SDK:** Manage services via programming language
- **Access Keys:** Provides access to AWS via CLI or SDK
- **Auditing:**
  - **IAM Credentials Reports:** *Account level* - Contains all users and status of their credentials
  - **IAM Access Advisor:** *User level* - service permissions granted to user and when last accessed.

# SRM

| AWS| User|
|-|-|
| - Infrastructure| - Correctly set up users, policies, roles and management/monitoring of these.|
| - Config and vulnerability analysis | - Rotate keys often |
| - Compliance validation | - Use IAM tools to apply appropriate permissions|
|  | - Enable MFA on all accounts |
|  | - Analyse access patterns and review permissions |

