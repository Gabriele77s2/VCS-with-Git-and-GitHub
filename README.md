# Version Control System with Git and GitHub

**Description**: Learn to use Git for version control and GitHub for collaboration.
- **Tasks**: Initialize a Git repository, commit changes, create branches, merge branches, and use GitHub for collaboration.
- **Tools**: Git, GitHub.
- **Learning Outcomes**: Understand version control basics, collaborative workflows, and repository management.

### Step 1: Install Git

**Install Git on your local machine:**
- Follow the installation guide from the [official Git documentation](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

### Step 2: Set Up Git

**Configure your Git username and email:**
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Step 3: Initialize a Git Repository

**Create a new directory and initialize a Git repository:**
```bash
mkdir my-project
cd my-project
git init
```

### Step 4: Create and Commit Files

**Create a README file and commit it:**
```bash
echo "# My Project" > README.md
git add README.md
git commit -m "Initial commit"
```

### Step 5: Create Branches and Merge

**Create a new branch and switch to it:**
```bash
git checkout -b feature-branch
```

**Make changes and commit them:**
```bash
echo "Some changes" >> README.md
git add README.md
git commit -m "Add changes to README"
```

**Switch back to the main branch and merge the feature branch:**
```bash
git checkout main
git merge feature-branch
```

### Step 6: Set Up GitHub

**Create a GitHub account if you don't have one:**
- Go to [GitHub](https://github.com/) and sign up.

### Step 7: Create a GitHub Repository

**Create a new repository on GitHub:**
1. Go to your GitHub dashboard.
2. Click "New" to create a new repository.
3. Name your repository (e.g., `my-project`) and click "Create repository".

### Step 8: Push Local Repository to GitHub

**Add the remote repository and push your changes:**
```bash
git remote add origin https://github.com/your-username/my-project.git
git branch -M main
git push -u origin main
```

### Step 9: Collaborate on GitHub

**Clone a GitHub repository:**
```bash
git clone https://github.com/your-username/my-project.git
```

**Create a pull request:**
1. Make changes in a new branch and push them to GitHub.
2. Go to the repository on GitHub.
3. Click "Compare & pull request" to create a pull request.

### Step 10: Review and Merge Pull Requests

**Review the pull request on GitHub and merge it:**
- Go to the "Pull requests" tab, review the changes, and click "Merge pull request".
