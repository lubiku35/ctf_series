# Wave a flag

## Description

Can you invoke help flags for a tool or binary? [This program](https://mercury.picoctf.net/static/cfea736820f329083dab9558c3932ada/warm) has extraordinarily helpful information...

## Write-up

### ENG

---

1. First of all we need to download the file using command `$ wget https://mercury.picoctf.net/static/cfea736820f329083dab9558c3932ada/warm`
2. What we know is that, this program is in binary and is possible to execute the program so we firstly use command `$ chmod +x warm` to change mods of file to be actually executable 
3. Next we use command `$ ./warm` to run the program, program says that we have to pass the operator “-h” to see what he can do  
4. And there is the flag

### SVK

---

1. Najskôr potrebujeme stiahnuť súbor príkazom `$ wget https://mercury.picoctf.net/static/cfea736820f329083dab9558c3932ada/warm`
2. Vieme že program je v “binárke” takže v podstate vieme tento súbor spustiť, na to potrebujeme `$ chmod +x warm` pre zmenu módu na executable 
3. ďalej použijeme `$ ./warm` na sputstenie programu, ktorý nám po spustení napovedá že máme použiť operátor “-h” pre detailnejšie zobrazenie čo program robí  
4. Tam nájdeme flag