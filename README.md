## Link to JsFiddle (Online HTML/CSS/Js Playground)

https://jsfiddle.net/

## Steps
1. Download Git client (git-scm.com)
2. Create a directory of your choice
3. Open that directory
4. Right click > Select More Options -> Open GIT Bash Here
5. This opens the git client

## Initializing a repo
1. run `git init`

## Timeline
1. I create a file. { Goto explorer, right click -> new file }
2. What are the changes? :> git status
3. Good. Lets accept those changes :> git add --all
4. Lets finalize the changes :> git commit -m "added new files"
5. Make some edits to the previous file and add new file
6. What are the changes?
7. What are the actual changes?
8. Okay. Lets accept those changes
9. Lets finalize the changes

## Github

1. Signup
2. Create a new repo { Github - Public, Private }
3. URL
	- Clone the project
	git clone URL
	
## Linking local and Server repo
1. Start at the server
	- Create a new repo
	- clone in your machine
		> git clone URL
2. Start at local
	- Initialize a repo in your file system
		> git init
	- Create a new empty repo in the server
	- Link up your local and server
		> git remote add origin URL
	- push your content to server
		> git push
	- Pull your changes from server to local
		> git pull

## List of commands that might be useful
	> git init
	> git status
	> git diff
	> git add --all
	> git commit -m "your commit message"
	> git push
	> git pull
	> git clone
	> Create a new branch
		> git checkout -b branch-name
	> Merge branches
		> git merge branch-name --no-ff
	> git log


## Branching
1. Create a new branch: path-1
2. Make some changes
3. Commit
4. Get back to master
5. No change??


