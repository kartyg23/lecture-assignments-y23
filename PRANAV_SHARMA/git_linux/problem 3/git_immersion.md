## LAB 1 :
pranav123@LAPTOP-N6Q5RB7O:/mnt/c/WINDOWS/system32$ git config --global user.name "Pranav"
pranav123@LAPTOP-N6Q5RB7O:/mnt/c/WINDOWS/system32$ git config --global user.email "kanacool80@gmail.com"
pranav123@LAPTOP-N6Q5RB7O:/mnt/c/WINDOWS/system32$ git config --global user.email

kanacool80@gmail.com

pranav123@LAPTOP-N6Q5RB7O:/mnt/c/WINDOWS/system32$ git config --global user.name

Pranav

## LAB 2:

pranav123@LAPTOP-N6Q5RB7O:/mnt/c/WINDOWS/system32$ git config --global core.autocrlf input
pranav123@LAPTOP-N6Q5RB7O:/mnt/c/WINDOWS/system32$ git config --global core.safecrlf true
pranav123@LAPTOP-N6Q5RB7O:/mnt/c/WINDOWS/system32$ sudo apt-get install ruby-full

## LAB 3:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder$ mkdir hello
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder$ cd hello
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ touch hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ echo "hello,world" > hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git init

Initialized empty Git repository in /mnt/d/New folder/hello/.git/

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git commit -m "First Commit"

[master (root-commit) b4e0e34] First Commit
 1 file changed, 1 insertion(+)
 create mode 100644 hello.rb

## LAB 4:
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git status

On branch master
nothing to commit, working tree clean

## LAB 5:
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ echo "Hello, #{ARGV.first}!" > hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ cat hello.rb
Hello, #{ARGV.first}!
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   hello.rb

no changes added to commit (use "git add" and/or "git commit -a")

## LAB 6:
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   hello.rb

## LAB 7:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ touch a.rb b.rb c.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add a.rb b.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git commit -m "Changes for a and b"

[master 841aa5a] Changes for a and b
 3 files changed, 1 insertion(+), 1 deletion(-)
 create mode 100644 a.rb
 create mode 100644 b.rb

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add c.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git commit -m "Unrelated change to c"

[master faad5f0] Unrelated change to c
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 c.rb

## LAB 8:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git commit

[master b52db9b] "using argv"
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 d.rb

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git status

On branch master
nothing to commit, working tree clean

## LAB 9:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ vim hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ vim hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   hello.rb

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   hello.rb

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git commit -m "Added a default value"
[master fb3e299] Added a default value
 1 file changed, 3 insertions(+), 1 deletion(-)
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   hello.rb

no changes added to commit (use "git add" and/or "git commit -a")
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add .
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   hello.rb

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git commit -m "Added a comment"
[master 9224df6] Added a comment
 1 file changed, 1 insertion(+)

## LAB 10:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git log

commit 9224df65f08e364559b64eeda5c3182e7c72e657 (HEAD -> master)
Author: Pranav <kanacool80@gmail.com>
Date:   Wed May 3 22:10:44 2023 +0530

    Added a comment

commit fb3e299ead46ead3541300adb98c0440d0b9cd37
Author: Pranav <kanacool80@gmail.com>
Date:   Wed May 3 22:09:20 2023 +0530

    Added a default value

commit b52db9b79f91c513e35cb62158e5cc11ef06f3dd
Author: Pranav <kanacool80@gmail.com>
Date:   Wed May 3 21:39:26 2023 +0530

    "using argv"

commit faad5f06fd1c5ad54c7088cb11516a37a9b1be9c
Author: Pranav <kanacool80@gmail.com>
Date:   Wed May 3 21:17:35 2023 +0530

    Unrelated change to c

commit 841aa5a9697029f83514d285d493817a32ef0a34
Author: Pranav <kanacool80@gmail.com>
Date:   Wed May 3 21:17:13 2023 +0530

    Changes for a and b

commit b4e0e347973bc7b9e229f4bb9c3bd127ab743dd6
Author: Pranav <kanacool80@gmail.com>
Date:   Wed May 3 19:21:35 2023 +0530

    First Commit

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git log --pretty=oneline

