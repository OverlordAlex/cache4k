# cache4k

This is a fork of Cache4k with the following goals:

* add a `getOrNull`
* change behaviour of `get` so that it throws an `ElementNotFoundException` on cache miss
* add a `getOrDefault` that returns a given value on cache miss
* add a `getOrPrevious` that returns a stale cache value if an update fails on miss
