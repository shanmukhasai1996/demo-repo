# Demo

Learning Github using VScode
Video - https://www.youtube.com/watch?v=RGOj5yH7evk


# Commands till now 

open terminal from view on vscode
run following commands to clone folder into local :

git clone https link/ssh key


To change the directory :
cd demo-repo 

Run ls -la to show all files, hidden files in the folder:
ls -la

Run clear command to clean the terminal i.e. remove previous records:
clear

Run git status command to track the changes (all files updated/deleted but haven't saved in commit yet) :
git status

Run git add command to track untracked, modified section (git add . : to track everything, git add index.html : to track specific file ) :
git add .

After running above add command all modification are tracked ( i.e. kind of saving so that it can later commit to main branch )

to commit into local branch run command git commit -m "message on what & why commit is being made" -m "description box :
git commit -m "Added index.html" -m "some description"

to merge to main run :
git push

Generate SSH key by running below command in local terminal :
ssh-keygen -t rsa -b 1996 -C "github@mail.com"

the above command generates 2 files. .pub file is public file that can be shared to github , the other should not be shared (its private). It is proof that it created the pub key.

The below command prints the key:
cat testkey.pub 

To upload the key, select the key to copy , the other way is to : pbcopy < ~/testkey.pub