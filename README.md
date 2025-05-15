
# **Collaborative Workflow: Tom & Jerry Using Git and GitHub**

This mini-project is a simulation of the collaboration between Tom and Jerry. In this project we will look at installation of Git, setting up of Github repository, cloning the repository, creating branches, making changes and merging to changes back into the main branch.

# Part 1: Setup & Initial configuration

### Git Installation
visit the git official website and download git for your operating system using the installation instructions.

![git version](./img/01.%20git%20version.png)

### Git Repository
* create or sign into a github. 

* click the + sign to create a new repository.


![new repository](./img/02.%20git%20repository%20.png)

create a new repository with a `README`
* Give a repository name (e.g. ai-startup-website).
* Add a description and then click create repository.

![create repository](./img/03.%20new%20repository%20.png)

### Cloning repository
On your github repo page that you just created, click the `code` button and copy the HTTPS Url. 

* open your terminal or command prompt. 

Create a folder `git-project` and change directory into the folder by running the `cd git-project`. create a directory named `ai-startup-website` inside the git-project folder and cd into the directory where you will clone the website by running the `git clone url`

![git clone](./img/05.%20git%20clone%20.png)

* Navigate into the cloned repository.

* Create an index.html file in the cloned repository and add content into the index.html file.

confirm that changes made has not been staged for commit by running `git status`, add changes to the staging area. After this, commit the changes made and then push the main branch to Github.

![git commit & push](./img/06.%20git%20commit%20&%20push.png)


# Part 2: simulating Tom & Jerry's Work
To simulate both tom and jerry's work on the same laptop, you would need to switch between two branches.

### 1. Tom's Work
Navigate to the directory you are currently working on and check the branch to make sure its on the `main` branch.

![git branch](./img/07.%20git%20branch%20.png)

* Create a new branch for tom named **update-navigation**

* Confirm that the changes from the `main` branch to the `update-navigation` branch.

![update navigation](./img/08.%20update-navigation%20.png)

* Add tom's contribution to the index.html file using your text editor, and confirm that changes made are ready to be staged.

* Stage changes and confirm that they are ready for commit.

![status & staging](./img/09.%20git%20status%20&%20staging%20-%20tom%20.png)

Now that changes have been staged, its time to `commit` those changes and `push` those changes from your local machine to your github (remote repository).

![commit & push](./img/10.%20commit%20&%20push%20-%20tom.png)

### 2. Jerry's Work

* Switch back to the main branch
* pull the latest changes from the remote repository to ensure that you have the latest changes on the main branch.
  
![git pull](./img/11.%20git%20pull%20.png)

* Create a new branch for jerry's work
* Stage changes made by jerry to the index.html file and commit those changes with a message.
* Push jerry's changes from the local branch to the remote branch on Github.

![jerry's branch, commit & push](./img/12.%20jerry's%20branch%20&%20commit.png)
