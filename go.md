## Console commans
Import library<br/>
```go get github.com/User_name/project_name/package_name```

## Golang
Import package:<br/>
placed in *pckg_name* directory <br/>
```import "./pckg_name"```

```import "github.com/User_name/project_name/package_name"```

Import many packages  
```Go 
import  (
&nbsp; "./package_name"  
&nbsp; "fmt"
)
```
Get variable type
```Go 
import "fmt"
import "reflect"
// Print type of MyVar variable
fmt.Println(reflect.TypeOf(MyVar))
```

Logical operators

|   Expression  |  AND  |  OR   |
| ------------- |-------| ------|
| true && true  | true  | true  |
| true && false | false | true  |
| false && true | false | true  |
| false && false| false | false |
 
AND operator
```Go 
true && true	true
true && false	false
false && true	false
false && false	false
```
OR operator
```Go 
true || true	true
true || false	true
false || true	true
false || false	false
```
NOT operator
```Go 
!true	false
!false	true
```
