This a sub-repo of [Neard project](https://github.com/crazy-max/neard) involving Webgrind app bundles.

## Installation

* Download and install [Neard](https://github.com/crazy-max/neard).
* If you already have installed Neard, stop it.
* Download [a Webgrind bundle](#download).
* Extract archive in `neard\apps\webgrind\`. Directory structure example :

```
[-] neard
 | [-] apps
 |  | [-] webgrind 
 |  |  | [-] webgrind1.0
 |  |     | neard.conf
 |  |  | [-] webgrind1.1
 |  |     | neard.conf
```

* Edit the `neard.conf` file and replace the key `webgrindVersion` with the correct version. (eg. `webgrindVersion="1.0"`)
* Edit the `alias/webgrind.conf` file and replace the lines with the correct version. (Not necessary since Neard 1.0.18)
* Start Neard.

## Download

![](https://raw.github.com/crazy-max/neard-app-webgrind/master/img/star-20160403.png) : Default bundle on Neard.

|                  | Webgrind release date | Neard release | Download |
| -----------------|:---------------------:|:-------------:|:--------:|
| **Webgrind 1.0** ![](https://raw.github.com/crazy-max/neard-app-webgrind/master/img/star-20160403.png) | 2009/02/20 | [r1](https://github.com/crazy-max/neard-app-webgrind/releases/tag/r1) | [neard-webgrind-1.0-r1.zip](https://github.com/crazy-max/neard-app-webgrind/releases/download/r1/neard-webgrind-1.0-r1.zip) |
| **Webgrind 1.1** | 2015/03/23 | [r2](https://github.com/crazy-max/neard-app-webgrind/releases/tag/r2) | [neard-webgrind-1.1-r2.zip](https://github.com/crazy-max/neard-app-webgrind/releases/download/r2/neard-webgrind-1.1-r2.zip) |

## Sources

* https://github.com/jokkedk/webgrind

## Contribute

If you want to contribute to this bundle and create new bundles, you have to download [neard-dev](https://github.com/crazy-max/neard-dev) in the parent folder of the bundle.
Directory structure example :

```
[-] neard-dev
 | [-] build
 |  |  | build-commons.xml 
[-] neard-app-webgrind
 |  | build.xml
```

To create a new bundle :
* Do not forget to increment the `build.release` in the `build.properties` file.
* If you want you can change the `build.path` (default `C:\neard-build`).
* Open a command prompt in your bundle folder and call the Ant target `release` : `ant release`.
* Upload your release on a file hosting system like [Sendspace](https://www.sendspace.com/).
* Create an [issue on Neard repository](https://github.com/crazy-max/neard/issues) to integrate your release.

## Issues

Issues must be reported on [Neard repository](https://github.com/crazy-max/neard/issues).<br />
Please read [Found a bug?](https://github.com/crazy-max/neard#found-a-bug) section before reporting an issue.
