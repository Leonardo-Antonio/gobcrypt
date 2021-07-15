# GoBcrypt

![image](/logo.png)

### Install 

```go
go get github.com/Leonardo-Antonio/gobcrypt
```

### How to use

> se recomienda usar como key de un .env por seguridad


- ***Generate Key***
   ```go
    key := gobcrypt.CreateHash(<youPassword>)
  ```

- ***Encrypt Data***
   ```go
    encrypt, err := gobcrypt.Encrypt(<youData>, key)
  ```

- ***Decrypt Data***
   ```go
    decrypt, err := gobcrypt.Decrypt(<encodedData>, key)
  ```
