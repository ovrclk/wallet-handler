# akash-wallet-handler

A command line GUI for managing an Akash wallet

## Dependencies

- Docker
- dialog
- qrencode

## Debian 10+/Ubuntu 18.04+
```
apt-get update ; apt-get -yqq install dialog qrencode docker.io
```
## Arch Linux (Manjaro)
```
pacman -S dialog qrencode docker
```
## Mac (Requires [Docker installed](https://docs.docker.com/desktop/mac/install/))
```
brew install qrencode
brew install dialog
```

# Getting Started

The akash-wallet-handler will detect a first time run and create a data folder and variables file in the location where `./menu.sh` is run.  The data folder and variables file will contain your wallet information and should not be deleted or modified.  Be sure to backup these files!

```
#To start akash-wallet-handler run:
git clone https://github.com/ovrclk/akash-wallet-handler
cd akash-wallet-handler
./menu.sh
```
# Support and Documentation

If you need help or want to request changes please contact the team in Discord or create an issue here on github.
Additionally you can check the Wiki for more documentation.

# Todos
```
-- Deployment manager
-- View last tx
-- View bids
-- Place bids
-- Bid manager?
```
