## Console commands
Import library<br/>
```Shell
go get github.com/User_name/project_name/package_name
```
Run program<br/>
```Shell
go get github.com/User_name/project_name/package_name
```

## Golang
Import package:<br/>
placed in *pckg_name* directory<br/>
```import "./pckg_name"```<br/>
imported from internet<br/>
```import "github.com/User_name/project_name/package_name"```<br/>

Import many packages  
```Go 
import  (
    "./package_name"
    "fmt"
)
```
Get variable type
```Go 
import "fmt"
import "reflect"
// Print type of MyVar variable
fmt.Println(reflect.TypeOf(MyVar))
```

Logical operators:<br/>
AND operator<br/>
```Go 
true  && true	true
true  && false	false
false && true	false
false && false	false
```
OR operator<br/>
```Go 
true  || true	true
true  || false	true
false || true	true
false || false	false
```
NOT operator<br/>
```Go 
!true	false
!false	true
```
