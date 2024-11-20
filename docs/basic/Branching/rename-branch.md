# Brannching

## **Scenario 1:** Rename the Current Branch


1. Check Out the Branch You Want to Rename: 
```bash 
git checkout <branch-name>
```

2. Rename the Current Branch: 
```bash
git branch -m <new-branch-name>
git branch -m new-feature-branch
```

## **Scenario 2:** Rename a Different Branch
    1. Rename the Branch Directly:
```bash
git branch -m <old-branch-name> <new-branch-name>
```

**For examples**
```bash
git branch -m feature-branch new-feature-branch
```
    
## **Scenario 3:** Push the Renamed Branch to Remote
    1. Delete the Old Branch on the Remote:
    2. Set the Upstream for the New Branch:
    3. 
```bash
git push origin <new-branch-name>; git push origin --delete <old-branch-name>;git push --set-upstream origin <new-branch-name>;
```

## Example Workflow for Renaming a Branch    
- Rename the branch:
- Push the renamed branch to the remote:
- Delete the old branch on the remote (if necessary):
- Set the upstream for the new branch:

```bash
git checkout feature-branch; git branch -m new-feature-branch;
git push origin new-feature-branch; 
git push origin --delete feature-branch;
git push --set-upstream origin new-feature-branch;
```
