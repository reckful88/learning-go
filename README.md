# learning-go

### 命令
1. `go run`
2. `go build`
   1. `go build -o `
3. `go install`
4. `golint ./...` 代码格式检查
5. `go vet ./...` 代码其他错误检查
6. `golangci-lint run`  结合了所有检查类工具
### 工具
1. `golint` 代码格式检查
   1. `go install golang.org/x/lint/golint@latest`
2. `goimports` 格式化代码
   1. `go install golang.org/x/tools/cmd/goimports@latest`
3. `hey` 对 HTTP 进行负载测试
   1. `go install github.com/rakyll/hey@latest`

### 代码格式化
1. 编译代码前一定要线运行`go fmt`或`goimports`
2. `go fmt`  代码格式化
3. `goimports -l -w .`  增强版的`go fmt`
   1. `-l`将格式不正确的文件打印到控制台
   2. `-w`在原路径修改文件
   3. `.`指定要扫描的文件