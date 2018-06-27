# helloworld
Markus Repository
# Rayban1131
$ git config --global user.name "myusername"
# Mailadresse angeben
$ git config --global user.email "mymail"
# Repository myfolder anlegen
$ git init myfolder
# in den Ordner wechseln
$ cd myfolder
# Datei erzeugen
$ touch myfile
# Füge Datei der Versionierung hinzu
$ git add myfile
# Committe die Änderungen in das lokale Repository
$ git commit -m "initial commit"
# Mache das GitHub Repository als origin bekannt
$ git remote add origin https://github.com/myuser/myrepository.git
# Schiebe lokales auf entferntes Repository
$ git push origin master
