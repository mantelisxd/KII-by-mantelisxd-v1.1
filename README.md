# KII-by-mantelisxd-v1.1
------------------------ KII v1.1 by mantelisxd ------------------------

				README


Čia bus pateikta visa reikalinga informacija apie Kompiuterio Išjungimo Įrankį arba KII.

------------------------ NAUDOJIMAS ------------------------

1. Spausk ant paleidiklis.bat
2. Atsiras UAC langas - spausk Yes/Taip
3. Ekrane pasirodys mažas langas, kuriame viršuj pasirinksi veiksmą, žemiau laiką.
4. JEI LAIKĄ RAŠAI HH:MM tau veiksmas bus įvykdytas pagal laikrodį 
pvz.: įrašai 01:00 tai reikš, jog veiksmas bus įvykdytas 1 valandą nakties, o ne po vienos valandos.
Visais kitais atvejais laikas skaičiuosis nuo tada kiek parašyta 
pvz.: 01:00:00 arba 3600 - veiksmas bus atliktas po valandos (galioja HH:MM:SS ir sek formatams).
5. Atėjus laikui programa užsidarys ir kompiuteris padarys tai, ką buvai pasirinkęs. 

------------------------ V 1.1 UPDATES ------------------------

Pakeistas programos pavadinimas iš Kompiuterio Išjungimo Įrankis į KII.
		
Pridėta Laikino failo funkcija readmeKII.txt (readme.txt) failui. Susikuria kai yra paleidžiamas skriptas,
išsitrina kai skriptas išsijungia/uždaromas.

Pridėtas Info mygtukas pamatyti readmeKII.txt (kas yra tas pats kaip readme.txt).

Pataisyta Pasirinkite veiksmą sekcija - nuo šiol Išjungti (Shut Down) yra default pasirinkimas.

Pridėta shortcut funkcija - pirmą kartą paleidus skriptą desktop'e atsiras nuoroda su custom ikona, pavadinimu "KII by mantelisxd"
Norint, kad nuoroda veiktų sklandžiai, patartina pradžioje įsikelti skriptą į ten kur nori ir tik tada jį paleisti,
kad būtų sukurta veikianti nuoroda! (Nuoroda susikuria nuo to momento kai esant UAC langui paspaudi Taip/Yes)

------------------------ ŽINOMI BUG'AI ------------------------

Pervadinus nuorodą, skriptas sukuria naują nuorodą "KII by mantelisxd".

------------------------ APIE APLANKALE/.ZIP ESANČIUS FAILUS ------------------------

			 JOKIU BŪDU NEPERVADINKITE FAILŲ !!!


Šiame aplankale/.zip yra 5 failai:

1. paleidiklis.bat
2. run.vbs
3. KII_by_mantelisxd.ps1
4. readme.txt (nematomas)
5. KII.ico


	paleidiklis.bat

* Šis failas reikalingas tam, kad butų paleistas run.vbs! 
* Jam atidaryti Admin teisių nereikia.
* Gali būti matomas cmd trumpas mirktelėjimas. Taip yra dėl to, nes jis 
padarytas tik tam, kad atidarytų run.vbs. Atidaręs jis neturi ką daugiau daryti
ir išsijungia.
* Paslepia readme.txt failą.

	run.vbs

* Šis failas reikalingas tam, kad butų paleistas KII_by_mantelisxd.ps1(PowerShell).
* Šį failą atidaro paleidiklis.bat.
* Šiame faile yra kodo dalis, kuri neleidžia atsirasti įprastiniam PowerShell langui, padarydamas jį nematomu.



	
	KII_by_mantelisxd.ps1

* Šis failas yra pagrindinis PowerShell skriptas. Tai jis atlieka visą darbą.
* KII yra Kompiuterio Išjungimo Įrankis trumpinys. 

	
	readme.txt (nematomas)

* Šis failas yra tas kurį tu dabar skaitai.
* Prieš 1.1 versiją jis buvo matomas kaip atskiras failas.
* Nuo 1.1 versijos šį failą lengvai gali pasiekti paspaudęs Info mygtuką pačiame KII! 
* Tiesa, tai bus šio readme.txt kopija pavadinimu: readmeKII.txt.

	KII.ico
* Tai yra custom ikonėlė desktop'o nuorodai į skriptą.
* Norint pasikeisti ikonėlę galima pasidaryti/atsisiųsti 512px .ico failą jį persivadinti į KII.ico ir įkelti į skripto folderį (seną ištrinti).


- Paskutinis update: 2026-01-05 18:33

	©mantelisxd 2026
