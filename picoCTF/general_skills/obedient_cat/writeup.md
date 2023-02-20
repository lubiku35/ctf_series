# Obedient Cat

## Description

This file has a flag in plain sight (aka "in-the-clear"). [Download flag](https://mercury.picoctf.net/static/33996e32dce022205a6a36f69aba56f0/flag).

## Write-up

### ENG

---

1. Starting with command `$ wget https://mercury.picoctf.net/static/33996e32dce022205a6a36f69aba56f0/flag` to download the corresponding file
2. By command `$ file flag` we get info that file is in ASCII text, so we can just use command `$ cat flag` to read the file
3. After using `$ cat flag` we get actually the flag

### SVK

---

1. Začneme s príkazom `$ wget https://mercury.picoctf.net/static/33996e32dce022205a6a36f69aba56f0/flag` pre stiahnutie korešpondenčného súboru
2. Pomocou `$ file flag` získame informáciu o tom, že súbor je v ASCII texte, takže môžeme ďalej pokračovať s príkazom `$ cat flag` pre prečítanie súboru
3. Po použití `$ cat flag` dostaneme flag