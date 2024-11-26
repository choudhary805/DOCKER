1. If made any changes first build the docker file
     docker build -t {tagname} .

2. Now run it with poert forwarding mapping
    docker run -p 8080:8080 {tagname}
