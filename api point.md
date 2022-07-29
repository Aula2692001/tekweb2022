<!--  Tabel Users -->

GET: /users

data:
[
{
"id": "2",
"name": "aufa wlndri",
"motto": "pantang menyerah",
"ig_url": "https://www.instagram.com/al.zhra_/?hl=id",
"gh_url": "https://github.com/Aufa2692001/tekweb2022",
"yt_url": "https://www.youtube.com/channel/UChKGaehqhuUnS5fagoj4OoQ"
}
]


GET: /users/[2]

data:{
"id": "2",
"name": "aufa wlndri",
"motto": "pantang menyerah",
"ig_url": "https://www.instagram.com/al.zhra_/?hl=id",
"gh_url": "https://github.com/Aufa2692001/tekweb2022",
"yt_url": "https://www.youtube.com/channel/UChKGaehqhuUnS5fagoj4OoQ"
}


POST: /users

data:{
  "name":"aufa wlndri",
  "motto":"Semangat",
  "ig_url":"https://instagram.com/aufa.wlndri_",
  "gh_url":"https://github.com/Aufa2692001/tekweb2022",
  "yt_url":"https://www.youtube.com/channel/UChKGaehqhuUnS5fagoj4OoQ",
  
}

PUT: /users/[2]

data:{
  "name":"aufa wlndri",
  "motto":"Semangat, besok bakal lebih berat",
  "ig_url":"https://instagram.com/aufa.wlndri_",
  "gh_url":"https://github.com/Aufa2692001/tekweb2022",
  "yt_url":"https://www.youtube.com/channel/UChKGaehqhuUnS5fagoj4OoQ",
  
}

<!--  Tabel Article -->

GET: /article

data:[
{
"id": "2",
"gambar": "https://raw.githubusercontent.com/umarfaishal/tekweb2022/master/img/diri.jpg",
"title": "Sains itu menyenangkan",
"deskripsi": ""
},
{
"id": "3",
"gambar": "https://raw.githubusercontent.com/umarfaishal/tekweb2022/master/img/diri.jpg",
"title": "Marvel",
"deskripsi": "Oleh : Anhar S"
},
{
"id": "4",
"gambar": "https://raw.githubusercontent.com/umarfaishal/tekweb2022/master/img/diri.jpg",
"title": "Marvel",
"deskripsi": "Oleh : Anhar S"
},
{
"id": "5",
"gambar": "https://raw.githubusercontent.com/umarfaishal/tekweb2022/master/img/diri.jpg",
"title": "Marvel",
"deskripsi": "Oleh : Anhar S"
},
{
"id": "6",
"gambar": "https://raw.githubusercontent.com/umarfaishal/tekweb2022/master/img/diri.jpg",
"title": "Marvel",
"deskripsi": "Oleh : Anhar S"
}
]


GET: /article/[2]

data:{
"id": "2",
"gambar": "https://raw.githubusercontent.com/umarfaishal/tekweb2022/master/img/diri.jpg",
"title": "Sains itu menyenangkan",
"deskripsi": ""
}


POST: /article

data:{
  "name":"aufa wlndri",
  "motto":"Semangat",
  "ig_url":"https://instagram.com/aufa.wlndri_",
  "gh_url":"https://github.com/Aufa2692001/tekweb2022",
  "yt_url":"https://www.youtube.com/channel/UChKGaehqhuUnS5fagoj4OoQ",
  
}


PUT: /article/[3]

data:{
  "name":"aufa wlndri",
  "motto":"Semangat, besok bakal lebih berat",
  "ig_url":"https://instagram.com/aufa.wlndri_",
  "gh_url":"https://github.com/Aufa2692001/tekweb2022",
  "yt_url":"https://www.youtube.com/channel/UChKGaehqhuUnS5fagoj4OoQ",
  
}
