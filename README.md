# go-mimetype
add mime types into standard library "mime"

## How to Use
1. import the package
``` go
import (
    _ "github.com/imroc/go-mimetype"
    "mime"
)
```

2. use the standard library
``` go
typ := mime.TypeByExtension(".xml")
```