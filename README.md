# vars

[![Package Version](https://img.shields.io/hexpm/v/vars)](https://hex.pm/packages/vars)
[![Hex Docs](https://img.shields.io/badge/hex-docs-ffaff3)](https://hexdocs.pm/vars/)

```sh
gleam add vars
```
## Usage

### Compile the program to an escript

```sh
gleam run -m gleescript
```

### Make the escript executable

```sh
chmod +x ./vars
```

### Run the program

```sh
./vars get USER
# => "USER=aristoteles"
```

## Development

```sh
gleam run   # Run the project
gleam test  # Run the tests
gleam shell # Run an Erlang shell
```
