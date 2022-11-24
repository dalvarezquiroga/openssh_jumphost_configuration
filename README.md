# Openssh Jumphost Configuration

![Cost](/assets/diagram.png)

We have many AWS account in different regions and we need a easy way to connect vía SSH to some servers.  This guide is a help to configure your VM to access easily.

# Technologies we’ll use:

*  OPENSSH

# Pre-requisites:

Please ensure that you have all certificates in your local and the config file created with the describe configuration:

```bash
touch ~/.ssh/config
chown YOUR-USER:YOUR-USER ~/.ssh/config
chmod 644 ~/.ssh/config
```

# Use:

Use as reference the file called "config" and adapt updating the IPs or DNS with your situation or arquitecture.

![Yes](/assets/think-smart.gif)


# Testing

If everything is working well, you will be connected in the instance if not try to debug with verbose mode --> ssh -vvv

![Result](/assets/test.png)

# Licence

Apache

# Information

More info --> 

https://medium.com/maverislabs/proxyjump-the-ssh-option-you-probably-never-heard-of-2d7e41d43464

https://www.ssh.com/academy/ssh/config

https://en.wikibooks.org/wiki/OpenSSH/Cookbook/Proxies_and_Jump_Hosts

David Álvarez Quiroga
