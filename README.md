# ⚡️ electronwall
A RPC daemon for LND that listens in the background and allows (whitelist) or rejects (blacklist) incoming channels from a list of node public keys and incoming payment routings (HTLC forwards) from a list of node IDs.

![Screenshot 2022-07-08 at 16 58 08-2](https://user-images.githubusercontent.com/93376500/178018529-8afe42e3-357d-4d4a-a6cd-2cf278f5163e.jpg)

## Install

### From source
Build from source (you may need to install go for this):

```bash
git clone https://github.com/callebtc/electronwall.git
cd electronwall
go build .
```

### Binaries

You can download a binary for your system [here](https://github.com/callebtc/electronwall/releases). You'll still need a [config file](https://github.com/callebtc/electronwall/blob/main/config.yaml.example).

## Config
Edit `config.yaml.example` and rename to `config.yaml`.

## Run

```bash
./electronwall
```
