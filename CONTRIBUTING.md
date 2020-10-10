# Contribution guide

If you are a beginner, you need to [install](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) Git on your local system. After installation, you need to configure git by running these commands on Command Prompt or Terminal.

`git config --global user.name “[firstname lastname]”`

set a name that is identifiable for credit when review version history

`git config --global user.email “[valid-email]”`

set an email address that will be associated with each history marker

----


Now, follow the below steps for contributing to the file:

Fork the repository `Hacktoberfest2020` from [Women Who Code Delhi](https://github.com/WomenWhoCodeDelhi/Hacktoberfest2020) organization and then clone it from your GitHub profile by running this command:

`git clone https://github.com/<github username>/Hacktoberfest2020.git`

Add a remote to the original repository:

`git remote add upstream https://github.com/WomenWhoCodeDelhi/Hacktoberfest2020.git`

Create a branch:

`git checkout -b <branch-name>` 

Now, create a file inside participants folder and add your basic info and save it. Refer `soumyaa1804.md` file for reference.

Check status: `git status`

It will show your changed file.

Stage all the changes: `git add .`

Commit the changes: `git commit -m <commit message>`

Push the branch to your remote repository: 
 `git push origin <branch name>`

Create a Pull Request.
