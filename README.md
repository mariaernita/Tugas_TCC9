</h1>Teknologi Cloud Computing</h1>

Tugas Deploy Static Html
Maria Ernita Saba
155410136

touch Dockerfile

nano Dockerfile // isi dari Docker file 
FROM nginx:alpine 
COPY myweb_Maria-master/ /usr/share/nginx/html

docker build -t ernita:v1 .

docker images

docker run -d -p 80:80 ernita:v1

cek ip docker dengan perintah ifconfig
172.17.0.1

