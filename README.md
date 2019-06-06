# demo
git testing

git log
git log --oneline

Undoing things
1.checkout commit(safe)
2.revert commit(not very safe)
3.reset commit (not safe)

git reset <commit num>
git reset <commit num> --hard

branches

to create branch
	git branch <branch-name>
to check all the branches
	git branch -a
to go to a branch
	git checkout <branch-name>
to delete branch
	git branch -D <branch-name>

shortcut
	git checkout -b feature-a

Collaborating on git hub
	git pull origin master
	git checkout -b index-html
	git push origin index-html
