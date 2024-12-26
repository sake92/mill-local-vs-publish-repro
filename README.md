
# Dependency resolution bug local vs published
```shell
./mill -i sharaf.publishLocal
```

vs


```shell
./mill -i mill.scalalib.PublishModule/publishAll
    ...
```






