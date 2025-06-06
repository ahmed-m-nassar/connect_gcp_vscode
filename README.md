# connect_gcp_vscode

Create keys using GIT BASH 
ssh-keygen -t rsa -f C:/users/amahmed/.ssh/gcp_instance1_key2

In vs code config
Host gcp_instance1_key2  
  HostName 34.122.118.127
  IdentityFile C:\Users\amahmed\.ssh\gcp_instance1_key2
  User EJADA+amahmed

The user should be the same user in the public key at the end (case sensitive)
Not necessarily EJADA+amahmed
