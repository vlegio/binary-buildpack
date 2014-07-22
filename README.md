# Dokku Static Buildpack using Nginx

Two things to make this work:

1. Add an empty `.servestatic` file in your project root
2. Create an `.env` file in your project containing this:

```
BUILDPACK_URL="https://github.com/t0pep0/static-buildpack.git"
```

FIXES:
 DROP apt-get command, add  download packets from http://security.ubuntu.com
