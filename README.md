# lighttpd_env_example

lighttpdでCGIに環境変数を渡すサンプル

## 起動

```shell-session
$ brew install lighttpd
$ HOGE=helloworld lighttpd -D -f lighttpd.conf
```

## 確認

```shell-session
$ curl http://localhost:3000/cgi-bin/hello.cgi
HOGE: helloworld
```
