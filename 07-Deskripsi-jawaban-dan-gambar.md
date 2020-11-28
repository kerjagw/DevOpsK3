# Deploy Project To Do App ke Heroku

### Pre-Requisites
1. Git
2. HEROKU-CLI
3. Node Package Manager

### Prosedur
1. Fork project yang akan di deploy
   ![fork](https://github.com/kerjagw/DevOpsK3/blob/main/Folder-images-jawaban/07-fork.png)
   - Clone
   ![clone](https://github.com/kerjagw/DevOpsK3/blob/main/Folder-images-jawaban/07-clone.png)
   - Git clone 
   ![git clone](https://github.com/kerjagw/DevOpsK3/blob/main/Folder-images-jawaban/07-gitclone.png)
2. Registrasi ke Heroku
   ![regis](https://github.com/kerjagw/DevOpsK3/blob/main/Folder-images-jawaban/07-loginheroku.png)
3. cd ke repository project yang akan di deploy/git bash here pada folder
   ![cd](https://github.com/kerjagw/DevOpsK3/blob/main/Folder-images-jawaban/07-cd.png)
4. innisialiasi git repo
   - heroku login
   ![heroku login](https://github.com/kerjagw/DevOpsK3/blob/main/Folder-images-jawaban/07-herokulogin.png)
   - heroku create gwit-deploy
   ![heroku create](https://github.com/kerjagw/DevOpsK3/blob/main/Folder-images-jawaban/07-herokuctda.png)
5. Kemudian deploy projek 
   - git add .
   - git commit -m “deploy project to do app”
   - git push heroku master
   ![heroku push](https://github.com/kerjagw/DevOpsK3/blob/main/Folder-images-jawaban/07-herokupush.png)
   
   *Meskipun hasil deploy error karena gagal konversi database posgreesql ke mysql yang menyebabkan server tidak dapat terhubung dengan database*
   ![](https://github.com/kerjagw/DevOpsK3/blob/main/Folder-images-jawaban/07-herokupushoutput.png)

6. Project dapat dibuka dengan perintah
   - heroku open
   ![heroku open](https://github.com/kerjagw/DevOpsK3/blob/main/Folder-images-jawaban/07-herokuopen.png) 