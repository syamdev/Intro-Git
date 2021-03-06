# Git - Cara Penggunaan Git

## Menggunakan GIT dengan Command Line
- Buat SSH keys
- Upload ke Github
- Buat repository
- Copy alamat SSH
- Clone dengan perintah git clone <alamat ssh>
- Ubah file
- Tambahkan ke daftar file yang diubah dengan git add
- Simpan perubahan dengan git commit
- Kirim perubahan ke github dengan git push

## Membuka GIT dengan PyCharm
- Pastikan menggunakan PyCharm terupdate
- Membuka project yang sudah di-clone di command line
- Merubah file
- Mengirim file ke Github
- Merubah di Github
- Mem-pull dari lokal

## Menggunakan GIT di Team
- Mulai bekerja dengan melihat ke Issue Tracker
- Bekerja tidak pada master, tapi pada branch tersendiri
- Mem-push branch baru tersebut (Mem-push jika sudah ada commit)
- Merubah kode pada branch tersebut
- Meng-commit kode dan me-review perubahan pada file terlebih dahulu
- Mem-push branch tsb

## Flow GIT di Team
- git checkout -b new-branch
- pull master
- git add file
- git commit
- push branch to remote
- git checkout master
- git merge new-branch
- push origin master

## Instalasi Git
- Menggunakan Linux, cukup dengan apt install git
- Menggunakan Windows, dengan mendownload tool Git di 
https://git-scm.com/downloads

## List Commands
- Copy url git ssh
```$ git clone url_git_ssh```

- Di folder project:
```
	$ git remote show origin
	$ git status
	$ git add .
	$ git commit -am "Commit message"
	$ git status
	$ git push origin master
```

- Ganti remote url:
``` $ git remote set-url origin git@github.com:syamdev/scrapy-flask.git```

## Git Workflow Alternative
- Create project folder on Local
- Create repo on Github
- Copy SSH git URL
- On Local project folder:
```
	$ git init
	$ git remote show origin
	$ git remote add origin git@github.com:syamdev/your-project.git
	$ git pull origin master
```

## Kesimpulan
- Dengan Git dan Github, kode akan aman dari harddisk rusak
- Memiliki repository Github yang public, akan menjadikan repository tersebut sebagai
portofolio
