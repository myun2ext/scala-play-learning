# Scala/Play Learning

## Installation

Recommended **Activator**.

* https://www.playframework.com/download

## HTML Template Engine

Slim like HTML template engine **Jade**.

* http://jade-lang.com/

```
doctype html
html(lang="en")
  head
    title= pageTitle
    script(type='text/javascript').
      if (foo) {
         bar(1 + 5)
      }
  body
    h1 Jade - node template engine
    #container.col
      if youAreUsingJade
        p You are amazing
      else
        p Get on it!
      p.
        Jade is a terse and simple
        templating language with a
        strong focus on performance
        and powerful features.
```
