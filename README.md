# dotenv

Load file `.env` to environment variables of current terminal session

## Installation

```
go get -u github.com/junlapong/dotenv
```

## Usage

Make a `.env` file that looks something like

```
FOO=BAR
```

then call

```
$ dotenv
$ echo $FOO
BAR
```

## TODO

- [ ] Support `dotenv -f /path/to/.env` file
