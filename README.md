# A02
## How to use Git, Vs Code, and GitHub


Before you begin, you will need to download __Git__ through git-scm.com, creat a __Github__ account at github.com, and downlod VS Code at code.visual.com.


Step 1: Setting up __Git__
- Open your terminal and type the following commands.

"git config --global user.name 'Your Name'

git config --global user.email 'ucid@njit.edu'"



Step 2: Create a __Repository__ on __GitHub__
- After logging into your account, click the "+" and choose "New __Repository__".
- Give your __repository__ a name and add a description if you would like.
- Make it public or private.
- Finally, click "create __repository__".


Step 3: __Cloning__ your __Repository__
- Copy the URL of your project.
- Through your terminal. go to the folder where you would like your project to be stored.
- Type the folowing command to get a copy of your project, but with the link to your project:

"git clone https://github.com/username/repository.git"
- Then change to your project folder by using the cd, change directory, command.


Step 4: How to create a new __branch__
- Type the following command to work on ideas without changing your main project:

"git checkout -b new-feature"


Step 5: Saving your changes 
- After making changes in your project through VS Code be sure to save them.
- Then go back to your terminal and type the following commands to stage and __commit__ changes:

"git add.

git commit -m "Add new feature"


Step 6: How to send changes to GitHub
- Type the following command to __push__ your changes to the __remote repository__
"git push origin new-feauture'
- In GitHub, click the "__pull__ request" button. Fill in the required information, then click "create __pull__ request".
- Click "__merge pull__ request". This will add your changes to the main project. 
- __Fetch__ updates by using the command, "git fetch".
- __Pull__ your most recent changes by using the command, "git pull origin main".


Step 7: How to handle __merge conflicts__
- Git will notify you if there is a __merge conflict__
- You must first resolve conflicts within VS Code.
- Then type the following commands:

"git add .

git commit -m "Resolve merge conflict"

## Glossary

- Branch: A seperate version of yoour project where you can work on changes without affecting the main project.
- Clone: Making a copy of your project where you can work on changes without affecting the main project
- Commit: Saving your changes to the project.
- Fetch: Checking for updates from GitHub. 
- GIT: A tool that helps you keep track of changes in your code and manage different versions of your project.
- Github: A website where you can store projects online, share them with others, and collaborate.
- Merge: Combing changes from one branch into another, usually cbringing new features into the main project.
- Merge Conflict: A situation where two changes can't be combined automatically because they contradict each other. 
- Push: Sending your changes from your computer to GitHub so they can be saved online.
- Pull: Getting the latest changes from GitHub to your computer.
- Remote: The version of your project that is stored in GitHub.
- Repository: a folder that contains all the files and history of your project.
## References
- Git Tutorial for Absolute Beginners: https://www.youtube.com/watch?app=desktop&v=CvUiKWv2-C0
- How To Use GitHub for Beginners: https://youtu.be/BovIkSKStPw?feature=shared
- VS Code in 100 Seconds: https://youtu.be/KMxo3T_MTvY?feature=shared
- Intoduction to Git in VS Code: https://code.visualstudio.com/docs/sourcecontrol/intro-to-git
