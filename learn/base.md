## 基础文件
```
go.mod
main.go
```
```go.mod```定义了go的依赖，```main.go```是主文件
## 代码结构
```
package main
import "fmt"

func main() {
	fmt.Println("Hello, World!")
}
```
```package main```定义了包名，```import "fmt"```导入了fmt包，```func main()```定义了主函数
## 运行
```
go run main.go
```