gomon
=====

go source file monitor, which restarts/rebuilds your go package automatically
while you are changing it.

Usage
-----

    gomon [dir] -- [cmd]
    gomon src -- run -x server.go # execute go run -x server.go
    gomon src -- build -x package # execute go build -x package

