We can make use of the following flag to get rid of public key access over SSH. Though its not advisable, its handy command to get started for internal purpose.

```
ssh -o PubKeyAuthentication=no user@server.ip
```

#### To cut short this lengthy command, use an alias

Add following line into .bash_profile(mac) or .bashrc (ubuntu)

```
  alias ssho='ssh -o PubKeyAuthentication=no'
```
