# Descripiton
safe-env is a golang lib for getting environment variable by passing default value to it if env value doesn't exist.


# Installation

```
go get github.com/LyhengTep/safe-env
```

# Usage
```
import "github.com/LyhengTep/safe-env"


func main() {
	env.Get("HOME","/user/home")
}

```
