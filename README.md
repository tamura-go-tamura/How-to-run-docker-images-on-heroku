# herokuでDockerを動かしたい！！

適当に

```terminal:sample
   docker build -t hogehoge
```

みたいにimageをビルドする

ほんで

```terminal:sample
   heroku container:push --app <app名>
```
みたいにdockerimageをpushでOK!!!!

