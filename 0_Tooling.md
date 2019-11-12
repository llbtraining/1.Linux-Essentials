Visual Studio Code remote
===========================
Autosave:
- Go to Preferences
- search for autosave
- choose after delay in the the drop down
- Auto Save Delay set to 1000

Remote: instructions below are for Mac
- From the market place, install "Remote - SSH"
- Once installed, click on the bottom left the icon that looks like >< (https://octodex.github.com/images/yaktocat.png)
- Choose connect to host / add new host. Enter the EC2 IP/FQDN then enter
- Choose a configuration to update, then click Open
- The section for the new host should look like:
    Host ec2-3-85-107-3.compute-1.amazonaws.com
         HostName ec2-0-00-000-0.compute-1.amazonaws.com
         User ec2-user
         IdentityFile ~/.ssh/your_keypair.pem
         IdentitiesOnly yes