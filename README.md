# unheic

*Simple bash script for adjusting the system volume on macOS.*


## Setup

Copy the `vol` executable to any location on your [`PATH`](https://en.wikipedia.org/wiki/PATH_(variable)).


## Usage

Run it without any arguments to find out:

```
$ vol
usage: vol [-h | --help | NUMBER_FROM_0_TO_100 | -DECREMENT | +INCREMENT]
```

Some examples:

```
$ vol
26
$ vol 0
26 -> 0 (muted)
$ vol 30
0 -> 30
$ vol +15
30 -> 45
$ vol -3
45 -> 42
```