9224df65f08e364559b64eeda5c3182e7c72e657 (HEAD -> master) Added a comment
fb3e299ead46ead3541300adb98c0440d0b9cd37 Added a default value
b52db9b79f91c513e35cb62158e5cc11ef06f3dd "using argv"
faad5f06fd1c5ad54c7088cb11516a37a9b1be9c Unrelated change to c
841aa5a9697029f83514d285d493817a32ef0a34 Changes for a and b
b4e0e347973bc7b9e229f4bb9c3bd127ab743dd6 First Commit
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git log --pretty=oneline --max-count=2
9224df65f08e364559b64eeda5c3182e7c72e657 (HEAD -> master) Added a comment
fb3e299ead46ead3541300adb98c0440d0b9cd37 Added a default value
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git log --pretty=oneline --since='5 minutes ago'
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git log --pretty=oneline --until='5 minutes ago'
9224df65f08e364559b64eeda5c3182e7c72e657 (HEAD -> master) Added a comment
fb3e299ead46ead3541300adb98c0440d0b9cd37 Added a default value
b52db9b79f91c513e35cb62158e5cc11ef06f3dd "using argv"
faad5f06fd1c5ad54c7088cb11516a37a9b1be9c Unrelated change to c
841aa5a9697029f83514d285d493817a32ef0a34 Changes for a and b
b4e0e347973bc7b9e229f4bb9c3bd127ab743dd6 First Commit
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git log --pretty=oneline --author=Pranav
9224df65f08e364559b64eeda5c3182e7c72e657 (HEAD -> master) Added a comment
fb3e299ead46ead3541300adb98c0440d0b9cd37 Added a default value
b52db9b79f91c513e35cb62158e5cc11ef06f3dd "using argv"
faad5f06fd1c5ad54c7088cb11516a37a9b1be9c Unrelated change to c
841aa5a9697029f83514d285d493817a32ef0a34 Changes for a and b
b4e0e347973bc7b9e229f4bb9c3bd127ab743dd6 First Commit
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git log --pretty=oneline --all
9224df65f08e364559b64eeda5c3182e7c72e657 (HEAD -> master) Added a comment
fb3e299ead46ead3541300adb98c0440d0b9cd37 Added a default value
b52db9b79f91c513e35cb62158e5cc11ef06f3dd "using argv"
faad5f06fd1c5ad54c7088cb11516a37a9b1be9c Unrelated change to c
841aa5a9697029f83514d285d493817a32ef0a34 Changes for a and b
b4e0e347973bc7b9e229f4bb9c3bd127ab743dd6 First Commit

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git log --all --pretty=format:'%h %cd %s (%an)' --since='7 days ago'

9224df6 Wed May 3 22:10:44 2023 +0530 Added a comment (Pranav)
fb3e299 Wed May 3 22:09:20 2023 +0530 Added a default value (Pranav)
b52db9b Wed May 3 21:39:26 2023 +0530 "using argv" (Pranav)
faad5f0 Wed May 3 21:17:35 2023 +0530 Unrelated change to c (Pranav)
841aa5a Wed May 3 21:17:13 2023 +0530 Changes for a and b (Pranav)
b4e0e34 Wed May 3 19:21:35 2023 +0530 First Commit (Pranav)

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short

* 9224df6 2023-05-03 | Added a comment (HEAD -> master) [Pranav]
* fb3e299 2023-05-03 | Added a default value [Pranav]
* b52db9b 2023-05-03 | "using argv" [Pranav]
* faad5f0 2023-05-03 | Unrelated change to c [Pranav]
* 841aa5a 2023-05-03 | Changes for a and b [Pranav]
* b4e0e34 2023-05-03 | First Commit [Pranav]

## LAB-11:

pranav123@LAPTOP-N6Q5RB7O:/home$ find /home -name .gitconfig
/home/pranav123/.gitconfig

pranav123@LAPTOP-N6Q5RB7O:/home$ cd /home/pranav123/.gitconfig
-bash: cd: /home/pranav123/.gitconfig: Not a directory

pranav123@LAPTOP-N6Q5RB7O:/home$ vim /home/pranav123/.gitconfig

## LAB 12:
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git hist
* 9224df6 2023-05-03 | Added a comment (HEAD -> master) [Pranav]
* fb3e299 2023-05-03 | Added a default value [Pranav]
* b52db9b 2023-05-03 | "using argv" [Pranav]
* faad5f0 2023-05-03 | Unrelated change to c [Pranav]
* 841aa5a 2023-05-03 | Changes for a and b [Pranav]
* b4e0e34 2023-05-03 | First Commit [Pranav]

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git checkout faad5f0
Note: switching to 'faad5f0'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at faad5f0 Unrelated change to c
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ cat hello.rb
Hello, #{ARGV.first}!
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git checkout master
Previous HEAD position was faad5f0 Unrelated change to c
Switched to branch 'master'
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ cat hello.rb
#Default is "World"
name = ARGV.first || "World"

