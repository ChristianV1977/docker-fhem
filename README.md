# fhem
FHEM for Raspberry Pi

## Thanks
Initial content was copied from https://github.com/Raigen/docker-fhem. Many thanks for your effort! 

## clips

```
cd ..
rm -rf docker-fhem 

git clone https://github.com/sejnub/docker-fhem.git
cd docker-fhem 

docker build -t sejnub/fhem .

docker rm -f fhem
docker run -d --rm -p 8083:8083 --name fhem sejnub/fhem

sudo docker exec -i -t fhem bash

```
