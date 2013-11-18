# Solar Dial

> Solar Dial is a helper for timing with Software Transactional Memory
> in Haskell.

The core data structure is a [delta queue][] (or list),
which can take anything that implements `Num` and `Ord`.


[delta queue]: http://everything2.com/title/delta+list