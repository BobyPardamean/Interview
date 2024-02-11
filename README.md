# interview tasks

## Proses Deployment Dengan Docker

Untuk melakukan proses deployment untuk menjalankan aplikasi yang diminta ini jalankan perintah dibawah dengan memasukkan password untuk variabel MYSQL_PASSWORD

```
MYSQL_PASSWORD='<some password>' docker compose --file dist/docker-compose/docker-compose.yml up
```

setelah menjalankan perintah tersebut  bukalah localhost berikut
```
http://localhost:8888
```
Berikut untuk images  dan container yang berhasil dibentuk setelah menjalankan  perintah Docker Compose

## Docker Images
![Images](/assets/images_docker.png)

## Docker Container
![Container](/assets/container_docker.png)

Berikut hasil deployment aplikasi dapat diakses melalui localhost:8888
![Home](/assets/home.png)






