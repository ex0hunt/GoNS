# GoNS

DNS server for home usage. Can resolve by global DNS (external dns) and internal
by searching in private_domains list. Also, GoNS can use redis-cache for dns requests.

**GoNS currently supports only IPv4 addresses for internal resolving**

### Build
```go build gons.go```

### Run
```./gons```