# RoleManager
## about_RoleManager

# SHORT DESCRIPTION
Describes the RoleManager Class

# LONG DESCRIPTION
{{ Long Description Placeholder }}


# Constructors
## RoleManager(Object Backend, StorageProvider Storage, Logger Logger)
{{ Constructor Description Placeholder }}

```powershell
[RoleManager]::new([Object]$Backend, [StorageProvider]$Storage, [Logger]$Logger)
```


# Properties
## _Backend
{{ Property Description Placeholder }}

```yaml
Name: _Backend
Type: Object
Hidden: True
Static: False
```

## _Logger
{{ Property Description Placeholder }}

```yaml
Name: _Logger
Type: Logger
Hidden: True
Static: False
```

## _Storage
{{ Property Description Placeholder }}

```yaml
Name: _Storage
Type: StorageProvider
Hidden: True
Static: False
```

## Groups
{{ Property Description Placeholder }}

```yaml
Name: Groups
Type: System.Collections.Hashtable
Hidden: False
Static: False
```

## Permissions
{{ Property Description Placeholder }}

```yaml
Name: Permissions
Type: System.Collections.Hashtable
Hidden: False
Static: False
```

## Roles
{{ Property Description Placeholder }}

```yaml
Name: Roles
Type: System.Collections.Hashtable
Hidden: False
Static: False
```

## RoleUserMapping
{{ Property Description Placeholder }}

```yaml
Name: RoleUserMapping
Type: System.Collections.Hashtable
Hidden: False
Static: False
```


# Methods
## AddGroup(Group Group)
{{ Method Description Placeholder }}

```yaml
Name: AddGroup
Return Type: Void
Hidden: False
Static: False
Definition: Void AddGroup(Group Group)
```

## AddPermission(Permission Permission)
{{ Method Description Placeholder }}

```yaml
Name: AddPermission
Return Type: Void
Hidden: False
Static: False
Definition: Void AddPermission(Permission Permission)
```

## AddPermissionToRole(String PermissionName, String RoleName)
{{ Method Description Placeholder }}

```yaml
Name: AddPermissionToRole
Return Type: Void
Hidden: False
Static: False
Definition: Void AddPermissionToRole(String PermissionName, String RoleName)
```

## AddRole(Role Role)
{{ Method Description Placeholder }}

```yaml
Name: AddRole
Return Type: Void
Hidden: False
Static: False
Definition: Void AddRole(Role Role)
```

## AddRoleToGroup(String RoleName, String GroupName)
{{ Method Description Placeholder }}

```yaml
Name: AddRoleToGroup
Return Type: Void
Hidden: False
Static: False
Definition: Void AddRoleToGroup(String RoleName, String GroupName)
```

## AddUserToGroup(String UserId, String GroupName)
{{ Method Description Placeholder }}

```yaml
Name: AddUserToGroup
Return Type: Void
Hidden: False
Static: False
Definition: Void AddUserToGroup(String UserId, String GroupName)
```

## GetGroup(String Groupname)
{{ Method Description Placeholder }}

```yaml
Name: GetGroup
Return Type: Group
Hidden: False
Static: False
Definition: Group GetGroup(String Groupname)
```

## GetPermission(String PermissionName)
{{ Method Description Placeholder }}

```yaml
Name: GetPermission
Return Type: Permission
Hidden: False
Static: False
Definition: Permission GetPermission(String PermissionName)
```

## GetRole(String RoleName)
{{ Method Description Placeholder }}

```yaml
Name: GetRole
Return Type: Role
Hidden: False
Static: False
Definition: Role GetRole(String RoleName)
```

## GetUserGroups(String UserId)
{{ Method Description Placeholder }}

```yaml
Name: GetUserGroups
Return Type: Group[]
Hidden: False
Static: False
Definition: Group[] GetUserGroups(String UserId)
```

## GetUserPermissions(String UserId)
{{ Method Description Placeholder }}

