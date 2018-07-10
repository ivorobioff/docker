
Use this to run a command within a container: 

`docker run --rm -w /app  -v $(pwd):/app -p 8080:8080 -it php72`