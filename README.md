[![Build Status](https://travis-ci.org/bitfurry/goconfig.svg?branch=master)](https://travis-ci.org/bitfurry/goconfig)

# goconfig
--
    import "github.com/gojek-engineering/goconfig"


## Usage


```go
type AppConfig struct {
	goconfig.BaseConfig
}

config := &AppConfig{}
config.Load()
config.GetValue("config_key")
```
