# Dokku Binary Buildpack

Two things to make this work:

1. Add an `.binary_project` file in your project root contains to binary file name and it's options
2. Create an `.env` file in your project containing this:

```
BUILDPACK_URL="https://github.com/t0pep0/binary-buildpack.git"
```

NB:
  Binary application must listen 0.0.0.0:5000
