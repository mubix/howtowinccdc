
# Passwords

#### Change all user's password in the "User" OU to `MyPassw0rdChanged!` and forces a password reset after that.
```
dsquery user ou=Users,dc=corp,dc=somewhatrealnews,dc=com | dsmod user -pwd MyPassw0rdChanged! -mustchpwd yes
```
##### Effect on Red Team

First off, it obviously changes passwords to something more complex, but it also sets the accounts to "***Must Change 
Password at Next Logon***". This cripples some Red Team tools that won't alert the Red Teamer that this setting is in
place. Even if the Red Teamer has the right password or has stolen it from somewhere else, it will still give an
access denied to any asset until the password is set.

##### Gotchas

This technique is easy and fast, however, it _only_ changes users that are in the Users OU. There are other users that 
it's important to change the passwords for that aren't in the Users OU
