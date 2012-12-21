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



Update
------

So thanks to AviMarcus for the tip. Template literals, part of ES6, will allow you to do this using backticks:

    var foobar = `hello
    big
    world`

See discussion here: http://www.nczonline.net/blog/2012/08/01/a-critical-review-of-ecmascript-6-quasi-literals/

And read template literals in the spec:

http://wiki.ecmascript.org/lib/exe/fetch.php?id=harmony%3Aspecification_drafts&cache=cache&media=harmony:working_draft_ecma-262_edition_6_11-22-12-nomarkup.pdf


