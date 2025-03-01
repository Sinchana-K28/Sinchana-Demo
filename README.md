# Sinchana-Demo
This is my first project
<br>
PS D:\Git Demo\Sinchana-Demo> git --version
git version 2.48.1.windows.1
<br>
PS D:\Git Demo> git clone  https://github.com/Sinchana-K28/Sinchana-Demo.git
Cloning into 'Sinchana-Demo'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.<br>
PS D:\Git Demo> cd Sinchana-Demo<br>
PS D:\Git Demo\Sinchana-Demo> ls
Directory: D:\Git Demo\Sinchana-Demo
Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        01-03-2025     23:35             67           README.md
<br>

PS D:\Git Demo\Sinchana-Demo> ls -Force


    Directory: D:\Git Demo\Sinchana-Demo


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d--h--        01-03-2025     23:35                .git
-a----        01-03-2025     23:35             67 README.md
<br>

PS D:\Git Demo\Sinchana-Demo> git status
On branch main
Your branch is up to date with 'origin/main'.
nothing to commit, working tree clean
<br>
PS D:\Git Demo\Sinchana-Demo> git status   
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS D:\Git Demo\Sinchana-Demo> <br>
PS D:\Git Demo\Sinchana-Demo> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

no changes added to commit (use "git add" and/or "git commit -a")
PS D:\Git Demo\Sinchana-Demo> <br>

no changes added to commit (use "git add" and/or "git commit -a")
PS D:\Git Demo\Sinchana-Demo> git add index.html
PS D:\Git Demo\Sinchana-Demo> git status        
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

PS D:\Git Demo\Sinchana-Demo> git add.          
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add
PS D:\Git Demo\Sinchana-Demo> git add .
PS D:\Git Demo\Sinchana-Demo> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        new file:   index.html
<br>
PS D:\Git Demo\Sinchana-Demo> git commit -m "Add new Paragraph"
[main 82b7399] Add new Paragraph
 2 files changed, 62 insertions(+), 1 deletion(-)
 create mode 100644 index.html
PS D:\Git Demo\Sinchana-Demo> git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
<br>
<br>
PS D:\Git Demo\Sinchana-Demo> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")
PS D:\Git Demo\Sinchana-Demo> git add .
PS D:\Git Demo\Sinchana-Demo> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        modified:   index.html

PS D:\Git Demo\Sinchana-Demo> git commit -m "Add new line"
[main 70d4b23] Add new line
 2 files changed, 51 insertions(+), 1 deletion(-)
PS D:\Git Demo\Sinchana-Demo> git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 746 bytes | 746.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Sinchana-K28/Sinchana-Demo.git
   82b7399..70d4b23  main -> main
PS D:\Git Demo\Sinchana-Demo> 