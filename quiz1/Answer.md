# answer
1.

git reset --hard HEAD~
git merge Addb --no-ff

2.

git reset --hard HEAD~
git checkout Addb
git rebase master
git checkout master
git merge Addb --no-ff

3.

git reset --soft HEAD~
git commit --amend

4.

git blame a
git revert ff858d8

