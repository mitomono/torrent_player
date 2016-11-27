# Torrent Player

This is a little project that allow you to play music, you need to load the torrents that you want to listen, cause some content can be ilegal.

Once you add the torrents you can listen all the music via streaming, free and with no ads.


## Future of this project

In the future the UI will be more complete with info about the artist. And probably allow to play video.


## Disclaimer

I'm not responsable of bad or ilegal use of this application.

## Thanks to:

[Feross Aboukhadijeh](https://github.com/feross) for his incredible [webtorrent API](https://github.com/feross/webtorrent/blob/master/docs/api.md) and help via email and issues.

[OSL UGR](http://osl.ugr.es/) members for so much help and specially to [JJ Merelo](https://github.com/JJ) for motivates me to open the code before it was ready and makes possible to make an amazing work in electron hackaton makes by OSL.

Thanks so much also to other members that help me, I can't name them all. His names will be in the [Contributor's page](https://github.com/rafaelleru/torrent_player/network/members).

## Instalation

clone and run  ``npm i`` and then ``npm start``.

### Install dependencies

```
$ npm install
```

### Run app

```
$ npm start
```

### Package app

Builds app binaries for OS X, Linux, and Windows.

```
$ npm run package
```

To build for one platform:

```
$ npm run package -- [platform] [package-type]
```

Where `[platform]` is `darwin`, `linux`, or `win32`

and `[package-type]` is `all` (default), `deb` or `zip` (`linux` platform only)

#### Windows build notes

To package the Windows app from non-Windows platforms, [Wine](https://www.winehq.org/) needs
to be installed.

On OS X, first install [XQuartz](http://www.xquartz.org/), then run:

```
brew install wine
```

(Requires the [Homebrew](http://brew.sh/) package manager.)