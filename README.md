# git_practice



# problems

1. failed to push #1
	```
	error: src refspec main does not match any.                      
	error: failed to push some refs to 'git@github.com:Sciencethebird/DLP_Labs.git'
	```
	solution:
	
	```
	git push <local_repo_name> HEAD:main
	# git push <local_repo_name> <local_branch>:<remote_branch>
	``` 
	why:
		- https://stackoverflow.com/questions/23241052/what-does-git-push-origin-head-mean	

1. failed to push #2