1. How did viewing a diff between two versions of a file help you see the bug that
was introduced?

   The diff focuses attention to the lines in the files that were changed. This allows
the user to ignore any lines that were not changed and narrow focus to the lines
that may have a problem.

---

2. How could having easy access to the entire history of a file make you a more
efficient programmer in the long term?

   Having acess to the history of a file has numerous benefits:
   - If you make a mistake you can easily go back to an earlier version that didn't have the mistake.
   - Earlier versions allow you to see changes made by collaborators
   - Earlier versions allow you to see how the file changes over time and may using a difference tool can help locate an error that was introduced.

---

3. What do you think are the pros and cons of manually choosing when to create a
commit, like you do in Git, vs having versions automatically saved, like Google
docs does?

   Manually choosing when to commit has the advantage of only committing changes that are ready and make sense. Automatic commits could lead to a scenario where errors are unintentially committed to a file. This could cause problems for other people who may be collaborating on the file. A disadvantage of manual commits is that it requires the file author to be dilligent about committing changes at the appropriate time.

---

4. Why do you think some version control systems, like Git, allow saving multiple
files in one commit, while others, like Google Docs, treat each file separately?

   The difference is most likely due to the different audiences for each system and the different use cases. Systems like Google Docs are intended for widespread public consumption where people tend to work on a single document at a time, which is most likely unlrelated to other documents.

   Git is intended for a technical audience that often work on many related files at the same time. A common use case is to see all of the files that were affected by a commit when fixing bugs or reviewing work done by others.

---

5. How can you use the commands git log and git diff to view the history of files?

   The git log command will show all of the commits for the files being tracked. The git log command provides a unique id for each commit snapshot; this commit id can be used to see the difference between two commits by using the git diff command. The git diff command will show the lines that have changed between the two versions of the files in the two snapshots.

---

6. How might using version control make you more confident to make changes that
could break something?

   Version control provides tools that help identify which changeset introduced an error. Further, the diff tool helps identify the lines changed and may identify the error.

---

7. Now that you have your workspace set up, what do you want to try using Git for?

    Git is useful for tracking file changes and experimenting with new code and features. Git is also useful for collaborating with others, and for learning from other people's code projects.