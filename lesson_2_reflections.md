1. What happens when you initialize a repository? Why do you need to do it?

   Git creates a hidden folder named .git in the same directory that the git init command was executed in. The git init command must be executed to begin tracking files in the directory with the git version control system.

2. How is the staging area different from the working directory and the repository?
What value do you think it offers?

   The staging area is a virtual storage area maintained by the git version control system. When files are added to the staging area it indicates to git the files will be included in the next committed changeset. The staging area differs from the working directory in that the working directory contains all files and directories that are within it. The staging area will only contain files that have been added to it via the git add command. The staging area provides the benefit of allowing the user to decide which files will be part of the next committed changeset - offering the ability include or exclude fils as needed.

3. How can you use the staging area to make sure you have one commit per logical
change?

   To limit the staging area to one commit per logical change, only add the files that were affected by the logical
   change to the staging area. Files can be selectively added to the staging area using the git add {filename} command.
   To see the difference between files in the working directory and files in the staging area, use the git diff command.

4. What are some situations when branches would be helpful in keeping your history
organized? How would branches help?

   Branches are useful for a variety of situations. A bug fix could be isolated to it's own branch during development
   so other developers are isolated from it until it is ready. A branch could also be utilized to isolate an experimental
   new feature that may not make it into the production code. Branches also allow developers working on a team to 
   isolate their code changes from other developers until the code is complete and ready to be merged with the 
   production code.

5. How do the diagrams help you visualize the branch structure?

   The diagrams illustrate the order that commits were created as well as the hierarchy of the various branches. 
   Because branches are created from the commit that HEAD is pointing at when the branch is created, branches
   can and will have different parents. The diagram helps illustrate the branch lineage and is helpful to see
   which commits are missing from a branch and need to be merged in.

6. What is the result of merging two branches together? Why do we represent it in
the diagram the way we do?

7. What are the pros and cons of Git's automatic merging vs. always doing merges
manually?