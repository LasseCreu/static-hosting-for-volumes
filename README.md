# Static Hosting from Railway Volumes

Hey, mit diesem Template könnt ihr eine beliebig große Seite statisch in Railway hosten.

## 💁‍♀️ How to use
Hierfür ein Volume anlegen, und es mit diesem einfachen Filebrowser befüllen:
https://github.com/brody192/filebrowser-template/pkgs/container/filebrowser-template (Den gibt es in Railway auch als fertiges Template - Einfach nach "filebrowser" suchen...)

Über den Filebrowser zieht ihr dann eure Daten in das Volume.
Wichtig: Es muss eine index.hmtl vorhanden sein.

Dann das Volume in dieses Projekt mit dem Pfad "/data" mounten.
In den Settings unter Port 443 öffentlich zugänglich machen.

Zack fertich - Statische große webseite!!

Bei Fragen gerne auf mich zukommen :)
LC
