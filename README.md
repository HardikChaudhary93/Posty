# Posty
 
### Follow instruction to run this app:

Firstly, download and install Xampp server by clik on this link: [Xampp](https://downloadsapachefriends.global.ssl.fastly.net/7.3.31/xampp-windows-x64-7.3.31-2-VC15-installer.exe?from_af=true)

After installing Xampp server, you will see Xampp folder in C drive. Open that folder and look for Htdocs folder and open that folder.

Download laravelAPI code zip file from this link: [Posty](https://codeload.github.com/HardikChaudhary93/Posty/zip/refs/heads/main)

Extract this zip file in htdocs folder.

Open Xampp server application by run as administrator and press start button of Apache and Mysql.

Now click this link: [Phpmyadmin](http://localhost/phpmyadmin/index.php)

Click on Database and right down database name as **posty** and press create button.

Open cmd and implement below commands step by step:
```bash
cd c:/xampp/htdocs/posty
```
```bash
php artisan migrate
```
now click on this link and see magic [Posty](http://localhost/Posty/public/)
