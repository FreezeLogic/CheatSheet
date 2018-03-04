## Console commans
Import library  
```go get github.com/User_name/project_name/package_name```




## Golang
Import package placed in *pckg_name* directory
```import "./pckg_name"```

```import "github.com/User_name/project_name/package_name"```

Import many packages  
```Go 
import  (
"./package_name"  
fmt"
)
```

Get variable type
```Go 
import "fmt"
import "reflect"
// Print type of MyVar variable
fmt.Println(reflect.TypeOf(MyVar))
```
