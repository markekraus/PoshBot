# PluginManager
## about_PluginManager

# SHORT DESCRIPTION
Describes the PluginManager Class

# LONG DESCRIPTION
{{ Long Description Placeholder }}


# Constructors
## PluginManager(RoleManager RoleManager, StorageProvider Storage, Logger Logger, String PoshBotModuleDir)
{{ Constructor Description Placeholder }}

```powershell
[PluginManager]::new([RoleManager]$RoleManager, [StorageProvider]$Storage, [Logger]$Logger, [String]$PoshBotModuleDir)
```


# Properties
## _PoshBotModuleDir
{{ Property Description Placeholder }}

```yaml
Name: _PoshBotModuleDir
Type: String
Hidden: True
Static: False
```

## _Storage
{{ Property Description Placeholder }}

```yaml
Name: _Storage
Type: StorageProvider
Hidden: False
Static: False
```

## Commands
{{ Property Description Placeholder }}

```yaml
Name: Commands
Type: System.Collections.Hashtable
Hidden: False
Static: False
```

## Logger
{{ Property Description Placeholder }}

```yaml
Name: Logger
Type: Logger
Hidden: False
Static: False
```

## Plugins
{{ Property Description Placeholder }}

```yaml
Name: Plugins
Type: System.Collections.Hashtable
Hidden: False
Static: False
```

## RoleManager
{{ Property Description Placeholder }}

```yaml
Name: RoleManager
Type: RoleManager
Hidden: False
Static: False
```


# Methods
## ActivatePlugin(String PluginName, String Version)
{{ Method Description Placeholder }}

```yaml
Name: ActivatePlugin
Return Type: Void
Hidden: False
Static: False
Definition: Void ActivatePlugin(String PluginName, String Version)
```

## ActivatePlugin(Plugin Plugin)
{{ Method Description Placeholder }}

```yaml
Name: ActivatePlugin
Return Type: Void
Hidden: False
Static: False
Definition: Void ActivatePlugin(Plugin Plugin)
```

## AddPlugin(Plugin Plugin, Boolean SaveAfterInstall)
{{ Method Description Placeholder }}

```yaml
Name: AddPlugin
Return Type: Void
Hidden: False
Static: False
Definition: Void AddPlugin(Plugin Plugin, Boolean SaveAfterInstall)
```

## CreatePluginFromModuleManifest(String ModuleName, String ManifestPath, Boolean AsJob, Boolean SaveAfterCreation)
{{ Method Description Placeholder }}

```yaml
Name: CreatePluginFromModuleManifest
Return Type: Void
Hidden: False
Static: False
Definition: Void CreatePluginFromModuleManifest(String ModuleName, String ManifestPath, Boolean AsJob, Boolean SaveAfterCreation)
```

## DeactivatePlugin(Plugin Plugin)
{{ Method Description Placeholder }}

```yaml
Name: DeactivatePlugin
Return Type: Void
Hidden: False
Static: False
Definition: Void DeactivatePlugin(Plugin Plugin)
```

## DeactivatePlugin(String PluginName, String Version)
{{ Method Description Placeholder }}

```yaml
Name: DeactivatePlugin
Return Type: Void
Hidden: False
Static: False
Definition: Void DeactivatePlugin(String PluginName, String Version)
```

## GetCommandMetadata(System.Management.Automation.FunctionInfo Command)
{{ Method Description Placeholder }}

```yaml
Name: GetCommandMetadata
Return Type: PoshBot.BotCommand
Hidden: False
Static: False
Definition: PoshBot.BotCommand GetCommandMetadata(System.Management.Automation.FunctionInfo Command)
```

## GetPermissionsFromModuleManifest(Object Manifest)
{{ Method Description Placeholder }}

```yaml
Name: GetPermissionsFromModuleManifest
Return Type: Permission[]
Hidden: False
Static: False
Definition: Permission[] GetPermissionsFromModuleManifest(Object Manifest)
```

## GetPluginConfig(String PluginName, String Version)
{{ Method Description Placeholder }}

```yaml
Name: GetPluginConfig
Return Type: System.Collections.Hashtable
Hidden: False
Static: False
Definition: System.Collections.Hashtable GetPluginConfig(String PluginName, String Version)
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

## InstallPlugin(String ManifestPath, Boolean SaveAfterInstall)
{{ Method Description Placeholder }}

```yaml
Name: InstallPlugin
Return Type: Void
Hidden: False
Static: False
Definition: Void InstallPlugin(String ManifestPath, Boolean SaveAfterInstall)
```

## LoadBuiltinPlugins()
{{ Method Description Placeholder }}

```yaml
Name: LoadBuiltinPlugins
Return Type: Void
Hidden: False
Static: False
Definition: Void LoadBuiltinPlugins()
```

## LoadCommands()
{{ Method Description Placeholder }}

```yaml
Name: LoadCommands
Return Type: Void
Hidden: False
Static: False
Definition: Void LoadCommands()
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

## MatchCommand(ParsedCommand ParsedCommand, Boolean CommandSearch)
{{ Method Description Placeholder }}

```yaml
Name: MatchCommand
Return Type: PluginCommand
Hidden: False
Static: False
Definition: PluginCommand MatchCommand(ParsedCommand ParsedCommand, Boolean CommandSearch)
```

## RemovePlugin(Plugin Plugin)
{{ Method Description Placeholder }}

```yaml
Name: RemovePlugin
Return Type: Void
Hidden: False
Static: False
Definition: Void RemovePlugin(Plugin Plugin)
```

## RemovePlugin(String PluginName, String Version)
{{ Method Description Placeholder }}

```yaml
Name: RemovePlugin
Return Type: Void
Hidden: False
Static: False
Definition: Void RemovePlugin(String PluginName, String Version)
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


