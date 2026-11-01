cd D:\code\xxxxxxxxxx
Save-ClipToFile README.md
git diff
git add -A
git commit -m "docs: rewrite README"
git push -u origin HEAD
gh pr create --fill