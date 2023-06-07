# Project: Create and Setup Your Git and GitHub Account

<h2>Description</h2>

Welcome to my first repository as a full-stack engineer! In this project, I will guide you through the process of creating and setting up your Git and GitHub account. By the end of this project, you will have a solid foundation for version control and collaboration using Git and GitHub.

<h2>Steps</h2>

<h5>1.InstallGit:</h5> If you haven't installed Git on your computer yet, make sure to do so. You can download Git from the official website: git-scm.com.
This is my first project using Git. I'm learning how to use version control and collaborating with others on software development.

<h5>2.Configure Basic Info:</h5> Open your terminal and navigate to your home directory. Configure your basic information, including your name and email address, which will be associated with your commits. This can be done using the following commands:

~~~
$ git config --global user.name "Your Name"
$ git config --global user.email "yourname@example.com"
~~~

Create Repository on GitHub: Visit github.com and log in to your account. Using the graphical interface on the website, create a new repository called "zero_day". Make sure the repository is public and does not include a README, .gitignore, or license file. Set the description as "This is my first repository as a full-stack engineer."

<h5>3.Initialize Git Locally:</h5> Back in your terminal, navigate to your desired directory and create a new directory called "zero_day":

~~~
$ cd path/to/your/directory
$ mkdir zero_day
$ cd zero_day
~~~

<h5>4.Initialize Git and Add Remote Origin:</h5> Initialize Git in the "zero_day" directory and add the remote origin pointing to your GitHub repository:

~~~
$ git init
$ git remote add origin https://github.com/yourusername/zero_day.git
~~~

<h5>5.Create README.md:</h5> Use your preferred command line editor (e.g., Emacs, Vim, Nano) to create a file named README.md inside the "zero_day" directory. The README.md file is essential for providing project documentation and information. Feel free to write a brief Markdown text introducing this project.

<h5>6.Commit and Push:</h5> Add the newly created README.md file to the Git repository, commit the changes with the message "My first commit," and push the changes to the remote server (GitHub):

~~~
$ git add README.md
$ git commit -m "My first commit"
$ git push origin master
~~~
