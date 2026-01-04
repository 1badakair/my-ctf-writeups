# Level 0
Bandit Level 0 - Level 1

## Instruksi
The password for the next level is stored in a file called **readme** located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

## Solusi
1. Mencari file apa saja yang ada menggunaka command `ls`. Ditemukan file bernama **readme**.
```
bandit0@bandit:~$ ls
readme
```
2. Mencari tahu jenis file readme menggunakan command `file`. Dikteahui file **readme** merupakan file **ASCII text**
```
bandit0@bandit:~$ file readme
readme: ASCII text
```
3. Menampilkan isi file **readme** karena filenya **ASCII text**
```
bandit0@bandit:~$ cat readme
The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```

## Password untuk ke Level 1 adalah:
```
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```