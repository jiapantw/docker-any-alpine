# docker-alpine-jq

Docker image for jq based on alpine linux image, just over 5MB in size.

## Usage

- you can modify ~/.bashrc or ~/.bash_profile

```sh
alias jq="docker run -i --rm jiapantw/alpine-jq:3.8"

echo "{\"test\":1}" | jq .
cat test.json | jq .
```

- or you also can directly to use:

```sh
echo "{\"test\":1}" | docker run -i --rm jiapantw/alpine-jq:3.8 .
cat test.json | docker run -i --rm jiapantw/alpine-jq:3.8 .
```
