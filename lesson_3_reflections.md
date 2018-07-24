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