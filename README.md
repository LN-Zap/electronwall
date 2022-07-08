# ⚡️🛡 electronwall
A tiny firewall for LND that can filter Lightning channel opening requests and HTLC forwards on your node. electronwall runs in the background and either allows (whitelist) or rejects (blacklist) events from a list of node public keys for channel openings, or channel IDs and channel pairs for payment routings.

![Screenshot](https://user-images.githubusercontent.com/93376500/178065589-8d591646-0494-4cfd-ae5b-5d2c93a82b5c.jpg)

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
