# Github Mini Mastery Exercise

## Setup

Run the following command in your terminal:

```bash
mkdir -p ~/workspace/quizzes/static-web/github && cd $_
```

This will create a project folder and cd you into it. 

Click the green "clone or download" button and then click the clipboard icon to copy the url for this repo.  
On the command line type `git clone` and then paste in the copied url and hit return/enter. This will pull this repo into your local folder and initialize a local repo for you. **Note:** You do not need to run `git init` or `git remote add origin` when cloning like this.

All of your quiz work should be on a branch, NOT on master. To do this, type:

```bash
git checkout -b quiz
touch index.html
```

You are now ready to work in the `quiz` branch.

When your work in complete, push up the branch (`git push origin quiz`) and submit the pull request on Github.

## Instructions

Create the index.html page and place your name in the `<body>` within an `<h1>` tag.

Complete the rest of the instructions to push your branch and submit a pull request on Github.

Once your pull request has been approved, you will merge the branch with the master and delete the branch.
