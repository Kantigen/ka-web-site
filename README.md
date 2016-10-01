# Keno Antigen Main Web Site

Main web site html for the Keno Antigen game

# install

The Docker container does not need to be built, it can be
downloaded automatically from docker-hub.

However, if you change (for example package.json) then it 
can be built thus.

```bash
$ ./build_docker.sh
```

Then run a shell in the container and run the jekyll server


```bash
$ ./run_docker.sh
root@17d2ed3096e5:/docs# jekyll serve
```

This will expose the jekyll web site on your local server, port 80

