# A03


To create a GitHub account, visit www.github.com and click on "Sign Up" on the top right of the page. Enter the e-mail address you want to register, create a password, and then a username when prompted. Press "y" or "n" to indicate whether you'd like to receive product updates and announcements via email.
Now that you're on GitHub, look at the top right of the page and click the '+' icon. Click "New repository" when the dropdown menu appears. Enter a repository name, add a README file, and choose whether you want it to be public or private.
Now that the repository is created, it's time to download webstorm by Jetbrains. Webstorm is an integrated development environment with support for JavaScript, HTML, stylesheets, and more. Visit https://www.jetbrains.com/webstorm/ and click "Download". Once you have downloaded Jetbrains and logged in, you can start the process of linking Webstorm to your Github repository.  
Select "Get From VCS" in Webstorm. From there, you will be informed that "Git is not installed" so click on "Download and Install" next to it and Git will install automatically for you. Then, click on GitHub on the left sidebar and log into your GitHub account using the credentials you created when you were on the website. You will then see Webstorm detect your repository on Github and you can clone that repository locally to your machine to work on it via Webstorm.
The Git application is a command line that takes care of the underlying version control while Github is the collaboration platform. Using commands from Git, you will be able to do many of the things Webstorm can do such as: clone, commit, push, pull, and more.


+ **Branch** - is a unique set of code changes with a unique name. By using branches, developers can make changes safely. Each repository can have one or more branches. The main branch - where all changes get merged back into, is called master.
+ **Clone** - Cloning is used to create a copy of a specific repository or branch onto the local machine. The ability to work with the entire repository locally means all developers can work more freely.
+ **Commit** - A commit is like a snapshot of your repository. They work like save points within Git. Commits can be made to different branches and users can specify exactly what changes to include. 
+ **Fetch** - Downloads branches and tags from other repositories and the objects that complete their histories.
+ **Git** - A Version control system that allows you to easily collaborate with other developers. You can use the terminal or GUI to enter commands.
+ **GitHub** - A product that allows users to host Git projects on the cloud. It is essentially a hosting service.
+ **Merge** - Integrates the independent lines of development into a single branch. It is primarily used to combine two branches and merge multiple commits into one history.
+ **Merge Conflict** - Merge conflicts happen when merge branches have competing commits. While Git can usually resolve differences automatically, sometimes Git needs your help to resolve the conflict. Often, they happen when people make different changes to the same line in the same file. 
+ **Pull** - updates your current local branch and all remote tracking branches. Without using pull, your local branch won't have any updates present on the remote branch. It is the most common way to update your repository.
+ **Push** - Updates the remote branch with local commits. It can be thought of as update or publish. A push can be made after making a commit locally. This makes your commits accessible to others who you may be collaboraing with. Any open pull requests will be updated with the branch being worked on.
+ **Remote** - Remote repositories are hosted on the internet or network. They contain versions of your project and help you easily collaborate with others by pushing and pulling data to the remote when you need to share work.
+ **Repository** - Repositories track all changes made to files in your project to build a history. It is the .git folder inside a project.