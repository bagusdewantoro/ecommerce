github branch = server

## GIT : Create difference branches for each folder di powershell
```
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop> cd admin
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\admin> git init
Initialized empty Git repository in C:/Users/octavianus.bagus/Documents/JavaScript2/shop/admin/.git/
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\admin> git add .
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\admin> git commit -am 'first'
[master (root-commit) b2d3e8a] first
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\admin> git branch -M admin
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\admin> git remote add origin https://github.com/bagusdewantoro/ecommerce.git
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\admin> git push origin admin
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 229 bytes | 229.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/bagusdewantoro/ecommerce.git
 * [new branch]      admin -> admin


PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\admin> cd ../client
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\client> git init
Initialized empty Git repository in C:/Users/octavianus.bagus/Documents/JavaScript2/shop/client/.git/
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\client> git checkout -b client
Switched to a new branch 'client'
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\client> git remote add origin https://github.com/bagusdewantoro/ecommerce.git
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\client> git add .
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\client> git commit -am 'first'
[client (root-commit) 467e366] first
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\client> git push origin client
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 233 bytes | 233.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'client' on GitHub by visiting:
remote:      https://github.com/bagusdewantoro/ecommerce/pull/new/client
remote:
To https://github.com/bagusdewantoro/ecommerce.git
 * [new branch]      client -> client


PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\client> cd ../server
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\server> git init
Initialized empty Git repository in C:/Users/octavianus.bagus/Documents/JavaScript2/shop/server/.git/
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\server> git add .
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\server> git commit -am 'first'
[master (root-commit) f77c30b] first
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\server> git checkout -b server
Switched to a new branch 'server'
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\server> git remote add origin https://ceritanya_salah_link
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\server> git remote add origin https://github.com/bagusdewantoro/ecommerce.git
fatal: remote origin already exists.
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\server> git remote remove origin
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\server> git remote add origin https://github.com/bagusdewantoro/ecommerce.git
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\server> git push origin server
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 232 bytes | 232.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'server' on GitHub by visiting:
remote:      https://github.com/bagusdewantoro/ecommerce/pull/new/server
remote:
To https://github.com/bagusdewantoro/ecommerce.git
 * [new branch]      server -> server
PS C:\Users\octavianus.bagus\Documents\JavaScript2\Shop\server>
```
