### Install brew

### Update brew
> brew update

> brew upgrade # update packages installed with brew including openssh
### Create a RSA key
> ssh-keygen -t rsa # get the public key: cat ~/.ssh/id_rsa.pub
### Login to the group server
> ssh BA@compute-01.nlproc.uni-bamberg.de # username is your BA number

> nano ~/.ssh/config # back to local and write the config file to rename the ssh connection to the server

```
Host nlproc
Hostname compute-01.nlproc.uni-bamberg.de
User ba8ma4
```

> ssh nlproc # new command for ssh connection

### Set the locales Language 
> nano .bashrc # ask the admin host to add your language to the global locale -a
```
LANG="en_US.utf8"
export LANG
```
> 


