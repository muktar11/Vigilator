
# Vigilate

This is the source code for Working with Websockets in Go (Golang).

A dead simple monitoring service, intended to replace things like Nagios.

## Build

Build in the normal way on Mac/Linux:

~~~
go build -o vigilate cmd/web/*.go
~~~

Or on Windows:

~~~
go build -o vigilate.exe cmd/web/.
~~~

Or for a particular platform:

~~~git@github.com:muktar11/recommendation-algo.git vigilate cmd/web/*.go
~~~git@github.com:muktar11/recommendation-algo.git
~~~
cd ipe
ipe.exe
~~~

Run with flags:

~~~
./vigilate \
-dbuser='tcs' \
-pusherHost='localhost' \
-pusherPort='4001' \
-pusherKey='123abc' \
-pusherSecret='abc123' \
-pusherApp="1" \
-pusherSecure=false
~~~~

## All Flags

~~~~
tcs@grendel vigilate-udemy % ./vigilate -help
Usage of ./vigilate:
  -db string
        database name (default "vigilate")
  -dbhost string
        database host (default "localhost")
  -dbport string
        database port (default "5432")
  -dbssl string
        database ssl setting (default "disable")
  -dbuser string
        database user
  -domain string
        domain name (e.g. example.com) (default "localhost")
  -identifier string
        unique identifier (default "vigilate")
  -port string
        port to listen on (default ":4000")
  -production
        application is in production
  -pusherApp string
        pusher app id (default "9")
  -pusherHost string
        pusher host
  -pusherKey string
        pusher key
  -pusherPort string
        pusher port (default "443")
  -pusherSecret string
        pusher secret
   -pusherSecure
        pusher server uses SSL (true or false)
~~~~

