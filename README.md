# Python web server in container test 
Based on 
https://medium.com/oracledevs/create-a-simple-docker-container-with-a-python-web-server-26534205061a





podman build -f Dockerfile . -t web-server-test
podman run -p 8000:8000/tcp web-server-test

