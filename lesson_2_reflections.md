1. What happens when you initialize a repository? Why do you need to do it?

   Git creates a hidden folder named .git in the same directory that the git init command was executed in. The git init command must be executed to begin tracking files in the directory with the git version control system.

2. How is the staging area different from the working directory and the repository?
What value do you think it offers?

   The staging area is a virtual storage area maintained by the git version control system. When files are added to the staging area it indicates to git the files will be included in the next committed changeset. The staging area differs from the working directory in that the working directory contains all files and directories that are within it. The staging area will only contain files that have been added to it via the git add command. The staging area provides the benefit of allowing the user to decide which files will be part of the next committed changeset - offering the ability include or exclude fils as needed.

3. How can you use the staging area to make sure you have one commit per logical
change?

4. What are some situations when branches would be helpful in keeping your history
organized? How would branches help?

5. How do the diagrams help you visualize the branch structure?

6. What is the result of merging two branches together? Why do we represent it in
the diagram the way we do?

7. What are the pros and cons of Git's automatic merging vs. always doing merges
manually?