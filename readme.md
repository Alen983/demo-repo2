## New Folder Local

Created a new folder locally without adding to git.
1. Initialization<br/>
    -> git init

2. Check for status of files/file
    -> git status
            -> if in red then is not commited.
            -> else if green then commited.

3. Adding before commiting
    -> To track files before commiting use:
        ->  git add .  <for all files>
        ->  git add <filename> <for specific files>

4. Check step 2 again.

5. Commiting the file
    -> To commit the changes created use 
        -> git commit -m "<message which could be created readme.md or updated or any action performed>" -m "<This part is for desc>"

6. Make it LIVE
    -> Since the repository is not cloned from a git repository then 
        -> Create an empty repository in github from the website.
        -> Copy the HTTPS or SSH(if you have created it.) link.
        -> 