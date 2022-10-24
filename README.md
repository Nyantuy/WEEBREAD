# WEEBREAD
Animanga, read and watch


# Installation
1. Already have python installed on your pc
2. run **pip install -r requirements.txt** in terminal
3. to run it, type **Python manage.py runserver** in terminal
4. enjoy.


# RESTful API

List Scraping
## Komikindo
### Status
```
api/komikindo/
```
### Home
```
api/komikindo/home
```
### Daftar Komik
```
api/komikindo/daftar-komik/page/<pagination:number>
```
### Komik Terbaru
```
api/komikindo/komik-terbaru/page/<pagination:number>
```
### Komik Type (Manga, Manhwa, Manhua)
```
type = [manga, manhwa, manhua]
api/komikindo/komikk/<type:string>/page/<pagination:number>
```
### Komik Detail
```
api/komikindo/komik/<endpoint:string>/
```
### Komik Chapter
```
api/komikindo/chapter/<endpoint:string>/
```
### Search Komik
```
api/komikindo/search/<query:string>/?page=<pagination:number>
```
## Otakudesu
### Status
```
/api/otakudesu/
```
### Home
```
api/otakudesu/home
```
### Search Anime
```
api/otakudesu/search/<query:string>
```
### Anime Detail
```
api/otakudesu/anime/<endpoint:string>
```
### Anime Episode
```
api/otakudesu/eps/<endpoint:string>
```
### Jadwal Rilis
```
api/otakudesu/jadwal-rilis
```
### Daftar Anime
```
api/otakudesu/daftar-anime
```
