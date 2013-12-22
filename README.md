node-histo-server
=================

TCP server for streaming data to a histogram

## install

```sh
$ npm install histo-server -g
```

## usage

`histo-server(1)` defaults to using port `5000`. It can be overloaded by
defining the `PORT` environment variable. See the example below.

```sh
$ histo-server <TITLE>
```

## example

```sh
$ PORT=3000 histo-server "Title of my histogram"
```

Will yield an empty histo with a title:

```
 0 ․

 0 ․

 0 ․

 0 ․

 0 ․

 0 ․
       ․ ․ ․ ․ ․ ․ ․ ․ ․ ․ ․ ․ ․ ․ ․ 

   Title of my histogram (port='3000')
```

## license

MIT
