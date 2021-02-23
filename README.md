# Instalooter

> InstaLooter adalah program yang dapat mengunduh gambar atau video apa pun yang terkait dari profil Instagram, tanpa akses API apa pun. Ini dapat dilihat sebagai implementasi ulang dari [InstaRaider](https://github.com/akurtovic/InstaRaider) yang sekarang tidak digunakan lagi yang dikembangkan oleh [@akurtovic](https://github.com/akurtovic)
## Installation
> [Baca dokumentasinya disini](https://instalooter.readthedocs.io/en/latest/) 

## Usage
Download Semua Foto dan Video yang ada di Instagram user
```commandline
instalooter user <username> [<directory>]
```
Download Foto dan Video dengan hashtag
```commandline
instalooter hashtag <hashtag> [<directory>]
```
Download dengan url
```commandline
instalooter post <post_token> [<directory>]
```
Gunakan file konfigurasi untuk mendownload dari beberapa akun menggunakan parameter kustom
```commandline
instalooter batch [<batch_file>]
```
## Example
```commandline
instalooter user fiqsky02 C:\Users\fiqih\IdeaProjects\insta-downloader\downloaded
instalooter hashtag python C:\Users\fiqih\IdeaProjects\insta-downloader\downloaded
instalooter post "https://www.instagram.com/p/CDyEZ2onm3W/" C:\Users\fiqih\IdeaProjects\insta-downloader\downloaded
instalooter batch /path/to/a/config/file.ini
```

Thanks
[@akurtovic](https://github.com/akurtovic), awesome library.