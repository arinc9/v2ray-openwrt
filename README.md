Add v2ray feed to the bottom of `feeds.conf.default`:
```
src-git v2ray https://github.com/arinc9/v2ray-openwrt.git
```

Refresh feeds and install v2ray feed
```
./scripts/feeds update -a && ./scripts/feeds install -a
```
