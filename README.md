# ML
git checkout -b feature-branch
git merge feature-branch
git stash save "your stash message"
git stash apply (to target branch)
git fetch origin
git rebase origin/feature-branch
git rebase --continue
git push origin main
git merge feature-branch -m "Your custom commit message here"
git tag v1.0 <commit-SHA>
git cherry-pick ABC123^..DEF456
git show <commit-ID>
git log -n 1 abc123
