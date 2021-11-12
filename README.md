# MyWebAPI

列出所有的 builder
```gherkin=
pack builder inspect 
```

.net core WebAPI 例子
```gherkin=
git clone https://github.com/ChunPingWang/MyWebAPI.git
```

Building Docker Image 
```gherkin=
pack build my-web-api --path MyWebAPI --builder paketobuildpacks/builder:base --trust-builder
```
