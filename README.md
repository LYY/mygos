# mygos

A list of Go frameworks, libraries and software of **MY** choice, like <http://awesome-go.com/>

## Content

### Web Framework

* [labstack/echo](https://github.com/labstack/echo)  A fast and unfancy micro web framework for Golang.
    * [LYY/echo-middleware](https://github.com/LYY/echo-middleware)  My own collection of echo middlewares.
* [kataras/iris](https://github.com/kataras/iris) Fast, unopinionated, minimalist web framework for Go. Built on top of fasthttp, up to 20x faster than the rest. [http://iris-go.com](http://iris-go.com).
* [lunny/tango](https://github.com/lunny/tango)  Package tango is a micro & pluggable web framework for Go.
	* [tango-contrib](https://github.com/tango-contrib) Collection of tango middlewares.
* [go-chi/chi](https://github.com/go-chi/chi) Lightweight, idiomatic and composable router for building Go HTTP services.

#### Sessions

* [gorilla/session](https://github.com/gorilla/sessions) gorilla/sessions provides cookie and filesystem sessions and infrastructure for custom session backends.
	* [boj/redistore](github.com/boj/redistore) Redis store sessions.

#### CSRF

* [justinas/nosurf](https://github.com/justinas/nosurf) CSRF protection middleware for Go.
* [josephspurrier/csrfbanana](https://github.com/josephspurrier/csrfbanana) Golang CSRF Protection for gorilla/sessions.

#### WebSocket

* [gorilla/websocket](https://github.com/gorilla/websocket) A WebSocket implementation for Go.
* [graarh/golang-socketio](https://github.com/graarh/golang-socketio) Golang socket.io client and server.

#### Authentication

* [volatiletech/authboss](https://github.com/volatiletech/authboss) The boss of http auth.

#### Validator

* [go-playground/validator](https://github.com/go-playground/validator) 💯Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.
* [asaskevich/govalidator](https://github.com/asaskevich/govalidator) [Go] Package of validators and sanitizers for strings, numerics, slices and structs.

#### JWT

* [dgrijalva/jwt-go](https://github.com/dgrijalva/jwt-go) Golang implementation of JSON Web Tokens (JWT).

#### Solutions

* [qor/qor](https://github.com/qor/qor) QOR is a set of libraries written in Go that abstracts common features needed for business applications, CMSs, and E-commerce systems.
* [name5566/leaf](https://github.com/name5566/leaf) A game server framework in Go (golang).

### ORM

* [jinzhu/gorm](https://github.com/jinzhu/gorm) The fantastic ORM library for Golang, aims to be developer friendly.
* [go-pg/pg](https://github.com/go-pg/pg) Fast PostgreSQL client and ORM for Golang.

### Microservice

* [go-kit/kit](https://github.com/go-kit/kit) A standard library for microservices.

### Database

#### Relational databases

* [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) Mysql database driver for go.

#### NoSQL databases

* [HouzuoGuo/tiedot](https://github.com/HouzuoGuo/tiedot) Your NoSQL database powered by Golang.
* [siddontang/ledisdb](https://github.com/siddontang/ledisdb) A high performance NoSQL powered by Go.
* [rainycape/memcached](https://github.com/rainycape/memcache) High performance memcache client in Go (golang).
* [garyburd/redigo](https://github.com/garyburd/redigo) Redigo is a Go client for the Redis database.
* [go-redis/redis](https://github.com/go-redis/redis) Redis client for Golang.

#### Distributed database

* [pingcap/tidb](https://github.com/pingcap/tidb) TiDB is a distributed HTAP database compatible with MySQL protocol.
* [cockroachdb/cockroach](https://github.com/cockroachdb/cockroach) CockroachDB - the open source, cloud-native SQL database.

#### Time series database

* [prometheus/prometheus](https://github.com/prometheus/prometheus) The Prometheus monitoring system and time series database.

#### KV

* [boltdb/bolt](https://github.com/boltdb/bolt) An embedded key/value database for Go.

### Caches

* [golang/groupcache](https://github.com/golang/groupcache) groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
* [patrickmn/go-cache](https://github.com/patrickmn/go-cache) An in-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.

### JSON

* [tidwall/gjson](https://github.com/tidwall/gjson) Get JSON values quickly - JSON Parser for Go.
* [pquerna/ffjson](https://github.com/pquerna/ffjson) faster JSON serialization for Go.
* [bitly/go-simplejson](https://github.com/bitly/go-simplejson) a Go package to interact with arbitrary JSON.
* [mailru/easyjson](https://github.com/mailru/easyjson) Fast JSON serializer for golang.

### HTTP Utitiles

* [franela/goreq](https://github.com/franela/goreq) Minimal and simple request library for Go language.
* [levigross/grequests](https://github.com/levigross/grequests) A Go "clone" of the great and famous Requests library.
* [sethgrid/pester](https://github.com/sethgrid/pester) Go (golang) http calls with retries and backoff.

### Message queue

* [nsqio/nsq](https://github.com/nsqio/nsq) A realtime distributed messaging platform.
	* [youzan/nsq](https://github.com/youzan/nsq) A nsq fork by youzan, add some useful features.
* [nats-io/go-nats](https://github.com/nats-io/go-nats) Golang client for NATS, the cloud native messaging system.

### Test

* [golang/mock](https://github.com/golang/mock) GoMock is a mocking framework for the Go programming language.
* [stretchr/testify](https://github.com/stretchr/testify) A toolkit with common assertions and mocks that plays nicely with the standard library.
* [Selvatico/go-mocket](https://github.com/Selvatico/go-mocket) Go GORM & SQL mocking library.

### Logging

* [Sirupsen/logrus](https://github.com/Sirupsen/logrus) Structured, pluggable logging for Go.
* [uber-go/zap](https://github.com/uber-go/zap) Blazing fast, structured, leveled logging in Go.
* [inconshreveable/log15](https://github.com/inconshreveable/log15) Structured, composable logging for Go.
* [rs/zerolog](https://github.com/rs/zerolog) Zero Allocation JSON Logger.

### Dependency & Environment

* [golang/dep](https://github.com/golang/dep) Go dependency management tool.
* [moovweb/gvm](https://github.com/moovweb/gvm) Go Version Manager.

### Resource Embedding

* [UnnoTed/fileb0x](https://github.com/UnnoTed/fileb0x) A better customizable tool to embed files in go; update embedded files remotely without restarting the server.

### Cron / Job runner

* [robfig/cron](https://github.com/robfig/cron) A cron library for go.
* [bamzi/jobrunner](https://github.com/bamzi/jobrunner) Framework for performing work asynchronously, outside of the request flow.
* [jrallison/go-workers](https://github.com/jrallison/go-workers) Sidekiq compatible background workers in golang.

### Command-line

* [alecthomas/kingpin](https://github.com/alecthomas/kingpin) A Go (golang) command line and flag parser.

### Network / Socket

* [nathanjsweet/zsocket](https://github.com/nathanjsweet/zsocket) Zero-copy sockets for Linux in Golang.
* [miekg/dns](https://github.com/miekg/dns) DNS library in Go.

### Proxy

* [cyfdecyf/cow](https://github.com/cyfdecyf/cow) HTTP proxy written in Go. COW can automatically identify blocked sites and use parent proxies to access.
* [inconshreveable/ngrok](https://github.com/inconshreveable/ngrok) Introspected tunnels to localhost.
* [shell909090/goproxy](https://github.com/shell909090/goproxy) A tunnel proxy for GFW.

### Server Applications

* [mholt/caddy](https://github.com/mholt/caddy) Fast, cross-platform HTTP/2 web server with automatic HTTPS.

### DevOps Tools

* [go-gitea/gitea](https://github.com/go-gitea/gitea) Gitea: Git with a cup of tea.
* [gogits/gogs](https://github.com/gogits/gogs) Gogs is a painless self-hosted Git service.

### Utilities

* [ungerik/go-dry](https://github.com/ungerik/go-dry) DRY (don't repeat yourself) package for Go.
* [cznic/sortutil](https://github.com/cznic/sortutil) Utilities supplemental to the Go standard "sort" package.
* [emirpasic/gods](https://github.com/emirpasic/gods) Go Data Structures. Tags: Containers, Sets, Lists, Stacks, Maps, Trees, HashSet, TreeSet, ArrayList, SinglyLinkedList, DoublyLinkedList, LinkedListStack, ArrayStack, HashMap, TreeMap, RedBlackTree, BinaryHeap, Comparator, Sort.
* [metakeule/fmtdate](https://github.com/metakeule/fmtdate) MS Excel (TM) syntax for Go time/date.
* [leekchan/timeutil](https://github.com/leekchan/timeutil) useful extensions (Timedelta, Strftime, ...) to the golang's time package.
* [acsellers/inflections](https://github.com/acsellers/inflections) A similar set of functionality to ActiveSupport's Inflections methods. Could be useful in building an interface to a Rails managed database schema.
* [PuerkitoBio/goquery](https://github.com/PuerkitoBio/goquery) A little like that j-thing, only in Go.
* [jessevdk/go-flags](https://github.com/jessevdk/go-flags) Go command line option parser, provides much more functionality and nicer formatting then the builtin flag library of go.
* [shirou/gopsutil](https://github.com/shirou/gopsutil) psutil for golang.
* [u-root/u-root](https://github.com/u-root/u-root) A universal root: u-root creates a root file system (initramfs) containing a busybox-like set of tools in Go.
* [bwmarrin/snowflake](https://github.com/bwmarrin/snowflake) A very simple to use Go (golang) package to generate or parse Twitter snowflake IDs.
* [fatih/structtag](https://github.com/fatih/structtag) Parse and modify Go struct field tags.
* [awnumar/memguard](https://github.com/awnumar/memguard) Easy and secure handling of sensitive memory, in pure Go.
* [cespare/xxhash](https://github.com/cespare/xxhash) A Go implementation of the 64-bit xxHash algorithm (XXH64).
* [imdario/mergo](https://github.com/imdario/mergo) Mergo: merging Go structs and maps since 2013.
* [jung-kurt/gofpdf](https://github.com/jung-kurt/gofpdf) A PDF document generator with high level support for text, drawing and images.
* [mkouhei/gosh](https://github.com/mkouhei/gosh) Interactive shell for Golang.
* [codeskyblue/go-sh](https://github.com/codeskyblue/go-sh) Like python-sh, for easy call shell with golang.
* [ChimeraCoder/gojson](https://github.com/ChimeraCoder/gojson) Automatically generate Go (golang) struct definitions from example JSON.
* [tealeg/xlsx](https://github.com/tealeg/xlsx) Google Go (golang) library for reading and writing XLSX files.
* [surgemq/surgemq](https://github.com/surgemq/surgemq) High-Performance MQTT Server and Client Libraries.
* [fsnotify/fsnotify](https://github.com/fsnotify/fsnotify) Cross-platform file system notifications for Go.
* [djherbis/buffer](https://github.com/djherbis/buffer) Composable Buffers for Go #golang.
* [go-godo/godo](https://github.com/go-godo/godo) Golang build tool in the spirt of rake, gulp.
* [glycerine/offheap](https://github.com/glycerine/offheap) An off-heap hash-table in Go. Used to be called go-offheap-hashtable, but we shortened it.
* [chrislusf/seaweedfs](https://github.com/chrislusf/seaweedfs) SeaweedFS is a simple and highly scalable distributed file system.
* [gogo/protobuf](https://github.com/gogo/protobuf) Protocol Buffers for Go with Gadgets.
* [sony/gobreaker](https://github.com/sony/gobreaker) Circuit Breaker implemented in Go.
* [thoas/go-funk](https://github.com/thoas/go-funk) A modern Go utility library which provides helpers (map, find, contains, filter, ...).
* [viant/toolbox](https://github.com/viant/toolbox) Toolbox - go utility library.

### Crawlers

* [henrylee2cn/pholcus](https://github.com/henrylee2cn/pholcus) [Crawler framework (golang)] Pholcus is pure golang crawler software, use single/server/client mods with web GUI support. Chinese Wiki.
	* [henrylee2cn/pholcus_lib](https://github.com/henrylee2cn/pholcus_lib) Public pholcus rules.

### Doc tools

* [go-swagger/go-swagger](https://github.com/go-swagger/go-swagger) Swagger 2.0 implementation for go https://goswagger.io.

### Debugs/profiler

* [derekparker/delve](https://github.com/derekparker/delve) Delve is a debugger for the Go programming language.
* [uber/go-torch](https://github.com/uber/go-torch) Stochastic flame graph profiler for Go programs.
