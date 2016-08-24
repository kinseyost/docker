# docker
Playground for learning docker to eventually containerize projects.

##Important Commands
View images
```
docker images
```
View running images
```
docker ps
```
Build an image using `Dockerfile` within current directory
```
docker build -t name-of-your-image .
```
Rename an image
```
docker tag <IMAGE_ID> <accountName>/<imageName>:<versionLabel/tag>
```
