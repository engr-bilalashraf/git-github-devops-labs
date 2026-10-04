Git Init

📌 What is git init?

git init is used to initialize a new Git repository in a directory.

It converts an existing project directory into a Git repository so Git can start tracking changes.

🔹 Syntax

git init

🔹 Basic Example

First, create a project directory:

mkdir my-project
cd my-project

Initialize Git:

git init

Git will create a hidden .git directory inside the project.

🔹 Verify the Repository

After running git init, use:

git status

You should see information indicating that you are on the default branch and that there are no commits yet.

You can also check the hidden .git directory:

ls -la

Example:

.
..
.git

The .git directory contains Git's internal repository data, including commit history, branches, and configuration.

