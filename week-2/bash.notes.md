Task 0 - 1 (commands: ssh -p, ls, cd, cat) 
*ssh -p = koristimo za konekciju na server*
*ls = izlistavamo sve vidljive fajlove/foldere u trenutnom direktoriju*
*cd = ulazimo u zeljeni fajl ili folder*
*cat = koristimo za ispis sadrzaja*
![Alt text](Task%20Level%200%20to%201%20%20-%20Bandit.png)


Task 1 - 2 (commands: ssh -p, cd ~, ls -la, cat ./)
*cd ~ = koristimo za pozicioniranje u home direktorij*
*ls -la = koristimo za izlistavanje svih vidljivih fajlova/foldera ali i skrivenih*
*cat ./-* = koristimo za ispis sadrzaja fajla koji sadrzi -(dash)*
![Alt text](Task%20Level%201%20to%202%20-%20Bandit.png)


Task 2 - 3 (commands: cd ~, ls -la, cat"")
*cat "" - koristimo kako bi izbjegli praznine(spaces) izmedju rijeci zadanog fajla i ocitali njegov sadrzaj*
![Alt text](Task%20Level%202%20to%203%20%20-%20Bandit.png)


Task 3 - 4 (commands: ls, cd, cat ./)
*Navedene komande za ovaj zadatak smo vec koristili u prethodnim zadacima*
![Alt text](Task%20Level%203%20to%204%20-%20Bandit.png)


Task 4 - 5 (commands: ls, file ./folder_name/*, cat ./ )
*file ./folder_name/* - Ova komanda nam omogućava da prikazemo tipove fajla unutar zeljenog direktorija.
![Alt text](Task%20Level%204%20to%205%20-%20Bandit.png)


Task 5 - 6 (commands:ls, ls -la, cd, cat ./, find)
*find - koristimo find . -type f -size kako bismo locirali trazeni fajl po njegovoj velicini u trenutnom direktoriju*
![Alt text](Task%20Level%205%20to%206%20-%20Bandit.png)


Task 6 - 7 (commands: find, cat)
*find - koristimo opciju find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null pomoću koje trazimo zeljeni fajl po zadanim kriterijumima(user, grupa, velicina fajla). 2>dev/null smo koristili kako bi izfiltrirali error messages i da prikazemo samo ono sto nas zanima*
![Alt text](Task%20Level%206%20to%207%20-%20Bandit.png)


Task 7 - 8 (commands: grep, cut)
*grep - koristimo komandu grep "millionth" data.txt | cut -f 2 kako bismo nasli fajl sa trazenom kljucnom rijeci "milionth" a onda koristimo komandu cut kako bi odvojili password kao zasebnu jedinicu*
![Alt text](Task%20Level%207%20to%208%20-%20Bandit.png)


Task 8 - 9 (commands: ls, sort, uniq, cut )
*sort - koristimo opciju sort kako bi sortirali sadrzaj zadanog fajla*
*uniq -u - koristimo ovu komandu kako bi ispisali onu liniju tekst koja se prikazuje samo jednom*
![Alt text](Task%20Level%208%20to%209%20-%20Bandit.png)


Task 9 - 10 (commands: ls, strings, grep)
*strings - koristimo za izvlacenje podataka koji su nam razumljivi iz binarnog fajla*
*grep - koristimo grep u ovoj situaciji kako bismo isfiltrirali samo one dijelove fajla koji su sadrzali zadani znak"
![Alt text](Task%20Level%209%20to%2010%20-%20Bandit.png)


Task 10 - 11 (commands: ls, cat, base64)
*base64 - koristimo ovu komandu kako bi dekodirali sadrzaj data.txt fajla koji se nalazi u binarnom formatu*
![Alt text](Task%20Level%2010%20to%2011%20-%20Bandit.png)