# 環境構築

## APP

### FRONT

### API

コンテナーの初回起動時に内部で以下コマンドを実行し、モジュールをimportする

```bash
go get github.com/gin-gonic/gin
go get gorm.io/gorm
go get github.com/go-sql-driver/mysql
go get gorm.io/driver/mysql
go install github.com/x-motemen/gore/cmd/gore@latest
go get github.com/go-delve/delve/cmd/dlv@latest 
go get github.com/stretchr/testify
```

### DB

