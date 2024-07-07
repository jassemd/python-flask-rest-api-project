Build Docker image
docker build -t python-rest-api .
Run Docker image
docker run -p 9001:9001 python-rest-api
