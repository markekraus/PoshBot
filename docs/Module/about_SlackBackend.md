# SlackBackend
## about_SlackBackend

# SHORT DESCRIPTION
Describes the SlackBackend Class

# LONG DESCRIPTION
{{ Long Description Placeholder }}


# Constructors
## SlackBackend(String Token)
{{ Constructor Description Placeholder }}

```powershell
[SlackBackend]::new([String]$Token)
```


# Properties
## _PSSlackColorMap
{{ Property Description Placeholder }}

```yaml
Name: _PSSlackColorMap
Type: System.Collections.Hashtable
Hidden: True
Static: False
```

## MaxMessageLength
{{ Property Description Placeholder }}

```yaml
Name: MaxMessageLength
Type: Int32
Hidden: False
Static: False
```

## MessageTypes
{{ Property Description Placeholder }}

```yaml
Name: MessageTypes
Type: String[]
Hidden: False
Static: False
```


# Methods
## _ChunkString(String Text)
{{ Method Description Placeholder }}

```yaml
Name: _ChunkString
Return Type: System.Collections.ArrayList
Hidden: True
Static: False
Definition: hidden System.Collections.ArrayList _ChunkString(String Text)
```

## _ResolveEmoji(ReactionType Type)
{{ Method Description Placeholder }}

```yaml
Name: _ResolveEmoji
Return Type: String
Hidden: True
Static: False
Definition: hidden String _ResolveEmoji(ReactionType Type)
```

## _SanitizeURIs(String Text)
{{ Method Description Placeholder }}

```yaml
Name: _SanitizeURIs
Return Type: String
Hidden: True
Static: False
Definition: hidden String _SanitizeURIs(String Text)
```

## AddReaction(Message Message, ReactionType Type, String Reaction)
{{ Method Description Placeholder }}

```yaml
Name: AddReaction
Return Type: Void
Hidden: False
Static: False
Definition: Void AddReaction(Message Message, ReactionType Type, String Reaction)
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

## GetBotIdentity()
{{ Method Description Placeholder }}

```yaml
Name: GetBotIdentity
Return Type: String
Hidden: False
Static: False
Definition: String GetBotIdentity()
```

## GetUser(String UserId)
{{ Method Description Placeholder }}

```yaml
Name: GetUser
Return Type: SlackPerson
Hidden: False
Static: False
Definition: SlackPerson GetUser(String UserId)
```

## LoadRooms()
{{ Method Description Placeholder }}

```yaml
Name: LoadRooms
Return Type: Void
Hidden: False
Static: False
Definition: Void LoadRooms()
```

## LoadUsers()
{{ Method Description Placeholder }}

```yaml
Name: LoadUsers
Return Type: Void
Hidden: False
Static: False
Definition: Void LoadUsers()
```

## MsgFromBot(String From)
{{ Method Description Placeholder }}

```yaml
Name: MsgFromBot
Return Type: Boolean
Hidden: False
Static: False
Definition: Boolean MsgFromBot(String From)
```

## Ping()
{{ Method Description Placeholder }}

```yaml
Name: Ping
Return Type: Void
Hidden: False
Static: False
Definition: Void Ping()
```

## ReceiveMessage()
{{ Method Description Placeholder }}

```yaml
Name: ReceiveMessage
Return Type: Message[]
Hidden: False
Static: False
Definition: Message[] ReceiveMessage()
```

## RemoveReaction(Message Message, ReactionType Type, String Reaction)
{{ Method Description Placeholder }}

```yaml
Name: RemoveReaction
Return Type: Void
Hidden: False
Static: False
Definition: Void RemoveReaction(Message Message, ReactionType Type, String Reaction)
```

## ResolveChannelId(String ChannelName)
{{ Method Description Placeholder }}

```yaml
Name: ResolveChannelId
Return Type: String
Hidden: False
Static: False
Definition: String ResolveChannelId(String ChannelName)
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

## UserIdToUsername(String UserId)
{{ Method Description Placeholder }}

```yaml
Name: UserIdToUsername
Return Type: String
Hidden: False
Static: False
Definition: String UserIdToUsername(String UserId)
```

## UsernameToUserId(String Username)
{{ Method Description Placeholder }}

```yaml
Name: UsernameToUserId
Return Type: String
Hidden: False
Static: False
Definition: String UsernameToUserId(String Username)
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


