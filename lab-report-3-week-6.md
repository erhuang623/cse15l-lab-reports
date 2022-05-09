# Lab Report 3

## Streamlining ssh Configuration
First you make a new file called config in our .ssh folder on our local machine. Then type that command with your unique username.

![Image](ssh_config.png)
Note that the third line is specifically for windows. 

Next use the ssh command to log into your account with the specific alias you have chosen.

![Image](ssh_ieng6.png)

This is an example of the scp command copying a file into the ieng6 account. 

![Image](scp_streamline.png)

## Setup Github Access from ieng6
This is the public key on gitbuh stored in my account settings
![Image](public_github_key.png)

This is my private key which is stored in known_hosts of my .ssh folder.
![Image](private_key.png)

This image shows git commands running on the remote server.

![Image](gitCommands.png)

This is the commit [History]()

## Copy whole directories with scp -r
We can use the command
```
scp -r
```
to copy a whole directory to the remote machine
![Image](scp_mdp_1.png)
![Image](scp_mdp_2.png)

We can now log into the remote server and compile the repository.

![Image](junit_repo_tests.png)

We can also run multiple commands at a time to copy and run the tests at the same time. 
![Image](one_line.png)
![Image](one_line2.png)
