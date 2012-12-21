Multiline String Support In Javascript
======================================

Let's add multiline string support to Javascript! Other scripting languages have it, why not Javascript?

Goal
----

This should work:

    var foobar = "hello
    big
    world"
    console.log(foobar)



Current Workarounds
-------------------

These are ugly:

    var foobar = "hello\n\
    big\n\
    world"
    console.log(foobar)


    var foobar = "hello\n" +
    "big\n" +
    "world"
    console.log(foobar)
