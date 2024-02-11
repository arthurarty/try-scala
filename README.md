## sbt project compiled with Scala 3

### Usage

This is a normal sbt project. You can compile code with `sbt compile`, run it with `sbt run`, and `sbt console` will start a Scala 3 REPL.

For more information on the sbt-dotty plugin, see the
[scala3-example-project](https://github.com/scala/scala3-example-project/blob/main/README.md).

## Linting
How to run the linter. This requires `scalastyle` to be part of your path.  
Check documentation to install. [Click](http://www.scalastyle.org/command-line.html)
```
scalastyle -c scalastyle-config.xml src
```
