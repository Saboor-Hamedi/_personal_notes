# MySQL Create a new user
1. Login into ```mysql```
    * ```CREATE USER 'username'@'localhost' IDENTIFIED BY 'password'```
2. CREATE USER 'new_user'@'localhost' IDENTIFIED BY 'password';
    * ```CREATE USER 'username'@'%' IDENTIFIED BY 'password'```
3. That is it, now you have a new ```username``` with full privileges. There is one more step to do which is tell
```mysql``` that we have got a new user. 
    * ```FLUSH PRIVILEGES```
