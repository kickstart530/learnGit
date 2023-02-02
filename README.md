# learnGit
repo to learn more about Git via command line.

git clone / init - copy remote codebase to local machine or Create one git repository using init

1. I used git clone (provided the URL from github to clone)

    *git clone https://github.com/kickstart530/learnGit.git*

2. create a file file1.txt to track the changes 

    *echo file1 > file1.txt*

3. run Git status command to 

    *git status*

      Command Output:

      On branch main
        Your branch is up-to-date with 'origin/main'.
        Untracked files:
        (use "git add <file>..." to include in what will be committed)
        
        file1.txt
        
4. Add the file to git hub for tracking changes.
    *git add file1.txt*
    
5. Push the file to git repo, this will update the repo to have this file called File1.txt
    *git push main*
