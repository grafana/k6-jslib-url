# k6-jslib-url

k6-jslib-url including core-js@3 URL and URLSearchParams web APIs.

## Usage

This jslib can be used in the context of k6 scripts by importing it from its [jslib.k6.io](https://jslib.k6.io/url/1.0.0/index.js) url directly: 

```js
import { URL, URLSearchParams } from "https://jslib.k6.io/url/1.0.0/index.js";
```

## APIs

### URL
```js
// Constructor
URL()

// Properties
hash
host
hostname
href
origin
password
pathname
port
protocol
search
searchParams
username

// Methods
toString()
toJSON()
```

### URLSearchParams

```js
// Constructor
URLSearchParams()

//Methods
append()
delete()
entries()
forEach()
get()
getAll()
has()
keys()
set()
sort()
toString()
values()
```