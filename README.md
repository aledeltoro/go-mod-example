# go mod example
A simple example for me to understand the import of third party packages. 

## Setup
This package should work anywhere we want, outside from our $GOPATH. 
Once you have [installed go](https://golang.org/doc/install), run this command to install the `greet` package in your project: 

```
go get github.com/aledeltoro/go-mod-example/greet
```

## Example

After installing the `greet` package, you should be good to go!

```go
package main

import (
	"fmt"
	"github.com/aledeltoro/go-mod-example/greet"
)

func main() {
	fmt.Println(greet.SayHi())
}

```
