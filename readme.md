<p align="center">Valet Gentoo</p>

<p align="center">
<a href="https://packagist.org/packages/drewwalton19216801/valet-gentoo"><img src="https://poser.pugx.org/drewwalton19216801/valet-gentoo/downloads.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/drewwalton19216801/valet-gentoo"><img src="https://poser.pugx.org/drewwalton19216801/valet-gentoo/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/drewwalton19216801/valet-gentoo"><img src="https://poser.pugx.org/drewwalton19216801/valet-gentoo/v/unstable.svg" alt="Latest Unstable Version"></a>
<a href="https://packagist.org/packages/drewwalton19216801/valet-gentoo"><img src="https://poser.pugx.org/drewwalton19216801/valet-gentoo/license.svg" alt="License"></a>
</p>

## Introduction

Valet *Gentoo* is a Laravel development environment for Gentoo Linux minimalists. No Vagrant, no `/etc/hosts` file. You can even share your sites publicly using local tunnels. _Yeah, we like it too._

Valet *Gentoo* configures your system to always run Nginx in the background when your machine starts. Then, using [DnsMasq](https://en.wikipedia.org/wiki/Dnsmasq), Valet proxies all requests on the `*.test` domain to point to sites installed on your local machine.

In other words, a blazing fast Laravel development environment that uses roughly 7mb of RAM. Valet *Gentoo* isn't a complete replacement for Vagrant or Homestead, but provides a great alternative if you want flexible basics, prefer extreme speed, or are working on a machine with a limited amount of RAM.

## Official Documentation

Documentation for Valet can be found on the [Valet Gentoo website](https://drewwalton19216801.github.io/valet-gentoo-docs/).

## License

Laravel Valet is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
