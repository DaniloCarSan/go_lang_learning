## Go hello world

Learning Go

**Run go**
`````
cd project_name
go run .
`````

**Iniciar um novo modulo em go**
````
go mod init example.com/hello
````

**Fazer o link da dependencia de um modulo hospedado localmente**
````
go mod edit -replace example.com/greetings=../greetings
````

**sincronizar as dependências de módulo, adicionando aquelas exigidas pelo código, mas ainda não rastreadas no módulo.**

````
go mod tidy
````