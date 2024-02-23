linjinsheng@linjinshengdeMacBook-Pro project-one % git add .
linjinsheng@linjinshengdeMacBook-Pro project-one % git commit -m "first commit"
[master (root-commit) 2613628] first commit
 1 file changed, 2 insertions(+)
 create mode 100644 runoob.txt
linjinsheng@linjinshengdeMacBook-Pro project-one % git branch -M master
linjinsheng@linjinshengdeMacBook-Pro project-one % git remote add origin https://github.com/linjinsheng/project-one.git
fatal: remote origin already exists.
linjinsheng@linjinshengdeMacBook-Pro project-one % git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 240 bytes | 240.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/linjinsheng/project-one.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
linjinsheng@linjinshengdeMacBook-Pro project-one %
