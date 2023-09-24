# BEAR Data
The BEAR.json is the json file of BEAR

If you want see the data in neo4j, please download the data folder from the following link and execute the docker compose file in this folder

https://drive.google.com/drive/folders/1aZZHDcWsiOavnUW77dIQf9abNFWnQfXI?usp=drive_link

The default service port is 7474, and the username is neo4j, pwd is 111111. 



Service initiation command:

```shell
pip install gdown

gdown https://drive.google.com/uc?id=1NSpOukjJvZ-KlY3gEOWeKarpmpwFQmQM

unzip data.zip

docker compose up -d
```

