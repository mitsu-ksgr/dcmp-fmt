dcmp-fmt
========

Format and display the outputs of docker compose ps.


```sh
$ docker compose ps --format json | dcmp-fmt


# with watch
$ watch -n 1 'docker compose ps --format json | dcmp-fmt'
```


