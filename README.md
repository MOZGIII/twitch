Twitch
======

A tiny wrapper for livestreamer to watch twitch.tv streams.

## Usage

```
$ twitch amazhs
Running stream: http://twitch.tv/amazhs
[cli][info] Found matching plugin twitch for URL http://twitch.tv/amazhs
[cli][info] Available streams: audio, high, low, medium, mobile (worst), source (best)
[cli][info] Opening stream: source (hls)
...
```

## Installation

Install via `pip`:

```
$ (sudo) pip install twitch
```

### Livestreamer setup

Livestreamer will be installed as a dependency, but you have to install other packages that are required for it to work.

Check out their docs for more info: http://docs.livestreamer.io/install.html

You can install `livestreamer` from your OS package manager to automatically install all the dependencies.

In Ubuntu:

```
$ sudo apt-get install livestreamer
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
