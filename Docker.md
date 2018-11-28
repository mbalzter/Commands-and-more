docker build -t online-pcs:0.2.6 .
docker save -o c:/temp/image online-pcs:0.2.6
docker load -i ./image
docker images - zeigt alle Images an
