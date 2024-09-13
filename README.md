# MineXLauncher-host

Use this repo to host MineXLauncher on your own website!

**You need to be on Linux for this to work. Support for other OSes coming soon.**

#### Steps:

```shell
git clone https://github.com/zumbiepig/MineXLauncher-host.git
cd MineXLauncher-host

bin/linux-x64
```

#### Configuration:

Setting a port:

```shell
PORT=3000 bin/linux-x64
```

Setting cache TTL:

```shell
CACHE_MINUTES=10 bin/linux-x64
```

Setting maximum cache size:

```shell
CACHE_SIZE=0.5 bin/linux-x64
```
