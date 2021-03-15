# ChallengeGit6
Challenge Git 6

Copie du "git log --oneline"

gregory@DevTech64:~$ cd Documents/

gregory@DevTech64:~/Documents$ mkdir My-Website-Oops
gregory@DevTech64:~/Documents$ cd My-Website-Oops/
gregory@DevTech64:~/Documents/My-Website-Oops$ touch index.html
gregory@DevTech64:~/Documents/My-Website-Oops$ code .
gregory@DevTech64:~/Documents/My-Website-Oops$ git add .
gregory@DevTech64:~/Documents/My-Website-Oops$ git commit -m "Creation du squelette"
[master 1275c66] Creation du squelette
 1 file changed, 12 insertions(+)
 create mode 100644 My-Website-Oops/index.html
 
gregory@DevTech64:~/Documents/My-Website-Oops$ git add .
gregory@DevTech64:~/Documents/My-Website-Oops$ git commit -m "Changement du titre"
[master e9ec1a0] Changement du titre
 1 file changed, 1 insertion(+), 1 deletion(-)
 
gregory@DevTech64:~/Documents/My-Website-Oops$ git add .
gregory@DevTech64:~/Documents/My-Website-Oops$ git commit -m "Ajout d'un paragraphe"
[master 4132d05] Ajout d'un paragraphe
 1 file changed, 1 insertion(+), 1 deletion(-)
 
gregory@DevTech64:~/Documents/My-Website-Oops$ git log --oneline
4132d05 (HEAD -> master) Ajout d'un paragraphe
e9ec1a0 Changement du titre
1275c66 Creation du squelette

gregory@DevTech64:~/Documents/My-Website-Oops$ git revert 4132d05
[master 41ea33a] Revert "Ajout d'un paragraphe"
 1 file changed, 1 insertion(+), 1 deletion(-)
 
gregory@DevTech64:~/Documents/My-Website-Oops$ git log --oneline
41ea33a (HEAD -> master) Revert "Ajout d'un paragraphe"
4132d05 Ajout d'un paragraphe
e9ec1a0 Changement du titre
1275c66 Creation du squelette

gregory@DevTech64:~/Documents/My-Website-Oops$
