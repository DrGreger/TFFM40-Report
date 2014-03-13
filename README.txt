Standard git kommandon

***Lägga till filer du skrivit i eller skapat***
!!!gör alltid en ”git pull” först!!!
git add <din_fil>
git commit -m”Skriv_vad_du_pushar”
git push origin master 			//man behöver inte alltid origin master..

***hämta filer från vårt repo***
git pull origin master

***kolla vilka filer du har ändrat***
git status

***slipp skriva ”origin master”***
git branch --set-upstream-to=origin/<branch> master
