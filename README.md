result of using different module name and repo:
```
$ go get github.com/b10s/test-go-mod
go: finding github.com/b10s/test-go-mod latest
go: downloading github.com/b10s/test-go-mod v0.0.0-20200324025940-fae74c66aa4b
go: extracting github.com/b10s/test-go-mod v0.0.0-20200324025940-fae74c66aa4b
go get: github.com/b10s/test-go-mod@v0.0.0-20200324025940-fae74c66aa4b: parsing go.mod:
        module declares its path as: github.com/b10s/foo-bar-baz
                but was required as: github.com/b10s/test-go-mod
```
