# Docker build
```
git clone https://github.com/fjkj2/dockerTest.git
cd dockerTest/UbuntuDocker
docker build --rm -it mast741/ut ./
docker images
```

# Docker run
```
docker run -it --name ut -v ~/df:/df --rm mast741/ut:2
```
