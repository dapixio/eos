## Goal

Connect to an alternative `nodeos` or `keosd` host

`cleos` can be connected to different nodes by using the `-H, --host` and `-p, --port` optional arguments.

If no optional arguments are used (i.e. -H and -p), `cleos` automatically tries to connect to a locally running eos node (i.e. `nodeos`).

## Before you begin

* Install the currently supported version of cleos

## Steps



## Connecting to Nodeos

```bash
  cleos -url nodeos-host:8888 ${subcommand}
```

## Connecting to Keosd

```bash
  cleos --wallet-url keosd-host:8888 ${subcommand}
```