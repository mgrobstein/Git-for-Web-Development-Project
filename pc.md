# Setting Up Your Computer

Welcome to day 1 at BloomTech, today we are going to spend time setting up your computer and learning the tools that you will be using to complete this program. Just like day 1 at a job, you will need to get your environment set up to build and run your code. Complete the set up tasks below and then get started on the research questions. Once you have finished check out the submission instructions in the `README.md` file to turn in your assignment for the day. 

## Set Up Tasks 
1. [x] [Download gitbash]() - Windows computers speak in a language called powershell however we will be speaking to our computers in a language called unixshell, in order to all be speaking the same language if you are using a PC you will need to download gitbash and use this program instead of the native command line. Whenever you see an instruction to use the terminal that will be your queue to open up gitbash. On a PC gitbash will be your terminal. 
2. [x] sign up for a [GitHub account](https://github.com/join) - please use a professional username. We recommending using your `firstname` `lastname`
3. [x] [Set up your SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) - GitHub uses SSH to keep their files secure. You will need to set up one SSH key for every computer that you want to access your GitHub account on. Please ensure you go through all of the steps to generate a new key, add a new key and test your connection. 
4. [x] [Download Zoom](https://zoom.us/download) - make sure your zoom display name is your `first name` `last name`
5. [x] [Download Slack](https://slack.com/intl/en-ca/help/articles/209038037-Download-Slack-for-Windows) - make sure your slack display name is your `first name` `last name` 
6. [x] [Download VS code](https://code.visualstudio.com/download) - this will be the tool you use to write all of your code. We recommend installing the following extensions: 
- [ES Lint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
7. [x] [Download Node.JS](https://nodejs.org/en/) - Please download the latest stable version. We will be using Node.JS to run the tests in all of our javaScript assignments. Test driven development is a common practice in the world of web dev. You can read more about it [here](https://www.freecodecamp.org/news/test-driven-development-what-it-is-and-what-it-is-not-41fa6bca02a2/) 
8. [x] Sign up for a free [codepen account](https://codepen.io/accounts/signup/user/free)

## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You can type your answer below the questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en) doc short for documentation are the instructions on how to use a languge, or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your google skills. 

1. What is git? What is the difference between git and GitHub?
    Git is a version control system which allows users to make changes to a shared code, upload the shared code, and keep track of these changes. GitHub is the largest cloud service which manages these versions for users.
2. Why do we create a branch?
    We use the command "get checkout -b"... and then BloomTech's convention is to name it with our firstname-lastname. Branches are used to create a modification of the forked code which we can work on to make changes, improvements, etc. The industry apparently usually requires us to name the branch the type of improvement we are working on such as "added-sidebar"
3. What is the purpose of a pull request? 
     pull request is used to update the local version to a remote version. You can use a pull to get the current version off GitHub and after updating you can push back up to GitHub.
4. What is the command you can use to switch between branches? For example you are working on a feature branch and you want to switch back to main.
    "git checkout" is the command to switch between branches. If you want to switch from "feature" branch to "main" branch you would use the code "git checkout main"
5. Explain the difference between `git fetch`, `git merge` and `git pull` what does each command do? 
    'git fetch' is used to download the contents of the fetched branch and integrate it into our working copy. You still have to switch or merge with your local copy.
    'git merge' is used to combine forked branches into a single branch. It takes two or more commits and creates a single commit history.
    'git pull' basically does both 'get fetch' and 'git merge' at the same time. It moves your current working version to the pulled version and updates the commit chain to the current pulled chain.
6. What is a merge conflict? How do you resolve a merge conflict? 
    Merges basically update the main file with what you've done to modify the main file. Merge conflicts occur when Git can't figure out which file (or parts of the file) will be the new main. This typically occurs when two people modify the same lines of code or if someone deleted a file while another person was working on it. After attempting to merge if you get a message saying "you have unmerged paths" you know something has gone wrong. There are many ways to resolve merge errors. You can modify the conflicted file. "git log --merge" will list the conflicted files.