this is a test demo on git and github in solavisetech institute with asaph
we did how to craate directory using "mkdir"
how to cd into that director using "cd dir"
creating a file and putting content into it using the "vi" command
cat the content to see what is inside in the terminal
move the content from the working directory to the staging area by:
a) "git add ." for adding all and "git add file" for adding a single file
b) "git init" to initiallise the directory
to remove file from a staging area, use "git rm -cached [file name]"


Move file to the local repository (how)
you first commit the file to the local repository using git commit -m "message"
"git log" to see who is doing what in the team [see the email, name, commit id, time and date]
to configure a local user for the first time, use "git config --global user.email "email address"
for the user name use "git config --global user.name "your name"
git pull
git push
git status


MOVING FROM ONE VERSION TO ANOTHER (VERSIONING)
revert to a particular version
use "git revert version id or commit id(should be the last version)"
press i, esc :wq! enter
