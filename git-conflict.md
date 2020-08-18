# Reason for Conflict

Lets say we create a file a.txt with content "One" and commit it to master. Now we checkout to another branch new_branch. In the new_branch we replace content of the file a.txt with "Two" and commit it. Now checkout to master again and edit the same file a.txt so that content changes to "Three" and commit it. Now when we try to merge master with new_branch we get merge conflict as the a.txt file has changed in master without merging the changes from new_branch.
