在go语言中的代码文件中最上层会定义一个package声明开头，说明源文件所属的包

而后使用Import导入依赖的包，其次为包级别的变量，产量，类型和函数的什么和赋值

函数中可定义局部的变量和常量等。

如下：

```
package main

import "fmt"

func main(){
  fmt.Println("hello world!")
}
```

package main 中的main是程序的入口。在后面的包管理中会有其他的方式表示

