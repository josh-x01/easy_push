## Use easy_push to make the git process easier
Please follow the instruction carefully

```
git clone https://github.com/eyasuyid/easy_push.git
cd easy_push
chmod u+x easy_push
sudo cp easy_push /usr/local/bin/es
```
```es```
```
dev@developer:~$ es
Commit message: write your commit message here
[main a4119bc] Write your commit message here
 2 files changed, 26 insertions(+), 11 deletions(-)
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 660 bytes | 660.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/eyasuyid/easy_push.git
   c1abf62..a4119bc  main -> mai
```
Second option using args
```
dev@developer:~$ es "Write your commit message here"
[main a4119bc] Write your commit message here
 2 files changed, 26 insertions(+), 11 deletions(-)
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 660 bytes | 660.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/eyasuyid/easy_push.git
   c1abf62..a4119bc  main -> main
```

### Thanks for using easy_push
