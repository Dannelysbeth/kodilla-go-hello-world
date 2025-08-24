1. Creating the image:

` docker build -f Dockerfile -t dannelysbeth/go-hello-world:1.0.0 .`

2. Running the container:

` docker run --name nginx-hello -d -p 8080:80 -v ${PWD}:/usr/share/nginx/html:ro dannelysbeth/nginx-hello-world:1.0.0`

3. Screenshot from server:
<img width="580" height="182" alt="image" src="https://github.com/user-attachments/assets/4e31b7b3-abae-4eec-9e12-96bb409b2c80" />