puts "Hello, #{name}!"

## LAB 13:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git tag v1
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git checkout v1^
Note: switching to 'v1^'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at fb3e299 Added a default value
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ cat hello.rb
name = ARGV.first || "World"

puts "Hello, #{name}!"
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git tag v1-beta
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git checkout v1
Previous HEAD position was fb3e299 Added a default value
HEAD is now at 9224df6 Added a comment
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git checkout v1-beta
Previous HEAD position was 9224df6 Added a comment
HEAD is now at fb3e299 Added a default value
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git tag
v1
v1-beta
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git hist master --all
* 9224df6 2023-05-03 | Added a comment (tag: v1, master) [Pranav]
* fb3e299 2023-05-03 | Added a default value (HEAD, tag: v1-beta) [Pranav]
* b52db9b 2023-05-03 | "using argv" [Pranav]
* faad5f0 2023-05-03 | Unrelated change to c [Pranav]
* 841aa5a 2023-05-03 | Changes for a and b [Pranav]
* b4e0e34 2023-05-03 | First Commit [Pranav]

## LAB-14:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git checkout master
Previous HEAD position was fb3e299 Added a default value
Switched to branch 'master'
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ vim hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   hello.rb

no changes added to commit (use "git add" and/or "git commit -a")
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git checkout hello.rb
Updated 1 path from the index
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git status
On branch master
nothing to commit, working tree clean
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ cat hello.rb
#Default is "World"
name = ARGV.first || "World"

puts "Hello, #{name}!"


## LAB 15:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ vim hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   hello.rb

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git reset HEAD hello.rb
Unstaged changes after reset:
M       hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git checkout hello.rb
Updated 1 path from the index
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git status
On branch master
nothing to commit, working tree clean

## Lab 16:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ vim hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git status

On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   hello.rb

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git reset HEAD hello.rb

Unstaged changes after reset:
M       hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git checkout hello.rb

Updated 1 path from the index
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git status

On branch master
nothing to commit, working tree clean

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ vim hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git commit -m "Oops, we didn't want this commit"

[master e56a4b6] Oops, we didn't want this commit
 1 file changed, 1 insertion(+), 1 deletion(-)

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git revert HEAD
[master 88b7ec8] Revert "Oops, we didn't want this commit"
 1 file changed, 1 insertion(+), 1 deletion(-)

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git hist
* 88b7ec8 2023-05-03 | Revert "Oops, we didn't want this commit" (HEAD -> master) [Pranav]
* e56a4b6 2023-05-03 | Oops, we didn't want this commit [Pranav]
* 9224df6 2023-05-03 | Added a comment (tag: v1) [Pranav]
* fb3e299 2023-05-03 | Added a default value (tag: v1-beta) [Pranav]
* b52db9b 2023-05-03 | "using argv" [Pranav]
* faad5f0 2023-05-03 | Unrelated change to c [Pranav]
* 841aa5a 2023-05-03 | Changes for a and b [Pranav]
* b4e0e34 2023-05-03 | First Commit [Pranav]

## LAB 17:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git hist
* 88b7ec8 2023-05-03 | Revert "Oops, we didn't want this commit" (HEAD -> master) [Pranav]
* e56a4b6 2023-05-03 | Oops, we didn't want this commit [Pranav]
* 9224df6 2023-05-03 | Added a comment (tag: v1) [Pranav]
* fb3e299 2023-05-03 | Added a default value (tag: v1-beta) [Pranav]
* b52db9b 2023-05-03 | "using argv" [Pranav]
* faad5f0 2023-05-03 | Unrelated change to c [Pranav]
* 841aa5a 2023-05-03 | Changes for a and b [Pranav]
* b4e0e34 2023-05-03 | First Commit [Pranav]
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git tag oops
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git reset --hard v1
HEAD is now at 9224df6 Added a comment
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git hist
* 9224df6 2023-05-03 | Added a comment (HEAD -> master, tag: v1) [Pranav]
* fb3e299 2023-05-03 | Added a default value (tag: v1-beta) [Pranav]
* b52db9b 2023-05-03 | "using argv" [Pranav]
* faad5f0 2023-05-03 | Unrelated change to c [Pranav]
* 841aa5a 2023-05-03 | Changes for a and b [Pranav]
* b4e0e34 2023-05-03 | First Commit [Pranav]
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git hist --all
* 88b7ec8 2023-05-03 | Revert "Oops, we didn't want this commit" (tag: oops) [Pranav]
* e56a4b6 2023-05-03 | Oops, we didn't want this commit [Pranav]
* 9224df6 2023-05-03 | Added a comment (HEAD -> master, tag: v1) [Pranav]
* fb3e299 2023-05-03 | Added a default value (tag: v1-beta) [Pranav]
* b52db9b 2023-05-03 | "using argv" [Pranav]
* faad5f0 2023-05-03 | Unrelated change to c [Pranav]
* 841aa5a 2023-05-03 | Changes for a and b [Pranav]
* b4e0e34 2023-05-03 | First Commit [Pranav]

