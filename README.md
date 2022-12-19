# Prerequisities

Install https://www.cyrusimap.org/sasl/

## MacOS

```bash
brew install cyrus-sasl
```

## Linux

```bash
#TODO
```

# Build

```bash
luarocks build
luarocks pack cyrussasl
luarocks pack cyrussasl-1.1.0-9.rockspec
```

## Publish

Manually copy to
https://github.com/neopaf/rocks

Read README there and publish to
https://neopaf.github.io/rocks/

## Installation

```bash
luarocks install cyrussasl --server https://neopaf.github.io/rocks/
```

OR

```bash
tarantoolctl rocks install cyrussasl --server https://neopaf.github.io/rocks/
```
