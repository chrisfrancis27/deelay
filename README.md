If you are looking for deelay ruby gem, you can find it [here](https://github.com/biesiad/deelay-ruby).

# [Deelay.me](http://deelay.me)

**Inline delay proxy for http resources**

Slow loading resources (images, scripts, etc) can break your code. Test it simulating unexpected network conditions applied to specific resource.


## Installation
```sh
$ npm install -g deelay
```

## Usage
```sh
$ deelay
Starting delay on port 4567
```

or with port environment variable

```sh
$ PORT=8080 deelay
Starting delay on port 8080
```

```html
<img src="localhost:4567/1000/http://mysite.com/image.gif">
```

## Development

### Tests
```sh
npm install
npm test
```
