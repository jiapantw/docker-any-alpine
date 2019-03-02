# docker-alpine-curl

Docker image for curl based on alpine linux image, just over 5MB in size.

## Usage
- you can modify ~/.bashrc or ~/.bash_profile

```sh
alias curl="docker run -i --rm jiapantw/alpine-curl:3.8"

curl -v -X GET https://www.google.com
```

- or you also can directly to use:

```sh
docker run -it --rm jiapantw/alpine-curl:3.8 -v -X GET https://www.google.com
```
