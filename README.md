# quorum-raspbian
The geth of quorum compiled for raspbian.

Usage

```bash
$ git clone https://github.com/shuzang/quorum-raspbian.git
$ cd quorum-raspbian
$ sudo cp bin/geth /usr/local/bin
$ sudo chmod +x /usr/local/bin/geth
```

Then you can use geth in your raspberry pi, but the binary was just tested in 3B/3B+. Some parameters of `geth` are as follows, which is obtained by the command `geth version`.

```bash
$ geth version
WARN [09-11|03:13:38.840] Sanitizing cache to Go's GC limits       provided=1024 updated=308
Geth
Version: 1.8.18-stable
Quorum Version: 2.2.5
Architecture: arm
Protocol Versions: [63 62]
Network Id: 1337
Go Version: go1.11.6
Operating System: linux
GOPATH=
GOROOT=/usr/lib/go-1.11
```

There are also some other binary files generated in the bin directory. 

```bash
$ ls bin/
abigen    clef    evm       faucet  mimegen  puppeth  simulations  swarm-smoke
bootnode  ethkey  examples  geth    p2psim   rlpdump  swarm        wnode
```



