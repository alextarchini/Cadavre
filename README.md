
alexa@DESKTOP-9V8DV4M MINGW64 ~ (master)
$ cd desktop

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop (master)
$ git clone https://github.com/alextarchini/Cadavre.git
Cloning into 'Cadavre'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop (master)
$ git branch development
fatal: Not a valid object name: 'master'.

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop (master)
$ ls
'BeCode NOTES.lnk'*   Cadavre/     'GitHub Desktop.lnk'*   ProPlus2019Retail.img
 becode_projects/     desktop.ini  'Microsoft Edge.lnk'*

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop (master)
$ cd Cadavre

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop/Cadavre (master)
$ git branch development

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop/Cadavre (master)
$ git checkout development
Switched to branch 'development'
M       README.md

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop/Cadavre (development)
$ git add .

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop/Cadavre (development)
$ git commit -m "Initial commit"
[development 9c86264] Initial commit
 1 file changed, 6 insertions(+), 1 deletion(-)

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop/Cadavre (development)
$ git push
fatal: The current branch development has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin development


alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop/Cadavre (development)
$ git push origin development
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 273 bytes | 273.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
remote:
remote: Create a pull request for 'development' on GitHub by visiting:
remote:      https://github.com/alextarchini/Cadavre/pull/new/development
remote:
To https://github.com/alextarchini/Cadavre.git
 * [new branch]      development -> development

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop/Cadavre (development)
$ ^C

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop/Cadavre (development)
$ cd..
bash: cd..: command not found

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop/Cadavre (development)
$ cd ..

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop (master)
$ git clone https://github.com/IsabelAguera/Exercice-Cadavre-Exquis-Isabel.git
Cloning into 'Exercice-Cadavre-Exquis-Isabel'...
remote: Enumerating objects: 18, done.
remote: Counting objects: 100% (18/18), done.
remote: Compressing objects: 100% (9/9), done.
remote: Total 18 (delta 3), reused 9 (delta 2), pack-reused 0
Unpacking objects: 100% (18/18), done.

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop (master)
$ ls
'BeCode NOTES.lnk'*   Cadavre/      Exercice-Cadavre-Exquis-Isabel/  'Microsoft Edge.lnk'*
 becode_projects/     desktop.ini  'GitHub Desktop.lnk'*              ProPlus2019Retail.img

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop (master)
$ cd Exercice-Cadavre-Exquis-Isabel/

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop/Exercice-Cadavre-Exquis-Isabel (master)
$ ls
README.md

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop/Exercice-Cadavre-Exquis-Isabel (master)
$ README.md
bash: README.md: command not found

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop/Exercice-Cadavre-Exquis-Isabel (master)
$ git add .

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop/Exercice-Cadavre-Exquis-Isabel (master)
$ git commit -m "AlexT"
[master b0f1e98] AlexT
 1 file changed, 2 insertions(+)

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop/Exercice-Cadavre-Exquis-Isabel (master)
$ git push origin
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 280 bytes | 280.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/IsabelAguera/Exercice-Cadavre-Exquis-Isabel.git
   be71036..b0f1e98  master -> master

alexa@DESKTOP-9V8DV4M MINGW64 ~/desktop/Exercice-Cadavre-Exquis-Isabel (master)
