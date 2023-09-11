# 2023-09-11-git-521
- add : It adds all the file from staging area to remote repository
- commit : It commits all the files that are changed to the remote repository
- push : It pushes the changes from local to remote repo
- pull : We can pull any changes from remote to local repo

- add: adding the <filenames> to the staging area
- commit -m "Message":commit with a message everything in the staging area
- push <where> <what> : pushes the history/commits to the remote (where) using the commits from the specified branch (what)
- pull <where> <what> : pulls( updates) the local repo with contents in the remote (where) using the information in the specified branch (what)

git log
git log --oneline : hows the log in condenced format
- this may open a terminal program called `less' that lets you scroll
- use `q` to quit out of less

- git diff :  show you the difference bet your changes and the last know git state
-  diff --staged:  shows you the diff of the files in staging area

-  If you want to remove any files from the staging area i.e sometimes we dont want some files to commit to github so with this command you can remove the file staging area so that it wont be used during commit `git restore --staged README.md`
-  `restore --staged <file> : unstages <file> from staging area
-  touch :

-  ls -l
-  ls -al
-  .gitignore : is the file where we can ignore the file that is set in this file. here we wither keep the actual file name or any specific pattern.
  Example : *.csv (ignore all csv), *.pdf (ignore all pdfs)

- git restore <filename> : it restores/undo the files that are deleted
- git revert <commit_number>  : It takes all the of the changes in a particular commit. Undos the chnages in the commit specified in any specified commit.
