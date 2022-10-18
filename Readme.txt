Git tutorial in Windows Readme file

1. Download git bash in windows
	https://git-scm.com/download/win

2. Git Commands
	git config --global user.name "siva.v"
	git config --global user.email "siva.v@phytec.in"

	git init .
	git status
	git add
	git commit -m "test file" -s
	git commit --amend
	git log
	git format-patch -1
	git am 
	git apply
	git reset commit-ID
	git reset --hard commit-ID
	git merge 
	git cherry-pick commit-ID
	git branch
	git checkout -b new-branch-name
	git remote -v
	git remote add origin  https://github.com/vsivanagulu/hellogit.git
	git push -u origin master
