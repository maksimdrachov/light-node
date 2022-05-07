## light.node

Prerequisites:

- Raspberry Pi (+ power cable)
- Hard disk (1 TB)
- Ethernet connection
- SD card (>64GB)

### 1. Installing Fedora (server)

#### ssh

### 2. Setting up storage (SD + HDD)

### 3. Setting up Bitcoin node

[Source](https://blockgeeks.com/install-bitcoin-core/)

```
wget https://bitcoin.org/bin/bitcoin-core-22.0/bitcoin-22.0-aarch64-linux-gnu.tar.gz

tar xzf bitcoin-22.0-aarch64-linux-gnu.tar.gz

cd bitcoin-22.0

cd bin

sudo install -m 0755 -o root -g root -t /usr/local/bin *
```

Now do:

```
bitcoind -daemon -datadir=<dir>
```

check size of bitcoin blockchain:

```
du -sh *
```

track progress

bitcoin-cli -datadir=/Seagate/bitcoin-data getblockcount

[source](https://bitcoin.stackexchange.com/questions/10859/how-to-check-bitcoind-block-chain-download-progress-level)

### 4. Setting up Lightning node

### 5. Setting up light.wifi access point

### 6. Setting up light.vpn router

### 7. Setting up light.server 


### Sources

- [Building a Raspberry Pi home server](https://raduzaharia.medium.com/building-a-raspberry-pi-home-server-9cab1ba7ab57)
- [Initial Fedora Server 35 configuration on a Raspberry Pi](https://raduzaharia.medium.com/initial-fedora-server-35-configuration-on-a-raspberry-pi-d317d462e2e8)
- [How to set up a home server and use it as a Bitcoin node](https://www.expressvpn.com/blog/how-to-set-up-a-home-server-and-use-it-as-a-bitcoin-node/)

- [Raspberry Pi - WiFi Access Point](https://medium.com/@daltonmblack/raspberry-pi-wifi-access-point-9a6884e4a361)
- [Raspberry Pi - VPN Router](https://muokicaleb.medium.com/raspberry-pi-vpn-router-cb9722affb1)

