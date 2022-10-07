# myfiles.test
For learning purposes

Learning how to create a file in the local repo and push the changes to GitHub repo
To do this you must have downloaded and install Git on your local pc that serves as a local repo
This is where you work with the command line interface(cli) from the open terminal
Now that git is install on you pc,you need to create the GitHub repository by typing the url in your browser https://github.com/login
Now login to your account account using your username and pw
click on the green button to create repository /import one.
slect public for everyone to see or private for a selected individuals
click on create repository
Now go to Got and open a new terminal to create a new repository
$mkdir myfiles.test
cd location to the local repo $ cd
myfiles.test and press enter
Add a file "README.md" using the command echo " learningdevop" >> myfiles.test
initialize the repo $ git init .This initializes the empty repo
Add the file you have created $ git add README.MD
Now cimmit the changes using $ git commit -m "my first commit"
create a main branch $ git branch -m main
navigate back to github and copy the url of the repoadd to origin $ hit remote add origin https:// ......
Now push the changes to github $ git push -u origin main
