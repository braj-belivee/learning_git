# learning_git

This repository was cloned to terminal using ssh mechanism

 1) ssh keygen -t rsa, this generates a ssh key
 2) In terminal eval"$(ssh-agent -s)"
 3) ssh -add ~/.ssh/rsa 
 This add the the private SSH to the SSH authentication agent , so we dont need to configure again and again
 4) Verify using
        ssh -add -l
 5) The .pub file will be stored in desired location of your or by default to Users/pavan/.ssh , this folder has the token
        cat ~/.ssh/id_rsa.pub
 6) Copy the token and paste it to the add new SSH key in the github
 7) Test Github SSH Access
       ssh -T git@github.com

 8) Output :
      Hi braj-belivee! You've successfully authenticated, but GitHub does not provide shell access.
    
This repository is used  to learn git advance concepts such as cheery-pick, rebase, merge etc 
