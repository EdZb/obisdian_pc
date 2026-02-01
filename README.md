# obisdian_pc

note for setting!
https://dev.to/padiazg/how-to-sync-your-obsidian-vault-using-github-a-complete-guide-2l08
1. personal access token -- fine-gained ... -- permission -- contents -- read and write + read only (meta data)
2. git add .gitignore
3.  git remote set-url origin git@github.com:EdZb/obisdian_pc.git
4. git branch -m main 如果已经设置则使用git branch -m master main
5. 用ssh替换https
6. 为了让branch默认为origin/main
	```
  	git checkout main
	git branch --set-upstream-to=origin/main main
	git status -sb
	```
7. 