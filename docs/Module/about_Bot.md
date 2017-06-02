# Bot
## about_Bot

# SHORT DESCRIPTION
Describes the Bot Class

# LONG DESCRIPTION
{{ Long Description Placeholder }}


# Constructors
## Bot(Backend Backend, String PoshBotDir, BotConfiguration Config)
{{ Constructor Description Placeholder }}

```powershell
[Bot]::new([Backend]$Backend, [String]$PoshBotDir, [BotConfiguration]$Config)
```

## Bot(String Name, Backend Backend, String PoshBotDir, String ConfigPath)
{{ Constructor Description Placeholder }}

```powershell
[Bot]::new([String]$Name, [Backend]$Backend, [String]$PoshBotDir, [String]$ConfigPath)
```


# Properties
## _Logger
{{ Property Description Placeholder }}

```yaml
Name: _Logger
Type: Logger
Hidden: True
Static: False
```

## _PoshBotDir
{{ Property Description Placeholder }}

```yaml
Name: _PoshBotDir
Type: String
Hidden: True
Static: False
```

## _PossibleCommandPrefixes
{{ Property Description Placeholder }}

```yaml
Name: _PossibleCommandPrefixes
Type: System.Collections.ArrayList
Hidden: True
Static: False
```

## _Stopwatch
{{ Property Description Placeholder }}

```yaml
Name: _Stopwatch
Type: System.Diagnostics.Stopwatch
Hidden: True
Static: False
```

## Backend
{{ Property Description Placeholder }}

```yaml
Name: Backend
Type: Backend
Hidden: False
Static: False
```

## Configuration
{{ Property Description Placeholder }}

```yaml
Name: Configuration
Type: BotConfiguration
Hidden: False
Static: False
```

## Executor
{{ Property Description Placeholder }}

```yaml
Name: Executor
Type: CommandExecutor
Hidden: False
Static: False
```

## MessageQueue
{{ Property Description Placeholder }}

```yaml
Name: MessageQueue
Type: System.Collections.Queue
Hidden: False
Static: False
```

## Name
{{ Property Description Placeholder }}

```yaml
Name: Name
Type: String
Hidden: False
Static: False
```

## PluginManager
{{ Property Description Placeholder }}

```yaml
Name: PluginManager
Type: PluginManager
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

## Storage
{{ Property Description Placeholder }}

```yaml
Name: Storage
Type: StorageProvider
Hidden: False
Static: False
```


# Methods
## _IsCustomResponse(Object Response)
{{ Method Description Placeholder }}

```yaml
Name: _IsCustomResponse
Return Type: Boolean
Hidden: True
Static: False
Definition: hidden Boolean _IsCustomResponse(Object Response)
```

## _IsPrimitiveType(Object Item)
{{ Method Description Placeholder }}

```yaml
Name: _IsPrimitiveType
Return Type: Boolean
Hidden: True
Static: False
Definition: hidden Boolean _IsPrimitiveType(Object Item)
```

## Connect()
{{ Method Description Placeholder }}

```yaml
Name: Connect
Return Type: Void
Hidden: False
Static: False
Definition: Void Connect()
```

## Disconnect()
{{ Method Description Placeholder }}

```yaml
Name: Disconnect
Return Type: Void
Hidden: False
Static: False
Definition: Void Disconnect()
```

## GenerateCommandPrefixList()
{{ Method Description Placeholder }}

```yaml
Name: GenerateCommandPrefixList
Return Type: Void
Hidden: False
Static: False
Definition: Void GenerateCommandPrefixList()
```

## GetConfigProvidedParameters(PluginCommand PluginCmd)
{{ Method Description Placeholder }}

```yaml
Name: GetConfigProvidedParameters
Return Type: System.Collections.Hashtable
Hidden: False
Static: False
Definition: System.Collections.Hashtable GetConfigProvidedParameters(PluginCommand PluginCmd)
```

## HandleMessage(Message Message)
{{ Method Description Placeholder }}

```yaml
Name: HandleMessage
Return Type: Void
Hidden: False
Static: False
Definition: Void HandleMessage(Message Message)
```

## Initialize(BotConfiguration Config)
{{ Method Description Placeholder }}

```yaml
Name: Initialize
Return Type: Void
Hidden: False
Static: False
Definition: Void Initialize(BotConfiguration Config)
```

## IsBotCommand(Message Message)
{{ Method Description Placeholder }}

```yaml
Name: IsBotCommand
Return Type: Boolean
Hidden: False
Static: False
Definition: Boolean IsBotCommand(Message Message)
```

## LoadConfiguration()
{{ Method Description Placeholder }}

```yaml
Name: LoadConfiguration
Return Type: Void
Hidden: False
Static: False
Definition: Void LoadConfiguration()
```

## ProcessCompletedJobs()
{{ Method Description Placeholder }}

```yaml
Name: ProcessCompletedJobs
Return Type: Void
Hidden: False
Static: False
Definition: Void ProcessCompletedJobs()
```

## ProcessMessageQueue()
{{ Method Description Placeholder }}

```yaml
Name: ProcessMessageQueue
Return Type: Void
Hidden: False
Static: False
Definition: Void ProcessMessageQueue()
```

## ReceiveMessage()
{{ Method Description Placeholder }}

```yaml
Name: ReceiveMessage
Return Type: Void
Hidden: False
Static: False
Definition: Void ReceiveMessage()
```

## SendMessage(Response Response)
{{ Method Description Placeholder }}

```yaml
Name: SendMessage
Return Type: Void
Hidden: False
Static: False
Definition: Void SendMessage(Response Response)
```

## Start()
{{ Method Description Placeholder }}

```yaml
Name: Start
Return Type: Void
Hidden: False
Static: False
Definition: Void Start()
```

## TrimPrefix(Message Message)
{{ Method Description Placeholder }}

```yaml
Name: TrimPrefix
Return Type: Message
Hidden: False
Static: False
Definition: Message TrimPrefix(Message Message)
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


