clone repository from github desktop

git add README.md
git commit -m "Commit 1"
git push
git add STEPS.md
git commit -m "Commit 1..."
git push
git add STEPS.md
git commit -m "Commit 2!"
git checkout -b bug-fix
git add STEPS.md
git commit -m "Commit 3?"
git push --set-upstream origin bug-fix
git add STEPS.md
git commit -m "Commit 4!"
git push
git merge main ---- this introduced a merge conflict
git add STEPS.md
VSCode commit button with generic merge message
git add STEPS.md
git commit -m "Commit 6"
git add STEPS.md
git commit -m "Commit 7!"
git push --set-upstream origin bug-fix-experimental
git add STEPS.md
git commit -m "Commit 8!"
git add STEPS.md
git commit -m "Commit 9!"
git checkout bug-fix
git merge bug-fix-experimental
git add STEPS.md
git commit -m "Commit 11!"
git push
git add STEPS.md
git commit -m "Commit 12"
