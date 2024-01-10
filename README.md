# Setup Git and GitHub for Raspberry Pi

## Configure github

```bash
     git config --global user.name "Your User Name" 

```
    
    
   ##  Add your Email to the configuration

    
``` bash
     git config --global user.email "Your Email" 
```


## Check the details 
``` bash
git config --list
```
## Create the ssh agent using following command
```bash
github@ubuntu:~/.ssh$ ssh-keygen -o -t rsa -C "email@example.com"
```
## Display SSH key
```bash 
cat id_rsa.pub
```

Add Key to the Github