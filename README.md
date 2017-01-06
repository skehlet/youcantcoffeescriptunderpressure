# You Can't JavaScript Under Pressure

This is just a small tweak to @shovon's You Can't CoffeeScript Under Pressure, which I switched back to accepting Javascript.

Previous README:

A CoffeeScript version of [Us Vs Th3m](https://www.facebook.com/Usvsth3m)'s ["You Can't JavaScript Under Pressure"](http://toys.usvsth3m.com/javascript-under-pressure/).

## Running

Just be sure to install [Harp](http://harpjs.com/), and then run

```shell
$ harp server
```

And you should be able to see the app on [http://localhost:9000](http://localhost:9000).

## Building the static site

Run

```shell
harp compile -o docs
```

to generate the docs. Set your repo to serve github pages out of the master branch and /docs and you should be good.
