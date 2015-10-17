# docker-hugs98

# How to run
Map your current directory to /code
```
docker run -i -t --rm -v "$PWD":/code d1egoaz/hugs98 [args...]
```

Inside hugs load the file (test.hs must be in current directory)
```
:load test.hs
```
or
```
:load src/test.hs
```

if you made changes to code you just need to reload (isn't necessary to run again the docker container:
```
:reload
```
