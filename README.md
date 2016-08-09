# mygos
A list of Go frameworks, libraries and software of **MY** choice, like http://awesome-go.com/

## Content

### Web Framework

* [echo](https://github.com/labstack/echo)  A fast and unfancy micro web framework for Golang.
	* [echo-contrib](https://github.com/echo-contrib)  Collection of echo middlewares.
* [iris](https://github.com/kataras/iris) Fast, unopinionated, minimalist web framework for Go. Built on top of fasthttp, up to 20x faster than the rest. [http://iris-go.com](http://iris-go.com).
* [tango](https://github.com/lunny/tango)  Package tango is a micro & pluggable web framework for Go.
	* [tango-contrib](https://github.com/tango-contrib) Collection of tango middlewares.

#### Sessions

* [session](https://github.com/gorilla/sessions) gorilla/sessions provides cookie and filesystem sessions and infrastructure for custom session backends.
	* [redistore](github.com/boj/redistore) Redis store sessions.

#### CSRF

* [nosurf](https://github.com/justinas/nosurf) CSRF protection middleware for Go.
* [csrfbanana](https://github.com/josephspurrier/csrfbanana) Golang CSRF Protection for gorilla/sessions.

### ORM

* [gorm](https://github.com/jinzhu/gorm) The fantastic ORM library for Golang, aims to be developer friendly.
* [go-pg](https://github.com/go-pg/pg) Fast PostgreSQL client and ORM for Golang.

### Database Drivers

#### Relational Databases
* [mysql](https://github.com/go-sql-driver/mysql) Mysql database driver for go.

#### NoSQL Databases

* [memcached](https://github.com/rainycape/memcache) High performance memcache client in Go (golang).
* [redigo](https://github.com/garyburd/redigo) Redigo is a Go client for the Redis database.
* [redis](https://github.com/go-redis/redis) Redis client for Golang. 

### Caches

* [groupcache](https://github.com/golang/groupcache) groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.

### Utilities

* [goreq](https://github.com/franela/goreq) Minimal and simple request library for Go language.
* [go-dry](https://github.com/ungerik/go-dry) DRY (don't repeat yourself) package for Go.
* [sortutil](https://github.com/cznic/sortutil) Utilities supplemental to the Go standard "sort" package.
* [gods](https://github.com/emirpasic/gods) Go Data Structures. Tags: Containers, Sets, Lists, Stacks, Maps, Trees, HashSet, TreeSet, ArrayList, SinglyLinkedList, DoublyLinkedList, LinkedListStack, ArrayStack, HashMap, TreeMap, RedBlackTree, BinaryHeap, Comparator, Sort.
* [fmtdate](https://github.com/metakeule/fmtdate) MS Excel (TM) syntax for Go time/date.
* [ffjson](https://github.com/pquerna/ffjson) faster JSON serialization for Go.
* [timeutil](https://github.com/leekchan/timeutil) useful extensions (Timedelta, Strftime, ...) to the golang's time package.
* [inflections](https://github.com/acsellers/inflections) A similar set of functionality to ActiveSupport's Inflections methods. Could be useful in building an interface to a Rails managed database schema.
* [logrus](https://github.com/Sirupsen/logrus) Structured, pluggable logging for Go.
* [goquery](https://github.com/PuerkitoBio/goquery) A little like that j-thing, only in Go.
* [go-flags](https://github.com/jessevdk/go-flags) Go command line option parser, provides much more functionality and nicer formatting then the builtin flag library of go.
* [go-simplejson](https://github.com/bitly/go-simplejson) a Go package to interact with arbitrary JSON.
* [easyjson](https://github.com/mailru/easyjson) Fast JSON serializer for golang.
* [gopsutil](https://github.com/shirou/gopsutil) psutil for golang.

### Crawlers
* [pholcus](https://github.com/henrylee2cn/pholcus) [Crawler framework (golang)] Pholcus is pure golang crawler software, use single/server/client mods with web GUI support. Chinese Wiki.

### Doc tools
* [go-swagger] (https://github.com/go-swagger/go-swagger) Swagger 2.0 implementation for go [https://goswagger.io]().

### Debugs

* [go-torch](https://github.com/uber/go-torch) Stochastic flame graph profiler for Go programs.
