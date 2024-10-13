11598@Echo MINGW64 /vscode/MarkdownFile (master)
$ git init
Reinitialized existing Git repository in D:/softwear/Git/vscode/MarkdownFile/.git/

11598@Echo MINGW64 /vscode/MarkdownFile (master)
$ git add .
warning: adding embedded git repository: Database-related-knowledge
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint:   git submodule add <url> Database-related-knowledge
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:
hint:   git rm --cached Database-related-knowledge
hint:
hint: See "git help submodule" for more information.
hint: Disable this message with "git config advice.addEmbeddedRepo false"

11598@Echo MINGW64 /vscode/MarkdownFile (master)
$ git commit -m "first"
[master 672055d] first
 1 file changed, 1 insertion(+)
 create mode 160000 Database-related-knowledge

11598@Echo MINGW64 /vscode/MarkdownFile (master)
$ git remote add origin https://github.com/Echo11220011/Database-related-knowledge.git
error: remote origin already exists.

11598@Echo MINGW64 /vscode/MarkdownFile (main)
$ git branch -M master

11598@Echo MINGW64 /vscode/MarkdownFile (master)
$ git push -u origin master
Enumerating objects: 20, done.
Counting objects: 100% (20/20), done.
Delta compression using up to 12 threads
Compressing objects: 100% (20/20), done.
Writing objects: 100% (20/20), 4.69 MiB | 1.20 MiB/s, done.
Total 20 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/Echo11220011/Database-related-knowledge/pull/new/master
remote:
To https://github.com/Echo11220011/Database-related-knowledge.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
