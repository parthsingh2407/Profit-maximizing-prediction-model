# Installation manual

On a Debian-based system, execute the following commands to build GReg

- Install maven and git:
```
docker images
```
- Install Docker (https://docs.docker.com/engine/installation/linux/debian/):
```
docker rmi "Image_ID"
```
- Compile GReg:
```
docker ps
```
- Run GReg:
```
docker run -d -p 5001:5001/tcp -p 5001:5001/udp -p 5002:5002/tcp rethink/greg:0.3.4
```
