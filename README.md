# How to use this image

Run in background:

```console
$ docker run -d --name some-minergate-cli minecoins/minergate-cli -user nguyentuan4989@gmail.com -xmr
```

Get minergate-cli options with:

```console
$ docker run --rm minecoins/minergate-cli -help
```

Fetch logs of a container:

```console
$ docker logs some-minergate-cli
```
