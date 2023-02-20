# Python Wrangling

## Description

Python scripts are invoked kind of like programs in the Terminal... Can you run [this Python script](https://mercury.picoctf.net/static/b351a89e0bc6745b00716849105f87c6/ende.py) using [this password](https://mercury.picoctf.net/static/b351a89e0bc6745b00716849105f87c6/pw.txt) to get [the flag](https://mercury.picoctf.net/static/b351a89e0bc6745b00716849105f87c6/flag.txt.en) ?

## Write-up

### ENG

---

1. Starting with commands to download all the files
- `$ wget https://mercury.picoctf.net/static/b351a89e0bc6745b00716849105f87c6/ende.py`
- `$ wget https://mercury.picoctf.net/static/b351a89e0bc6745b00716849105f87c6/pw.txt`
- `$ wget https://mercury.picoctf.net/static/b351a89e0bc6745b00716849105f87c6/flag.txt.en`
1. After using command `$ python [ende.py](http://ende.py)` we get info of usage this script
2. Also we need to use password in file `pw.txt`, so we use `$ cat pw.txt` and copy the password
3. Next we use command `$ python [ende.py](http://ende.py) -d falg.txt.en` with our password and get the flag

### SVK

---

1. Začneme príkazmi na stiahnutie všetkých súborov
- `$ wget https://mercury.picoctf.net/static/b351a89e0bc6745b00716849105f87c6/ende.py`
- `$ wget https://mercury.picoctf.net/static/b351a89e0bc6745b00716849105f87c6/pw.txt`
- `$ wget https://mercury.picoctf.net/static/b351a89e0bc6745b00716849105f87c6/flag.txt.en`
1. Po použití `$ python [ende.py](http://ende.py)` dostaneme info o tom ako používať tento script
2. Taktiež potrebujeme heslo ktoré jednoducho získame zo súboru `pw.txt`, použitím `$ cat pw.txt` 
3. Ďalej použijeme príkaz `$ python [ende.py](http://ende.py) -d falg.txt.en` s našim heslom ako input a dostaneme flag