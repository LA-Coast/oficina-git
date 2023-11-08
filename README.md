# oficina-git
primeiros passos com git hub

# Oficina "Primeiro pasos com git e github
## Jornada interdiciplinar - 8 de novembro de 2023
### Aluno
- Leticia
- ADS
- 1° semestre


aluno@L040017368 MINGW64 ~/Desktop
$ git clone https://github.com/LA-Coast/oficina-git.git
git: 'clone' is not a git command. See 'git --help'.

aluno@L040017368 MINGW64 ~/Desktop
$ git clone https://github.com/LA-Coast/oficina-git.git
Cloning into 'oficina-git'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

aluno@L040017368 MINGW64 ~/Desktop
$ ls
desktop.ini  oficina-git/

aluno@L040017368 MINGW64 ~/Desktop
$ cd oficina-git/

aluno@L040017368 MINGW64 ~/Desktop/oficina-git (main)
$ ls
README.md

aluno@L040017368 MINGW64 ~/Desktop/oficina-git (main)
$ git config user.name "leticia"

aluno@L040017368 MINGW64 ~/Desktop/oficina-git (main)
$ git config user.email "leticia99.costa@gmail.com"

aluno@L040017368 MINGW64 ~/Desktop/oficina-git (main)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/LA-Coast/oficina-git.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.main.remote=origin
branch.main.merge=refs/heads/main
user.name=leticia
user.email=leticia99.costa@gmail.com

aluno@L040017368 MINGW64 ~/Desktop/oficina-git (main)
$ git diff
diff --git a/README.md b/README.md
index d60f958..6556650 100644
--- a/README.md
+++ b/README.md
@@ -1,2 +1,9 @@
 # oficina-git
 primeiros passos com git hub
+
+# Oficina "Primeiro pasos com git e github
+## Jornada interdiciplinar - 8 de novembro de 2023
+### Aluno
+- Leticia
+- ADS
+- 1° semestre
\ No newline at end of file

aluno@L040017368 MINGW64 ~/Desktop/oficina-git (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

aluno@L040017368 MINGW64 ~/Desktop/oficina-git (main)
$ git add .

aluno@L040017368 MINGW64 ~/Desktop/oficina-git (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


aluno@L040017368 MINGW64 ~/Desktop/oficina-git (main)
$ git commit -m "Atauliza conteudo do README"
[main 222d69a] Atauliza conteudo do README
 1 file changed, 7 insertions(+)

aluno@L040017368 MINGW64 ~/Desktop/oficina-git (main)
$ giEnumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 392 bytes | 392.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/LA-Coast/oficina-git.git
   20e4d7e..222d69a  main -> main

