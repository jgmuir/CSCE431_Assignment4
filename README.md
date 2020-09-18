# CSCE431_Assignment4

Instructions for Assignment 4
1. For this assignment you should work in your own github public repository. Github classroom repository link wouldn’t be provided. This is to ensure that the code is pushed to your Heroku without any issues.
2. Create your own github repository and make sure it contains dev, test and master branches. Clone this repository locally.
3. Create a local copy of your dev branch. Command - $ git branch dev
4. Create a local copy of your test branch. Command - $ git branch test
5. Validate that you have three local branches dev, test, master (this one is automatically created when you clone). Command - $ git branch. It should show these three branches and master should be checked out (* pointer)
6. Checkout the dev branch. Command - $ git checkout dev
7. Add your changes to the staging area $ git add .
8. Commit your changes $ git commit -m "your commit message"
9. Push the changes $ git push <remote> <branch> (NOTE: here the branch should be *dev* and remote is origin)
10.Create a pull request and merge the changes *from dev to test*
11.Create a pull request and merge the changes *from test to master* 
12.Checkout the master branch. Command - $ git checkout master
13.Pull the merged changes from the origin into your local copy of master. Command - $ git pull origin master
14.Add your configuration changes (for Heroku the database should be postgres, change the gemfile and database.yml accordingly)
15.Create a Heroku App and push these changes to the heroku master
15.Push your changes to your Github's master as well. Command - $ git push origin master
16.Submit your heroku app link and github repository link on E-Campus 
