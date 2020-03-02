# prime_portraits

1. install docker compose
2. type docker-compose up


Alternatively, clone this repository and in the folder run: 
docker build -t primeportraits dockerfiles
docker run -it -p 8888:8888 -v $(pwd):/notebooks primeportraits
