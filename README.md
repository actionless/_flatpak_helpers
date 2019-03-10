```fish
env CARGO_HOME=(pwd)/cargo_home cargo fetch
tar cf cargo_home.tar cargo_home
gzip cargo_home.tar
```
