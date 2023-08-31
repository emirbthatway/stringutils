# stringutils

A basic stringutils package. It contains only Reverse() function.

```
func Reverse(s string) (string, error)
```

____

## Installation

Go to root folder which contains go.mod file.

```
go get github.com/emirbthatway/stringutils
```

______

## Usage

```
package main

import (
	"fmt"

	"github.com/emirbthatway/stringutils"
)

func main(){
	reversed, err := stringutils.Reverse("famidok")
	if err != nil {
		log.Fatal(err)
	}    
	fmt.Println(reversed) // kodimaf
}
```


____

## Contributor(s)

* [Emir Burak Önder](https://github.com/emirbthatway) - Creator, maintainer


## Contribute

All PR’s are welcome!

1. `fork` (https://github.com/vigo/stringutils-demo/fork)
1. Create your `branch` (`git checkout -b my-feature`)
1. `commit` yours (`git commit -am 'add some functionality'`)
1. `push` your `branch` (`git push origin my-feature`)
1. Than create a new **Pull Request**!

---

## License

This project is licensed under GPLv3

---

