Node-Webkit-Test
================

Trying out Node-Webkit

Download node-webkit for your [platform](https://github.com/rogerwang/node-webkit)

Run QuickStart

```
$ /path/to/nw QuickStart/.
```

Run diskDBApp

```
$ cd diskDBApp
$ npm install
$ /path/to/nw .
```

Creating the mytest.bin file was done by following the steps outlined in [Protect JAvaScript source code with the v8 snapshot](https://github.com/rogerwang/node-webkit/wiki/Protect-JavaScript-source-code-with-v8-snapshot)

```
# nwsnapshot is in the same dir as nw
$ /path/to/nwsnapshot --extra_code mytest.js mytest.bin
```

