# use_of_git
How to use git and their steps?

Git is a version control system that allows you to keep track of changes made to your code over time. GitHub is a popular online platform that provides hosting for Git repositories and collaboration tools. Here are the basic steps to use Git and GitHub:

Install Git: Download and install Git on your computer. You can download Git from the official website (https://git-scm.com/downloads).

Create a new repository: Create a new repository on GitHub by clicking the "+" icon in the top-right corner of the website and selecting "New repository". Give your repository a name and a description.

Clone the repository: Clone the repository to your local machine by running the following command in your terminal:

bash
Copy code
git clone https://github.com/your-username/your-repository.git
Replace "your-username" and "your-repository" with the actual username and repository name on GitHub.

Make changes: Make changes to the code in your local repository using your preferred text editor or IDE.

Stage changes: Stage the changes you have made using the following command:


Copy code
**git add .**
This command stages all the changes in your repository.

Commit changes: Commit the staged changes with a commit message using the following command:


Copy code
**git commit -m "commit message"**
Replace "commit message" with a short description of the changes you have made.

Push changes: Push the committed changes to your remote repository on GitHub using the following command:


Copy code
**git push origin main**
This command pushes the changes to the "main" branch on GitHub.

Pull changes: If someone else has made changes to the remote repository since the last time you pulled changes, you may need to pull the changes first before you can push your own changes. This will help you avoid conflicts with the changes made by others.


Copy code
**git pull origin main**
This command pulls changes from the "main" branch on GitHub to your local repository.

These are the basic steps for using Git and GitHub. You can also use other Git commands and GitHub features for collaboration, branching, merging, and more advanced workflows.
