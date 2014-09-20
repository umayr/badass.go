
Badass
=======

A tiny script that can make you look *badass* on github


Instructions
----

```sh
# Move to any repo you want to generate commits on
$ cd path/to/repo
$ go get github.com/umayr/badass
$ go build github.com/umayr/badass
$ chmod +x badass
$ badass --date 02/21/2013 --seed 50
...
$ git push origin master

```

Later you can remove the bin or whatevs.


Version
----

0.2

Flags
-----

Badass takes various flags as input

* **--saturation, -s** : Higher the value of seeds, higher the saturations of commits. *Default: 72*
* **--columns, -c** - Denotes one column of contribution graph. *Default: 81*
* **--date, -d** - Start date for commits *Default: 1 Year*
* **--max-commits, -m** - Maximum commits per day *Default: 74*


License
----

MIT

Contact
-----

Twitter: [@Bandooqwala](https://twitter.com/Bandooqwala)

