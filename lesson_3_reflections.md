1. When would you want to use a remote repository rather than keeping all of your work local?

   A remote repository is useful for sharing code with other developers. Additionally, a remote
   repository serves as an excellent backup location for your code. If anything happens to your
   computer the code can be cloned to a new disk from the remote repository.

2. Why might you want to always pull changes manually rather than having Git automatically stay
   up-to-date with your remote repository?

   With code shared to a remote repository, and given the disconnected nature of git, it is possible
   that someone will commit changes to the remote repository that you're not aware of. Manually pulling
   changes down from the remote repository allows the option to merge those code changes into your
   branch at a point-in-time that you're ready to receive those code changes - without them interferring
   with your own code changes.

 3. Describe the differences between forks, clones, and branches. When would you use one instead of
    another?

    The fork feature is limited in scope to the GitHub website. A user forks a repository when they
    don't have access to make any updates to the source repository, but would like to make changes to 
    the repository. This happens frequently with open source projects which often have many developers
    contributing to the repository. The developers fork the source repository to have a copy that they
    can work on.

    Cloning a repository creates a copy of a repository, including all of it's commit history. A 
    repository is often cloned from a remote source (like GitHub) to a local disk so a developer
    can work on the project on his local disk (in a disconnected manner). Any changes to the files
    in the repository only occur in the cloned repository until such time as the changes are pushed 
    back into the source repository.

    Branches are used to label commits in a meaningful way. A branch isolates a set of commits from 
    other branches in the repository. This allows a developer to work in an isolated workspace to 
    create experimental code features or test bug fixes; without affecting the production code line.

4. What is the benefit of having a copy of the last known state of the remote stored locally?

   Having the last known state of the remote stored locally allows you to compare the work you make
   in your local branch with the work that was present in the remote branch - without requiring an
   internet connection. 
