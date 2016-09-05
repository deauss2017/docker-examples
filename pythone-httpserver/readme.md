编译:
docker build -t python-httpserver:1.0 .

上传到registry:
docker tag python-httpserver:1.0 localhost:5000/python-httpserver:1.0

docker push localhost:5000/python-httpserver:1.0