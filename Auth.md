# chatserver_docs
All docs and design specs for our client-server based chat application to rule the world!

## AUTHENTIFICATION METHOD
```csharp

private string UserName = "";  // Nickname
private string Status = ""; // online, away, offline >> maybe realized with State Pattern?
private string clientipAddress = "0.0.0.0"; // Client IP Adress
private string connectId; // PC-Name = Console.WriteLine("MachineName: {0}", Environment.MachineName);
private string passwort = "12345"; // The passwort

Description

The passwort and username and/or connectID shoud be stored in a database at first connection.
In any further connection the credentials will be checked with database entry.

```

