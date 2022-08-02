# leveldb-rpc
LevelDB's XML-RPC based interface.
## Getting Started
Currently, only following methods are supported:
* put
* get
* delete
## start an XML-RPC server
```sh
$ python leveldb-server.py
```
## start an XML-RPC client
```sh
$ python leveldb-client.py
localhost:8000> get foo
localhost:8000> put foo bar
localhost:8000> get foo
bar
localhost:8000> delete foo
localhost:8000> <CTRL-D>
$ 
```



