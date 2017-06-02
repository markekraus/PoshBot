# CommandExecutor
## about_CommandExecutor

# SHORT DESCRIPTION
Describes the CommandExecutor Class

# LONG DESCRIPTION
{{ Long Description Placeholder }}


# Constructors
## CommandExecutor(RoleManager RoleManager, Bot Bot)
{{ Constructor Description Placeholder }}

```powershell
[CommandExecutor]::new([RoleManager]$RoleManager, [Bot]$Bot)
```


# Properties
## _bot
{{ Property Description Placeholder }}

```yaml
Name: _bot
Type: Bot
Hidden: True
Static: False
```

## _jobTracker
{{ Property Description Placeholder }}

```yaml
Name: _jobTracker
Type: System.Collections.Hashtable
Hidden: True
Static: False
```

## ExecutedCount
{{ Property Description Placeholder }}

```yaml
Name: ExecutedCount
Type: Int32
Hidden: False
Static: False
```

## History
{{ Property Description Placeholder }}

```yaml
Name: History
Type: System.Collections.ArrayList
Hidden: False
Static: False
```

## HistoryToKeep
{{ Property Description Placeholder }}

```yaml
Name: HistoryToKeep
Type: Int32
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
## AddToHistory(CommandExecutionContext CmdExecContext)
{{ Method Description Placeholder }}

```yaml
Name: AddToHistory
Return Type: Void
Hidden: False
Static: False
Definition: Void AddToHistory(CommandExecutionContext CmdExecContext)
```

## ExecuteCommand(PluginCommand PluginCmd, ParsedCommand ParsedCommand, Message Message)
{{ Method Description Placeholder }}

```yaml
Name: ExecuteCommand
Return Type: Void
Hidden: False
Static: False
Definition: Void ExecuteCommand(PluginCommand PluginCmd, ParsedCommand ParsedCommand, Message Message)
```

## ReceiveJob()
{{ Method Description Placeholder }}

```yaml
Name: ReceiveJob
Return Type: CommandExecutionContext[]
Hidden: False
Static: False
Definition: CommandExecutionContext[] ReceiveJob()
```

## TrackJob(CommandExecutionContext CommandContext)
{{ Method Description Placeholder }}

```yaml
Name: TrackJob
Return Type: Void
Hidden: False
Static: False
Definition: Void TrackJob(CommandExecutionContext CommandContext)
```

## ValidateMandatoryParameters(ParsedCommand ParsedCommand, Command Command)
{{ Method Description Placeholder }}

```yaml
Name: ValidateMandatoryParameters
Return Type: Boolean
Hidden: False
Static: False
Definition: Boolean ValidateMandatoryParameters(ParsedCommand ParsedCommand, Command Command)
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


