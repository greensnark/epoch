# epoch

A [Stack](https://docs.haskellstack.org/en/stable/README/) script to convert
epoch seconds or milliseconds to an RFC3339 time

## Usage

(This tool needs [Haskell
Stack](https://docs.haskellstack.org/en/stable/README/), make sure you've
installed it)

Show RFC3339 equivalent of Unix epoch time:

```sh
$ epoch 1542241604572
2018-11-14T20:26:44-04:00
$ epoch 1542241604
2018-11-14T20:26:44-04:00
```

Show current Unix epoch time (milliseconds):

```sh
$ epoch
1552841883022
```
