# apache2_php

## Usage
To run the image
```sh
docker run -d -P --name lamp chihhunglin/lamp
```
To see the port forwarding
```sh
docker port lamp
```
To login ssh container (password: root)
```sh
ssh root@localhost -p <host port>
```
To login mysql after login container
```sh
mysql -h localhost
```
