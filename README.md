# learning-go

1. 编译代码前一定要线运行`go fmt`或`goimports`
2. `go fmt`  代码格式化
3. `goimports -l -w .`  增强版的`go fmt`
   1. `-l`将格式不正确的文件打印到控制台
   2. `-w`在原路径修改文件
   3. `.`指定要扫描的文件