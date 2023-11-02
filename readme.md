## New Folder Local

Created a new folder locally without adding to git.
1. Initialization<br/>
    -> git init

2. Check for status of files/file<br/>
    -> git status<br/>
            -> if in red then is not commited.<br/>
            -> else if green then commited.<br/>

3. Adding before commiting<br/>
    -> To track files before commiting use:<br/>
        ->  git add .  [for all files]<br/>
        ->  git add <filename> [for specific files]<br/>

4. Check step 2 again.

5. Commiting the file<br/>
    -> To commit the changes created use <br/>
        -> git commit -m "[message which could be created readme.md or updated or any action performed]" -m "[This part is for desc]"<br/>

6. Make it LIVE<br/>
    -> Since the repository is not cloned from a git repository then <br/>
        -> Create an empty repository in github from the website.<br/>
        -> Copy the HTTPS or SSH(if you have created it.) link.<br/>
        -> git remote add origin master [This creates a local remote connection with the local machine repo to the github repo on the master ]
        -> git push origin master [This adds it to the repo].
        