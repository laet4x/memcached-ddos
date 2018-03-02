# MemcacheDos
Memcache DDOS.

# Steps
```
git clone https://github.com/laet4x/memcached-ddos.git
cd memcached-ddos
npm install
./node_modules/.bin/ts-node main.ts --list result.txt --ip 1.1.1.1 --port 80
```

# Q&A
* Testing Server
  > CentOS7, nodejs v6.12.3 yum
* `npm install raw-socket`
  > use `npm install --unsafe` 

# Related News
* [Memcrashed - Major amplification attacks from UDP port 11211](https://blog.cloudflare.com/memcrashed-major-amplification-attacks-from-port-11211/)
* [Use Memcache as a DRDoS Reflection Amplifier for DDoS Attacks](https://cert.360.cn/warning/detail?id=c63eb87058834e37c7c112c35ef5f9fd)
