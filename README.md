# cli-gopher

A tiny Go CLI that prints a colorful ASCII Gopher and exits.

## Features

- richer Gopher face/details
- 24-bit truecolor ANSI output
- `--no-color` mode for plain terminals

## Run

```bash
go run .
```

## Run without colors

```bash
go run . --no-color
```

## Build

```bash
go build -o cli-gopher .
./cli-gopher
./cli-gopher --no-color
```
