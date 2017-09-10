# sonosthesia-website

The Sonosthesia website powered by Harp and Bootstrap


First make sure you have Harp installed:

```sh
$ sudo npm install -g harp
```

Then run Harp server in the harp directory, to live rebuild

```sh
$ cd ./harp
$ harp server
```

Or compile into a standalone build which you can just drop in a static HTTP server:

```sh
$ cd sonosthesia-website
$ mkdir build
$ harp compile ./harp ./build
```