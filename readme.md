## GIT

0.To get a folder from github on your local machine<br/>
-> Go to the terminal within vscode<br/>
-> use git clone {HTTPS or SSH link}

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
        -> git remote add origin [link pasted]<br/>
        -> git remote add origin master [This creates a local remote connection with the local machine repo to the github repo on the master ]
        <br/>
        ->{optional} if you don't want to type the entire <u>origin master</u> then use git remote add -u origin master<br/> 
        -> git push origin master [This adds it to the repo].

<hr>

## Branching
 
0. To know which branch your are on and the number of branches use <br/>
->git branch<br/>
[This will show the different branches and then with an asterisk symbol (*) shows which branch we are currently on]<br/>

1. To Create new branch <br/>
-> To create a new branch we use<br/>
-> git checkout -b [branch name]<br/>
-> eg: git checkout -b feature-1-readme <br/>

2. Switch between branches<br/>
-> git checkout<br/>
-> or git checkout {name of branch}<br/>

3. To see the differences between the two branches<br/>
-> go to the main branch[step 2] then<br/>
git diff [branch name]

4. To push the branch use<br/>
-> git push <br/>
-> it will provide a syntax use -u instead of upstream<br/>
-> so code is<br/>
 git push -u origin feature-1-readme <br/>

5. Create a pull request . Go to Github to create a pull request and merge them

<hr>

## Reset

0. To reset a git action performed use the<br/>
-> git reset [filename]

1.To undo a commit<br/>
-> git reset HEAD~1<br/>
-> In the above case it goes back 1 step behind the commit action performed<br/>
-> "HEAD" is a pointer to the last commit.

2. To undo a specific commit<br/>
-> git log<br/>
-> This shows all the commits in all chronological order.<br/>
-> so from there goto the hash of the commit and copy<br/>
-> git reset [hash function eg(6218316236sgddg.....)]<br/>

3. To Completely remove the commits performed<br/>
-> git reset --hard [hash function eg(6218316236sgddg.....)]<br/>
-> in this case head points to a different commit.<br/> 

<hr>

## Forking.

0. To make a pr to a repo or just branch off the code<br/>
go to the repo you wish to fork<br/>
click the fork and select your account<br/>
so if you wish to add changes then create a pull request 




