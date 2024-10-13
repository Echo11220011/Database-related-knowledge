11598@Echo MINGW64 /
$ git config --global user.name 'Echo11220011'

11598@Echo MINGW64 /
$ git config --global user.email '1159832349@qq.com'

11598@Echo MINGW64 /
$ git clone 'https://github.com/Echo11220011/vscode.git'
Cloning into 'vscode'...
warning: You appear to have cloned an empty repository.

11598@Echo MINGW64 /
$ git add
fatal: not a git repository (or any of the parent directories): .git

11598@Echo MINGW64 /
$ cd vscode/

11598@Echo MINGW64 /vscode (main)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config advice.addEmptyPathspec false"

11598@Echo MINGW64 /vscode (main)
$ git add index.js

11598@Echo MINGW64 /vscode (main)
$ git commit -m 'add index.js'
[main (root-commit) 2643f7f] add index.js
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.js

11598@Echo MINGW64 /vscode (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 212 bytes | 212.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Echo11220011/vscode.git
 * [new branch]      main -> main

11598@Echo MINGW64 /vscode (main)
$ git pull
Already up to date.

11598@Echo MINGW64 /vscode (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 940 bytes | 67.00 KiB/s, done.
From https://github.com/Echo11220011/vscode
   2643f7f..65fa620  main       -> origin/main
Updating 2643f7f..65fa620
Fast-forward
 index.js | 1 +
 1 file changed, 1 insertion(+)

11598@Echo MINGW64 /vscode (main)
$ git checkout index.js
Updated 1 path from the index

11598@Echo MINGW64 /vscode (main)
$ ^C

11598@Echo MINGW64 /vscode (main)
$
