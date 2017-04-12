# Simple image to run stylelint, eslint

## Usage

```sh
docker run --rm -v $PWD:/app/ dimanech/linters-alp stylelint
```

## Debug

```sh
docker run --rm -v $PWD:/app/ -it --entrypoint=bash dimanech/linters-alp
```