```yaml
Name: GetUserPermissions
Return Type: Permission[]
Hidden: False
Static: False
Definition: Permission[] GetUserPermissions(String UserId)
```

## GetUserRoles(String UserId)
{{ Method Description Placeholder }}

```yaml
Name: GetUserRoles
Return Type: Role[]
Hidden: False
Static: False
Definition: Role[] GetUserRoles(String UserId)
```

## Initialize()
{{ Method Description Placeholder }}

```yaml
Name: Initialize
Return Type: Void
Hidden: False
Static: False
Definition: Void Initialize()
```

## LoadState()
{{ Method Description Placeholder }}

```yaml
Name: LoadState
Return Type: Void
Hidden: False
Static: False
Definition: Void LoadState()
```

## RemoveGroup(Group Group)
{{ Method Description Placeholder }}

```yaml
Name: RemoveGroup
Return Type: Void
Hidden: False
Static: False
Definition: Void RemoveGroup(Group Group)
```

## RemovePermission(Permission Permission)
{{ Method Description Placeholder }}

```yaml
Name: RemovePermission
Return Type: Void
Hidden: False
Static: False
Definition: Void RemovePermission(Permission Permission)
```

## RemovePermissionFromRole(String PermissionName, String RoleName)
{{ Method Description Placeholder }}

```yaml
Name: RemovePermissionFromRole
Return Type: Void
Hidden: False
Static: False
Definition: Void RemovePermissionFromRole(String PermissionName, String RoleName)
```

## RemoveRole(Role Role)
{{ Method Description Placeholder }}

```yaml
Name: RemoveRole
Return Type: Void
Hidden: False
Static: False
Definition: Void RemoveRole(Role Role)
```

## RemoveRoleFromGroup(String RoleName, String GroupName)
{{ Method Description Placeholder }}

```yaml
Name: RemoveRoleFromGroup
Return Type: Void
Hidden: False
Static: False
Definition: Void RemoveRoleFromGroup(String RoleName, String GroupName)
```

## RemoveUserFromGroup(String UserId, String GroupName)
{{ Method Description Placeholder }}

```yaml
Name: RemoveUserFromGroup
Return Type: Void
Hidden: False
Static: False
Definition: Void RemoveUserFromGroup(String UserId, String GroupName)
```

## ResolveUserToId(String Username)
{{ Method Description Placeholder }}

```yaml
Name: ResolveUserToId
Return Type: String
Hidden: False
Static: False
Definition: String ResolveUserToId(String Username)
```

## SaveState()
{{ Method Description Placeholder }}

```yaml
Name: SaveState
Return Type: Void
Hidden: False
Static: False
Definition: Void SaveState()
```

## UpdateGroupDescription(String Groupname, String Description)
{{ Method Description Placeholder }}

```yaml
Name: UpdateGroupDescription
Return Type: Void
Hidden: False
Static: False
Definition: Void UpdateGroupDescription(String Groupname, String Description)
```

## UpdateRoleDescription(String Rolename, String Description)
{{ Method Description Placeholder }}

```yaml
Name: UpdateRoleDescription
Return Type: Void
Hidden: False
Static: False
Definition: Void UpdateRoleDescription(String Rolename, String Description)
```


# EXAMPLES
{{ Code or descriptive examples of how to leverage the functions described. }}

# NOTE
{{ Note Placeholder - Additional information that a user needs to know.}}

# TROUBLESHOOTING NOTE
{{ Troubleshooting Placeholder - Warns users of bugs}}

{{ Explains behavior that is likely to change with fixes }}

# SEE ALSO
{{ See also placeholder }}

{{ You can also list related articles, blogs, and video URLs. }}

# KEYWORDS
{{List alternate names or titles for this topic that readers might use.}}

- {{ Keyword Placeholder }}
- {{ Keyword Placeholder }}
- {{ Keyword Placeholder }}
- {{ Keyword Placeholder }}    


