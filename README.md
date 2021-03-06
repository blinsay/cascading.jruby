# Cascading.JRuby [![Build Status](https://secure.travis-ci.org/mrwalker/cascading.jruby.png)](http://travis-ci.org/mrwalker/cascading.jruby)

cascading.jruby is a small DSL above [Cascading](http://www.cascading.org/).

It requires Hadoop (>= 0.20.2) and [Cascading 2.0.0](http://files.cascading.org/cascading/2.0/cascading-2.0.0.tgz) to be set via the environment variables: `HADOOP_HOME` and `CASCADING_HOME`

It has been tested on JRuby versions 1.2.0, 1.4.0, 1.5.3, 1.6.5, and 1.6.7.2.

To run cascading.jruby applications on a Hadoop cluster, you must use
[Jading](https://github.com/etsy/jading) to package them into a job jar.