## LAB 18:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git tag -d oops
Deleted tag 'oops' (was 88b7ec8)
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git hist --all
* 9224df6 2023-05-03 | Added a comment (HEAD -> master, tag: v1) [Pranav]
* fb3e299 2023-05-03 | Added a default value (tag: v1-beta) [Pranav]
* b52db9b 2023-05-03 | "using argv" [Pranav]
* faad5f0 2023-05-03 | Unrelated change to c [Pranav]
* 841aa5a 2023-05-03 | Changes for a and b [Pranav]
* b4e0e34 2023-05-03 | First Commit [Pranav]

## LAB 19:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ vim hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git commit -m "Add an author comment"
[master da9f36c] Add an author comment
 1 file changed, 2 insertions(+), 1 deletion(-)
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ vim hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git commit --amend -m "Add an author/email comment"
[master 1c44421] Add an author/email comment
 Date: Wed May 3 23:17:47 2023 +0530
 1 file changed, 2 insertions(+), 1 deletion(-)
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git hist
* 1c44421 2023-05-03 | Add an author/email comment (HEAD -> master) [Pranav]
* 9224df6 2023-05-03 | Added a comment (tag: v1) [Pranav]
* fb3e299 2023-05-03 | Added a default value (tag: v1-beta) [Pranav]
* b52db9b 2023-05-03 | "using argv" [Pranav]
* faad5f0 2023-05-03 | Unrelated change to c [Pranav]
* 841aa5a 2023-05-03 | Changes for a and b [Pranav]
* b4e0e34 2023-05-03 | First Commit [Pranav]

## LAB 20:
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ mkdir lib
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git mv hello.rb lib
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git status

On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        renamed:    hello.rb -> lib/hello.rb

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git commit -m "Moved hello.rb to lib"
[master dfb59b8] Moved hello.rb to lib
 1 file changed, 0 insertions(+), 0 deletions(-)
 rename hello.rb => lib/hello.rb (100%)


## LAB 21:
i was getting this error again and again related to ruby :

ERROR:  While executing gem ... (Gem::FilePermissionError)
    You don't have write permissions for the /var/lib/gems/2.7.0 directory.

