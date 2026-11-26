SEC- <Type>- <Name>

Northwind Services will use the naming convention as follows. All security groups using `SEC-<Type>-<Name>`. SEC identifies the object as a security group, <Type> defines the grouping category (Dept for department, Role for job function, or Loc for physical location), and <Name> specifies the actual category (such as Finance, Helpdesk, or Remote, resulting in groups like SEC-Dept-Finance and SEC-Role-Helpdesk). All user principal names (UPNs) will follow the firstname.lastname@://onmicrosoft.com format across all 15 users.

Enforcing a strict naming convention on day one prevents directory clutter and confusion as the organization grows. While tracking 15 users and a handful of groups is easy at the start, real-world tenants quickly scale to hundreds of groups where inconsistent names force administrators to open each group just to understand what access it grants. Using predictable prefixes and a uniform UPN format keeps audit logs easy to read, reduces the risk of accidental permission mistakes, and lays a clean foundation for automated access management in the future.

