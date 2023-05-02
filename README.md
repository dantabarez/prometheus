# prometheus
prueba de prometeus en docker y local

docker build -t mi-prometheus-image .
docker run --name prometheus -d -p 127.0.0.1:9090:9090 mi-prometheus-image

