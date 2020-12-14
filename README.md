# prime_portraits

To run the prime portraits, you can follow the following steps: 
1. install docker compose
2. type docker-compose up


Alternatively, clone this repository and in the folder run: 
```bash
docker build -t primeportraits dockerfiles
docker run -it -p 8888:8888 -v $(pwd):/notebooks primeportraits
```

After you do this a jupyter notebook server should be started at http://localhost:8888/ . The password should be 'abc'

There you can open the jupyter notebook and find your own prime portrait!
