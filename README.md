
# Dependency resolution bug local vs published
```shell
./mill -i __.publishLocal
```

vs


```shell
./mill -i mill.scalalib.PublishModule/publishAll
    ...
```






