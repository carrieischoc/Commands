### Install brew

### Update brew
> brew update

> brew upgrade # update packages installed with brew including openssh
### Create a RSA key
> ssh-keygen -t rsa # get the public key: cat ~/.ssh/id_rsa.pub, copy all and sent to It-service
### Login to the group server
> ssh BA@Server_Address # username is your BA number

> nano ~/.ssh/config # back to local and write the config file to rename the ssh connection to the server

```
Host nlproc
Hostname Server_Address
User BA
```

> ssh nlproc # new command for ssh connection

### Set the locales Language 
> nano .bashrc 
```
LANG="en_US.utf8"
export LANG
# we already have the English language and it might help when you have UnicodeEncodeError for anaconda
# ask the admin host to add your language to the global locale -a
```
> 


