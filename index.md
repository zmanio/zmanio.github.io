---
layout: home
title: projects
description: "Software for eating the world."
headline: software for eating the world
tags: [software, projects, scala]
---

I write a lot of software, some of it makes its way here where it's available [for free](https://www.apache.org/licenses/LICENSE-2.0.html).

## [atmos](/atmos/) - <small>minimalist retry-on-failure behavior for scala</small>

A [Scala](http://www.scala-lang.org/) library for describing retry-on-failure behavior using a concise, literate [embedded DSL](http://c2.com/cgi/wiki?EmbeddedDomainSpecificLanguage).

## [rummage](/rummage/) - <small>one-off scala utilities and tools</small>

A [Scala](http://www.scala-lang.org/) library that contains utilities that are too small and general to warrant their own package and/or artifact, but are too large, nuanced or handy to have around to be re-implemented over and over again.

The project currently contains only a flexible timer abstraction for scheduling delayed and repeating tasks. 

## [sbt-ghreadme](/sbt-ghreadme/) - <small>use github readme files in your sbt-site</small>

A [SBT](http://www.scala-sbt.org/) plugin that extends [sbt-site](https://github.com/sbt/sbt-site) by prepending YAML front matter to your github-style README files and including them in the generated site. This allows you to use the same documentation in multiple contexts without any manual duplication.
