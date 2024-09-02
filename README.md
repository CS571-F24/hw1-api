build
```bash
docker build . -t ctnelson1997/cs571-f24-hw1-api
docker push ctnelson1997/cs571-f24-hw1-api
```

run 
```bash
docker pull ctnelson1997/cs571-f24-hw1-api
docker run --name=cs571_f24_hw1_api -d --restart=always -p 48101:48101 -v /cs571/f24/hw1:/cs571 ctnelson1997/cs571-f24-hw1-api
```