## LAB 22:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ ls -C .git
COMMIT_EDITMSG       HEAD       branches  description  index  logs     refs
COMMIT_EDITMSG.save  ORIG_HEAD  config    hooks        info   objects

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ ls -C .git/objects
10  1c  2d  76  84  87  92  b4  c4  da  e4  e6  ee  f2  fb    pack
1b  2a  31  7e  85  88  9c  b5  c9  df  e5  ec  f1  fa  info

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ ls -C .git/objects
10  1c  2d  76  84  87  92  b4  c4  da  e4  e6  ee  f2  fb    pack
1b  2a  31  7e  85  88  9c  b5  c9  df  e5  ec  f1  fa  info

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ ls -C .git/objects/<dir>
-bash: syntax error near unexpected token `newline'

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ ls -C .git/objects/10
f1d2a507e31e9c8198710cb7bdfd3d528544b8

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ cat .git/config
[core]
        repositoryformatversion = 0
        filemode = false
        bare = false
        logallrefupdates = true
        ignorecase = true

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ ls .git/refs
heads  tags

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ ls .git/refs/heads
master

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ ls .git/refs/tags
v1  v1-beta

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ cat .git/refs/tags/v1
9224df65f08e364559b64eeda5c3182e7c72e657

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ cat .git/HEAD
ref: refs/heads/master

## LAB 23:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git hist --max-count=1
* dfb59b8 2023-05-03 | Moved hello.rb to lib (HEAD -> master) [Pranav]
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git cat-file -t dfb59b8
commit
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git cat-file -p dfb59b8
tree 2a75a7327c87decd726099bfc6af3371eda2276e
parent 1c44421a3effd5d350e47ebaf04968e1320be709
author Pranav <kanacool80@gmail.com> 1683136330 +0530
committer Pranav <kanacool80@gmail.com> 1683136330 +0530

Moved hello.rb to lib
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git cat-file -p 2a75a73
100644 blob e69de29bb2d1d6434b8b29ae775ad8c2e48c5391    a.rb
100644 blob e69de29bb2d1d6434b8b29ae775ad8c2e48c5391    b.rb
100644 blob e69de29bb2d1d6434b8b29ae775ad8c2e48c5391    c.rb
100644 blob e69de29bb2d1d6434b8b29ae775ad8c2e48c5391    d.rb
040000 tree e46f374f5b36c6f02fb3e9e922b79044f754d795    lib
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git cat-file -p e46f374
100644 blob c45f26b6fdc7db6ba779fc4c385d9d24fc12cf72    hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git cat-file -p c45f26b
# Default is World
# Author: Jim Weirich (jim@somewhere.com)
name = ARGV.first || "World"

puts "Hello, #{name}!"

## LAB 24:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ cd lib
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello/lib$ touch greeter.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello/lib$ vim greeter.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello/lib$ cd..
cd..: command not found
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello/lib$ cd ..
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add lib/greeter.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git commit -m "Added greeter class"
[greet 8125b8f] Added greeter class
 1 file changed, 8 insertions(+)
 create mode 100644 lib/greeter.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ cd lib
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello/lib$ vim hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello/lib$ git add lib/hello.rb
warning: could not open directory 'lib/lib/': No such file or directory
fatal: pathspec 'lib/hello.rb' did not match any files
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello/lib$ cd ..
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add lib/hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git commit -m "Hello uses Greeter"
[greet edb0a1e] Hello uses Greeter
 1 file changed, 4 insertions(+), 2 deletions(-)

## LAB 25:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git hist --all
* edb0a1e 2023-05-04 | Hello uses Greeter (HEAD -> greet) [Pranav]
* 8125b8f 2023-05-04 | Added greeter class [Pranav]
* a5aa405 2023-05-04 | Added greeter class [Pranav]
* dfb59b8 2023-05-03 | Moved hello.rb to lib (master) [Pranav]
* 1c44421 2023-05-03 | Add an author/email comment [Pranav]
* 9224df6 2023-05-03 | Added a comment (tag: v1) [Pranav]
* fb3e299 2023-05-03 | Added a default value (tag: v1-beta) [Pranav]
* b52db9b 2023-05-03 | "using argv" [Pranav]
* faad5f0 2023-05-03 | Unrelated change to c [Pranav]
* 841aa5a 2023-05-03 | Changes for a and b [Pranav]
* b4e0e34 2023-05-03 | First Commit [Pranav]
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git checkout master
Switched to branch 'master'
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ cat lib/hello.rb
# Default is World
# Author: Jim Weirich (jim@somewhere.com)
name = ARGV.first || "World"

puts "Hello, #{name}!"
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git checkout greet
Switched to branch 'greet'
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ cat lib/hello.rb
require 'greeter'

# Default is World
name = ARGV.first || "World"

greeter = Greeter.new(name)
puts greeter.greet

## LAB 26:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git checkout master
Switched to branch 'master'
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ touch Readme.md
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ vim Readme.md
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add README
fatal: pathspec 'README' did not match any files
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add Readme.md
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git commit -m "Added README"
[master ce91fe6] Added README
 1 file changed, 1 insertion(+)
 create mode 100644 Readme.md

## LAB 27:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git hist --all
* ce91fe6 2023-05-04 | Added README (HEAD -> master) [Pranav]
| * edb0a1e 2023-05-04 | Hello uses Greeter (greet) [Pranav]
| * 8125b8f 2023-05-04 | Added greeter class [Pranav]
| * a5aa405 2023-05-04 | Added greeter class [Pranav]
|/
* dfb59b8 2023-05-03 | Moved hello.rb to lib [Pranav]
* 1c44421 2023-05-03 | Add an author/email comment [Pranav]
* 9224df6 2023-05-03 | Added a comment (tag: v1) [Pranav]
* fb3e299 2023-05-03 | Added a default value (tag: v1-beta) [Pranav]
* b52db9b 2023-05-03 | "using argv" [Pranav]
* faad5f0 2023-05-03 | Unrelated change to c [Pranav]
* 841aa5a 2023-05-03 | Changes for a and b [Pranav]
* b4e0e34 2023-05-03 | First Commit [Pranav]

## LAB 28:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git checkout greet
Switched to branch 'greet'
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git merge master
Merge made by the 'recursive' strategy.
 Readme.md | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Readme.md
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git hist --all
*   99cf74b 2023-05-04 | Merge branch 'master' into greet (HEAD -> greet) [Pranav]
|\
| * ce91fe6 2023-05-04 | Added README (master) [Pranav]
* | edb0a1e 2023-05-04 | Hello uses Greeter [Pranav]
* | 8125b8f 2023-05-04 | Added greeter class [Pranav]
* | a5aa405 2023-05-04 | Added greeter class [Pranav]
|/
* dfb59b8 2023-05-03 | Moved hello.rb to lib [Pranav]
* 1c44421 2023-05-03 | Add an author/email comment [Pranav]
* 9224df6 2023-05-03 | Added a comment (tag: v1) [Pranav]
* fb3e299 2023-05-03 | Added a default value (tag: v1-beta) [Pranav]
* b52db9b 2023-05-03 | "using argv" [Pranav]
* faad5f0 2023-05-03 | Unrelated change to c [Pranav]
* 841aa5a 2023-05-03 | Changes for a and b [Pranav]
* b4e0e34 2023-05-03 | First Commit [Pranav]

## LAB 29:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git checkout master
Switched to branch 'master'
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ cd lib
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello/lib$ vim hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello/lib$ git add lib/hello.rb
warning: could not open directory 'lib/lib/': No such file or directory
fatal: pathspec 'lib/hello.rb' did not match any files
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello/lib$ cd ..
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add lib/hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git commit -m "Made interactive"
[master 21b882c] Made interactive
 1 file changed, 3 insertions(+), 4 deletions(-)
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git hist --all
* 21b882c 2023-05-04 | Made interactive (HEAD -> master) [Pranav]
| *   99cf74b 2023-05-04 | Merge branch 'master' into greet (greet) [Pranav]
| |\
| |/
|/|
* | ce91fe6 2023-05-04 | Added README [Pranav]
| * edb0a1e 2023-05-04 | Hello uses Greeter [Pranav]
| * 8125b8f 2023-05-04 | Added greeter class [Pranav]
| * a5aa405 2023-05-04 | Added greeter class [Pranav]
|/
* dfb59b8 2023-05-03 | Moved hello.rb to lib [Pranav]
* 1c44421 2023-05-03 | Add an author/email comment [Pranav]
* 9224df6 2023-05-03 | Added a comment (tag: v1) [Pranav]
* fb3e299 2023-05-03 | Added a default value (tag: v1-beta) [Pranav]
* b52db9b 2023-05-03 | "using argv" [Pranav]
* faad5f0 2023-05-03 | Unrelated change to c [Pranav]
* 841aa5a 2023-05-03 | Changes for a and b [Pranav]
* b4e0e34 2023-05-03 | First Commit [Pranav]

## LAB 30:

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git checkout greet
Switched to branch 'greet'
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git merge master
Auto-merging lib/hello.rb
CONFLICT (content): Merge conflict in lib/hello.rb
Automatic merge failed; fix conflicts and then commit the result.
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ lib

Command 'lib' not found, did you mean:

  command 'slib' from deb slib (3b1-5)
  command 'lie' from deb lie (2.2.2+dfsg-3build1)
  command 'lid' from deb id-utils (4.6+git20120811-4ubuntu2)
  command 'lix' from deb lix (0.9.29-1build2)
  command 'ldb' from deb rocksdb-tools (5.17.2-3)
  command 'lb' from deb live-build (3.0~a57-1ubuntu38.20.04.2)
  command 'lb' from deb open-infrastructure-system-build (20190301-lts1-2)

Try: sudo apt install <deb name>

pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ cd lib
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello/lib$ vim hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello/lib$ git add lib/hello.rb
warning: could not open directory 'lib/lib/': No such file or directory
fatal: pathspec 'lib/hello.rb' did not match any files
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello/lib$ cd ..
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git add lib/hello.rb
pranav123@LAPTOP-N6Q5RB7O:/mnt/d/New folder/hello$ git commit -m "Merged master fixed conflict."
[greet d6a3156] Merged master fixed conflict.
