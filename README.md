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
