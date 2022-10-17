list running containers 
`docker ps`

list all containers 
`docker ps -a`

run docker image in interactive mode
`docker run -it node`

stop running image
`docker stop image_name`

remove image
`docker rm image_1 image_2 image_3`

remove all image
`docker image prune`

for newly done changes
`docker build .` => assuming Dockerfile is there

for copy from current machine to image
`docker cp folder/. image_name:/pathtocopy`
for copy from image to current machine
`docker cp image_name:/pathtocopy folder/.`

run docker with named container
`docker run 80:3000 -d --rm --name name_image_here image_id`

docker build image with tag and version
`docker build -t name_here:version_here .`



Tip
Always keep following copy before code copy statement 
`COPY package.json /app`
`RUN npm i`




