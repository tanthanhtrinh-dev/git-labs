

## Scenario 1: Revert Uncommitted Changes (Reset to Last Commit)
```bash
# Use the following command to discard changes to specific files:
git checkout -- <file>

# If you want to revert all uncommitted changes:
git checkout -- .

 # If the changes have been staged but not committed, you can unstage them with:
git reset <file_name>



