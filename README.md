# THE ICONIC - Public Docker Images

These are public docker images with tools used by our Developers and Pipeline scripts.

## apiDoc
Example:
```docker run --rm -v $PWD:/app theiconic/apidoc -i src/Controller/ -o public/docs```

*Mounts current folder inside docker container, searches src/Controller folder for annotations and output to public/docs.*
