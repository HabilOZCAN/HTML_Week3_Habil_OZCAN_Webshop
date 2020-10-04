1. öncelikle dosyamın webshop dosyasının içine girerek
> git init
komutunu çalıştırdım.
2.git add --all ve git commit -m 'xxxxx' komutlarını çalıştırdım.
3.github sitesinden local makinedeki aynı isimde bir repository oluşturdum.
4. git remote add origin https://github.com/HabilOZCAN/HTML_Week3_Habil_OZCAN_Webshop.git komutunu çalıştırdım
fatal: remote origin already exists, hatasını verdi.
5. git branch -M main komutunu ve git push -u origin main komutunu çalıştırdım.
/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 1.83 KiB | 1.83 MiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/HabilOZCAN/HTML_Week3_Habil_OZCAN_Webshop.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/*/
output'unu verdi ve github repository'de halihazırdaki 3 html file'ı gorebildim.
6. sonrasında styles.css dosyasını oluşturdum, commit yaptım ve git push komutunu kullarak bunları githup repository'e ekledim
7. styles.css dosyasını içeriğini yazdım ve html sayfalarına link ekleyerek tekrar git add . komutu ve git commit -m 'xxxx' komutu ile 
yeni değişiklikleri local git repository'de etkinleştirdim sonrasında push komutu ile github repository'e push ettim.
8. touch .gitignore komutu ile .gitignore dosyasını oluşturdum.
9. Readme.md file oluşturuldu.
