# wiki

Yet another command line interface to a python module: `wikipedia`. Created in 10 minutes for an immediate need.

Usage:

To show the first line of the summary (until the first period)
```
$ wiki "David Bowie"
David Bowie: David Robert Jones (8 January 1947 – 10 January 2016), known professionally as David Bowie (, UK also  BOH-ee), was an English singer-songwriter and actor.
(https://en.wikipedia.org/wiki/David_Bowie)
```

To show the whole summary:
```
$ wiki "David Bowie" --more
David Bowie: David Robert Jones (8 January 1947 – 10 January 2016), known professionally as David Bowie (, UK also  BOH-ee), was an English singer-songwriter and actor. He was a leading figure in the music industry and is regarded as one of the most influential musicians of the 20th century. He was acclaimed by critics and musicians, particularly for his innovative work during the 1970s. His career was marked by reinvention[...]
(https://en.wikipedia.org/wiki/David_Bowie)
```

To show the whole page:
```
wiki "David Bowie" --page
TheWholeWikiPage[...]
```

That's it :D
