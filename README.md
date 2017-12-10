# vim-themis

A docker image for running [vim-themis][] on [Vim][].

## Usage

```
# Run vim-themis
docker run --rm --volume $PWD:/mnt/volume -it lambdalisue/vim-themis

# Run Vim
docker run --rm --entrypoint= -it lambdalisue/vim-themis /usr/local/bin/vim
```

[vim-themis]: https://github.com/thinca/vim-themis
[Vim]: https://github.com/vim/vim
