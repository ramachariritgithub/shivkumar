# shivkumar
Feature Branch Changes By GD
Hotel Booking Management System!
Developers

Mr. X.
Miss. Y.
Mrs. J.
Mr. K.
Step 1: Create Github account. Step 2: Generate Github Token? Go to Account Settings-> Developer Settings->Personal access tokens-> Token classic->Generate new token -> Save token to some text file for future use. Step 3: Install Git using the instllation document. Step 4: Configure 3 git paramters & verif it they are set correctly. Step 5: Under Github create new repository -> Step 6: Create folder to clone all the git repositories in future in winodows & clone the repo- git clone https://github.com/gangadharparde/hbms-capstone-group1.git GD@RevMINGW64 /c/scrap $ git clone https://github.com/gangadharparde/hbms-capstone-group1.git Cloning into 'hbms-capstone-group1'... remote: Enumerating objects: 7, done. remote: Counting objects: 100% (7/7), done. remote: Compressing objects: 100% (7/7), done. remote: Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 Receiving objects: 100% (7/7), 4.04 KiB | 1.01 MiB/s, done. Ensure README.md and .gitignore options are selected. Step 7: Once the code is cloned try modifying the README.md file. Step 8: In Git application traverse to the cloned project path & run below command GD@RevMINGW64 /c/scrap $ cd hbms-capstone-group1/ git status to verify unstaged changed

GD@RevMINGW64 /c/scrap/hbms-capstone-group1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
    modified:   README.md
no changes added to commit (use "git add" and/or "git commit -a")
Step 9: Add the modified files from Working directory to Satging Area git add .

    GD@RevMINGW64 /c/scrap/hbms-capstone-group1 (main)
    $ git add .

    GD@RevMINGW64 /c/scrap/hbms-capstone-group1 (main)
    $ git status
    On branch main
    Your branch is up to date with 'origin/main'.

    Changes to be committed:
    (use "git restore --staged <file>..." to unstage)
            modified:   README.md
Step 9: Add the modified files from Working directory to Satging Area git commit -m "Message What is commited"

    GD@RevMINGW64 /c/scrap/hbms-capstone-group1 (main)
    $ git commit -m "Updated README.md"
    [main 87db35a] Updated README.md
    1 file changed, 6 insertions(+), 142 deletions(-)

    GD@RevMINGW64 /c/scrap/hbms-capstone-group1 (main)
    $ git status
    On branch main
    Your branch is ahead of 'origin/main' by 1 commit.
    (use "git push" to publish your local commits)

    nothing to commit, working tree clean
Step 10: Since Local Repository is not in sync with Remote Repository we need to push local changes to remote repository. GD@RevMINGW64 /c/scrap/hbms-capstone-group1 (main) $ git push Enumerating objects: 5, done. Counting objects: 100% (5/5), done. Delta compression using up to 8 threads Compressing objects: 100% (3/3), done. Writing objects: 100% (3/3), 371 bytes | 185.00 KiB/s, done. Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 To https://github.com/gangadharparde/hbms-capstone-group1.git 53757e1..87db35a main -> main Step 11: Refresh the Github page to see the modified changes in files.

