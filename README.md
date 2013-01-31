cthlru
======

*The stupid LRU system man was not meant to know.*

`cthlru <cache name>` - Present a series of cached values with the least
  recently used at the end.

`cthlru <cache name> <value>` - hit a value. It will be added to the cache or
  have its time warmed.


Disclaimer
----------

There's probably a really good reason you should never do this. noatime mounted
partitions is one of them. If I ever care, I may fix that.

