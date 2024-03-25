hash-router-101
==
hash router experiment 
--

## Demo

* https://mitchallen.github.io/hash-router-101
* https://mitchallen.github.io/hash-router-101/#/hello
* https://mitchallen.github.io/hash-router-101/#/html
* https://mitchallen.github.io/hash-router-101/#/json
* https://mitchallen.github.io/hash-router-101/#/code
* https://mitchallen.github.io/hash-router-101/#/BOGUS - not found test

## Usage 

```sh
## Python 3 server
python3 -m http.server

http://localhost:8000/#/

http://localhost:8000/#/hello

http://localhost:8000/#/html

http://localhost:8000/#/json

http://localhost:8000/#/code

```

```sh
open index.html
## Then in the browser, append: #/hello
## Note that there is no slash before `#` when doing it this way
## ../index.html#/hello
```

## Python Server

For older versions of Python (2.x):

```sh
python -m SimpleHTTPServer
```