## Libp2p Chat
This article introduces how to develop a simple peer-to-peer chat application using libp2p. Readers who wish to follow the steps to implement the example described below should ensure that Golang is installed golang(go version>=1.11)。

````
$ git clone https://github.com/rkgitvinay/go-libp2p-chat.git

$ cd go-libp2p-chat/chat
````

## Compile and Start
```
go build chat.go
```

Step 1:
```
$ ./chat
Run './chat -d /ip4/127.0.0.1/tcp/62217/p2p/QmPTvaZ7x9YbENjam7XZ3GmcPrwTvfwi4gPATKQ4QjX7rV' on another console.
You can replace 127.0.0.1 with public IP as well.

Waiting for incoming connection
```

Step 2:
```
$ ./chat -d /ip4/127.0.0.1/tcp/62217/p2p/QmPTvaZ7x9YbENjam7XZ3GmcPrwTvfwi4gPATKQ4QjX7rV
```
