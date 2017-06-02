# Logger
## about_Logger

# SHORT DESCRIPTION
Describes the Logger Class

# LONG DESCRIPTION
{{ Long Description Placeholder }}


# Constructors
## Logger(String LogDir, LogLevel LogLevel)
{{ Constructor Description Placeholder }}

```powershell
[Logger]::new([String]$LogDir, [LogLevel]$LogLevel)
```


# Properties
## FilesToKeep
{{ Property Description Placeholder }}

```yaml
Name: FilesToKeep
Type: Int32
Hidden: False
Static: False
```

## LogDir
{{ Property Description Placeholder }}

```yaml
Name: LogDir
Type: String
Hidden: False
Static: False
```

## LogFile
{{ Property Description Placeholder }}

```yaml
Name: LogFile
Type: String
Hidden: True
Static: False
```

## LogLevel
{{ Property Description Placeholder }}

```yaml
Name: LogLevel
Type: LogLevel
Hidden: False
Static: False
```

## MaxSizeMB
{{ Property Description Placeholder }}

```yaml
Name: MaxSizeMB
Type: Int32
Hidden: False
Static: False
```


# Methods
## CreateLogFile()
{{ Method Description Placeholder }}

```yaml
Name: CreateLogFile
Return Type: Void
Hidden: True
Static: False
Definition: hidden Void CreateLogFile()
```

## Debug(LogMessage Message)
{{ Method Description Placeholder }}

```yaml
Name: Debug
Return Type: Void
Hidden: False
Static: False
Definition: Void Debug(LogMessage Message)
```

## Info(LogMessage Message)
{{ Method Description Placeholder }}

```yaml
Name: Info
Return Type: Void
Hidden: False
Static: False
Definition: Void Info(LogMessage Message)
```

## Log(LogMessage Message)
{{ Method Description Placeholder }}

```yaml
Name: Log
Return Type: Void
Hidden: False
Static: False
Definition: Void Log(LogMessage Message)
```

## RollLog(String LogFile, Boolean Always)
{{ Method Description Placeholder }}

```yaml
Name: RollLog
Return Type: Void
Hidden: True
Static: False
Definition: hidden Void RollLog(String LogFile, Boolean Always)
```

## Verbose(LogMessage Message)
{{ Method Description Placeholder }}

```yaml
Name: Verbose
Return Type: Void
Hidden: False
Static: False
Definition: Void Verbose(LogMessage Message)
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


