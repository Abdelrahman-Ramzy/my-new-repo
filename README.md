# How to Create and Upload a Repository to GitHub

This guide walks you through creating a local Git repository and uploading it to GitHub.

## Step 1: Create a Local Repository

`mkdir my-new-repo`
`cd my-new-repo`
`git init`

## Step 2: Create A README File

echo "# My Project Title" > README.md

##Step 3: Add and Commit Your Files

`git add .`
`git commit -m "Initial commit with README"`

## Step 4: Create a GitHub Repository

Go to https://github.com

Click on New Repository

Name it (e.g., my-new-repo)

Do not initialize with a README (you already have one locally)

## Step 5: Connect Local Repo to GitHub

Replace <USERNAME> and <REPO> with your info:

`git remote add origin https://github.com/<USERNAME>/<REPO>.git`
`git branch -M main`
`git push -u origin main`
