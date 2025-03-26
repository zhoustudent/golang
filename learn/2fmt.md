## fmt包
fmt包是go的标准库，提供了格式化的IO功能，包括打印、格式化字符串、格式化输出、格式化输入、格式化错误、格式化日志等功能。
## 格式化字符串
```go
package main
import "fmt"

func main() {
	fmt.Println("Hello, World!")
}
```
## 格式化输出
```go
package main
import "fmt"

func main() {
	fmt.Printf("Hello, World!")
}
```
## fmt用法及区别
```go
package main

func main() {
  fmt.Println("Hello, World!")
  fmt.Printf("Hello, World!")
  fmt.Print(223)
  fmt.Scanln(&name)
  fmt.Scanf(23432)
  fmt.Scan(23)
  fmt.Sprint(234)
  fmt.Sprintln(2324)
}
```
他们之间的区别：
1. Println()会自动换行
2. Print()不会自动换行
3. Printf()会格式化输出
4. Scanln()会阻塞等待输入
5. Scanf()会阻塞等待输入
6. Scan()会阻塞等待输入
7. Sprint()不会自动换行
8. Sprintf()不会自动换行

## 打印类型
```go
package main

func main() {
  fmt.Printf("%T", 234)
}
```


