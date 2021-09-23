# FBChecker
## General
Check if a password correspond to an email for Facebook Account. All you need is a _passowrd_ and an associated _email_, you can check via bash if the password corresponds to the target email. The script provides:
 - Check if the password is correct for a given email
 - Check if it is enabled Double-Check for the target account
 - You can verify a list of password (up to 20 attempts per time)

## Features

You can choose between manual insertion or importing a _.csv_ file with separator ";". The result is a nice screen that informs you if the login is correct, if the password is bad, of there is double-check.

You get some useful information and an HTML-OUTPUT page that you can read to see the output of the operation.

Some characters are not allowed

## Note
The only scope of the software is to test the security of a Facebook account, then it is out of the scope of this project the hacking of the same.
In fact, if the account has enabled a Double Factor Safety (SMS, Code Generator, ...) you can only knows the password of the Facebook Account without log in.
