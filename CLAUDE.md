## MANDATORY GIT RULES (ALL AGENTS)

### YOU MUST COMPLETE ALL 5 STEPS. A TASK IS NOT DONE UNTIL STEP 5.

1. git pull origin main
2. git checkout -b feature/short-description
3. Make changes, commit: git add . && git commit -m "description"
4. Push: git push -u origin feature/short-description
5. CREATE THE PR: gh pr create --title "description" --body "details"

### CRITICAL: Step 5 is MANDATORY. If you skip it, the task has FAILED.
### The task completion message MUST include the PR URL.
### If gh pr create fails, report the error. Do not silently skip it.

- NEVER commit directly to main
- NEVER merge branches into main
- NEVER run git merge
- Only the Board (VinR) merges PRs on GitHub
- After a PR is merged, clean up your local branch: git checkout main && git pull && git branch -D feature/branch-name
