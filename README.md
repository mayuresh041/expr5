C:\Users\91987>cd rev1

C:\Users\91987\rev1>git init
Reinitialized existing Git repository in C:/Users/91987/rev1/.git/

C:\Users\91987\rev1>git clone https://github.com/mayuresh041/m05.git
Cloning into 'm05'...
remote: Enumerating objects: 18, done.
remote: Counting objects: 100% (18/18), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 18 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (18/18), 4.64 KiB | 2.32 MiB/s, done.

C:\Users\91987\rev1>git checkout fb2
error: pathspec 'fb2' did not match any file(s) known to git

C:\Users\91987\rev1>git checkout -b fbn2
Switched to a new branch 'fbn2'

C:\Users\91987\rev1>git fetch origin
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

C:\Users\91987\rev1>cd repo m05
The system cannot find the path specified.

C:\Users\91987\rev1>cd m05

C:\Users\91987\rev1\m05>git fetch origin

C:\Users\91987\rev1\m05>git fetch origin
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 942 bytes | 78.00 KiB/s, done.
From https://github.com/mayuresh041/m05
   8fdad5a..f204391  main       -> origin/main

C:\Users\91987\rev1\m05>git rebase origin/main
Successfully rebased and updated refs/heads/main.

C:\Users\91987\rev1\m05>git add .

C:\Users\91987\rev1\m05>git commit -m "second"
[main 9b80ce4] second
 1 file changed, 1 insertion(+)

C:\Users\91987\rev1\m05>git fetch origin
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 952 bytes | 86.00 KiB/s, done.
From https://github.com/mayuresh041/m05
   f204391..958a753  main       -> origin/main

C:\Users\91987\rev1\m05>git rebase origin/main
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
error: could not apply 9b80ce4... second
hint: Resolve all conflicts manually, mark them as resolved with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
hint: You can instead skip this commit: run "git rebase --skip".
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply 9b80ce4... second

C:\Users\91987\rev1\m05>git add .

C:\Users\91987\rev1\m05>git rebase --continue
[detached HEAD 27474d6] savesecond
 1 file changed, 3 insertions(+), 1 deletion(-)
Successfully rebased and updated refs/heads/main.

C:\Users\91987\rev1\m05>git checkout master
error: pathspec 'master' did not match any file(s) known to git

C:\Users\91987\rev1\m05>git checkout -b tb2
Switched to a new branch 'tb2'

C:\Users\91987\rev1\m05>git merge fb2
merge: fb2 - not something we can merge

C:\Users\91987\rev1\m05>git checkout fb2
error: pathspec 'fb2' did not match any file(s) known to git

C:\Users\91987\rev1\m05>git checkout fbn2
error: pathspec 'fbn2' did not match any file(s) known to git

C:\Users\91987\rev1\m05>git branch list

C:\Users\91987\rev1\m05>git branch
  list
  main
* tb2

C:\Users\91987\rev1\m05>git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

C:\Users\91987\rev1\m05>git merge tb2
Already up to date.

C:\Users\91987\rev1\m05>git checkout tb2
Switched to branch 'tb2'

C:\Users\91987\rev1\m05>git add .

C:\Users\91987\rev1\m05>git commit -m "second"
[tb2 081f75c] second
 1 file changed, 1 insertion(+)

C:\Users\91987\rev1\m05>git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

C:\Users\91987\rev1\m05>git push origin tb2
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 521 bytes | 521.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'tb2' on GitHub by visiting:
remote:      https://github.com/mayuresh041/m05/pull/new/tb2
remote:
To https://github.com/mayuresh041/m05.git
 * [new branch]      tb2 -> tb2

C:\Users\91987\rev1\m05># expr5
expr6
