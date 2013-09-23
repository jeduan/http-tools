http-tools
=========

Frequently used methods dealing with HTTP connections

postbody
-------
Will generate an urlencoded body string

```lua
local httptools = require 'vendor.httptools.httptools'

httptools.postBody{
	foo = bar
}
```


urlencode
------

```lua
local httptools = require 'vendor.httptools.httptools'

httptools.urlencode()
```