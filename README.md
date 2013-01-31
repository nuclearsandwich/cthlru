cthlru
======

*The stupid LRU system man was not meant to know.*

`cthlru <cache name>` - Present a series of cached values with the least
  recently used at the end.

`cthlru <cache name> <value>` - hit a value. It will be added to the cache or
  have its time warmed.

What?
-----

cthlru sets you up with a [Least Recently Used][LRU] cache that you can use in
programs such as dmenu to generate a list of options ordered by recent use.

Why?
----

I was drinking tea and thought it'd be a <strike>horrib</strike> cool thing.

How?
----

At first I did something kind of stupid with `sha1sum` and `ls -ut` it made me
really uncomfortable and I didn't know why. On the bus home I realized I should
just have a history file that has only unique items.

But really, why?
----------------

[dmenu_github][dgh]


[dgh]: https://github.com/nuclearsandwich/homebin/blob/master/dmenu_github


[LRU]: https://en.wikipedia.org/wiki/LRU_cache#Least_Recently_Used
