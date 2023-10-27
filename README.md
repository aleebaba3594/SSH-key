# SSH-key for github both for windows and ubuntu
* `ssh-keygen -o -t rsa -C "your@email.com"`
* `press enter `
* `press enter`

```Your identification has been saved in /Users/username/.ssh/id_rsa.
Your public key has been saved in /Users/username/.ssh/id_rsa.pub.
The key fingerprint is:
01:0f:f4:3j:ca:89:d6:17:a6:7d:f0:68:9d:f0:e2:db your@email.com
The key's randomart image is:
+--[ RSA 2048]----+
|                 |
|                 |
|        . E +    |
|       . o = .   |
|     . T !=   o  |
|       o.0 . o   |
|       o .+ .    |
|      . o-..     |
|       .+=o      |
+-----------------+
after seeing this
```
* `type C:\Users\YourUsername\.ssh\id_rsa.pub`    (replace your username)                 //windows
* `cat ~/.ssh/id_rsa.pub `                                                                //ubuntu
* copy the whole key and paste it into the github account.... it will look like this


ssh-rsa AAAAB3NzaC1yc2EAAAABIwAAAQEA879BJGYlPTLIuc9/R5MYiN4yc/YiCLcdBpSdzgK9Dt0Bkfe3rSz5cPm4wmehdE7GkVFXrBJ2YHqPLuM1yx1AUxIebpwlIl9f/aUHOts9eVnVh4NztPy0iSU/Sv0b2ODQQvcy2vYcujlorscl8JjAgfWsO3W4iGEe6QwBpVomcME8IU35v5VbylM9ORQedera6wvZMVrPECBvwItTY8cPWH3MGZiK/74eHbSLKA4PY3gM4GHI450Nie16yggEg2aTQfWA1rry9JYWEoHS9pJ1dnLqZU3k/8OWgqJrilwSoC5rGjgp93iu0H8T6+mEHGRQe84Nk1y5lESSWIbn6P636Bl3uQ== your@email.com


