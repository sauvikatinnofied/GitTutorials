# GitTutorials

Sample Repository to learn git essentials.

## Basic Set Up Commands
```
cd .../To your project's root directory
```
Or you can simply create a local git repo with the following command
```
git init <My_Project_Root_Folder>
```
Now create a remote repository in your remote server. Suppose the url is
`https://github.com/sauvikatinnofied/GitTutorials.git`. So add your remote with the following command

```
git remote add origin https://github.com/sauvikatinnofied/GitTutorials.git
```

Now you can follow the basic commands to for the following purposes.

```
//add/modify a new/existing file
git add FileThatIsAddedOrModified
//or
git add --all // for adding all affected files

git commit -m 'Your commit message'
git push feat-README-1 // Pushing to a specific brach or you can simply use
git push origin master // or more simply
git push 
```

## Working with Branch and Merging Branches

### Creating a new branch
`git branch your_new_branch_name`
`git checkout your_new_branch_name` // moves to the newly created branch

#### Modify/add your files now
`git add --all` or just simply `git add your_files_those_are_added_or_modified`
`git commit -m "New feature added blah! blah! blah!"`
`git push origin your_new_brach_name`


#### Merging Two Branches

`git checkout your_merge_to_branch`
`git merge your_merger_from_branch`

#### EXAMPLE
Suppose you have new feature in *feature-2* branch. You are going to add them in *master*. So your merging commands are
`git checkout master`
`git merge feature-2`


#### Pushing changes to remote

`git add --all`
`git commit -m "Merged feature2 to master"`
`git push origin master`


