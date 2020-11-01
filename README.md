# Hacking
## Password Stealing
### Edge Passwords (windows credential manager) Windows only
These resources are for java
- https://github.com/dariusz-szczepaniak/java.jna.WindowsCredentialManager (library)
- https://stackoverflow.com/questions/55233269/how-to-retrieve-username-and-password-from-windows-vault-using-java (question on stack overflow)
- [ ] To Do: add python resources

### Chrome Passwords
#### Windows
Stored in file `C:\Users\XXXXXX\AppData\Local\Google\Chrome\User Data\Default\Login Data`
- https://www.nirsoft.net/utils/chromepass.html (tool for extracting passwords)

This can be swiped with all good programming languages, like Python, Java and C#

### Firefox Passwords
This one is the hardest to hack
Passwords are stored in directory `%appdata%\Mozilla\Firefox\Profiles\`, in files:
- `key4.db`
- `logins.json`

## Token Logging
### Minecraft Session Token
Resets when Minecraft launcher is opened, so when victim closes the launcher the token is still valid (but when victim reopens launcher, it gets invalidated)
