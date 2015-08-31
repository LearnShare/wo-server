wo-server
====

Create HTTP file server in any directory

A simple HTTP file server for dev, DO NOT use for online service.

Install
----

`npm install -g wo-server`

Usage
----

###basic usage

```
cd dir/to/your/project/
wo-server
```

Server running at http://localhost:8135/  
Root Dir: dir/to/your/project/

###with arguments

```
wo-server -d dir/to/your/project/ -p 8080 -l
```

Supported arguments:

+ -d dir, set directory where you want to create server
+ -p port, set server port (8135 is default)
+ -l, show server logs

Enjoy.

License
----

MIT
