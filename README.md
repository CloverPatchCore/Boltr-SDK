
![Surface Core](https://github.com/boltrswap/Boltr-Swap-SDK/blob/main/boltrGITSDK.jpg) 



SurfaceOS 1.0 Introduction
=====================================

**Well designed and created by Ismail Abinting & Alex Kim [2020]**

[Ismail Abinting](https://t.me/ismailabintig)

SurfaceOS is a core system behind a cryptocurrency exchange for


### Surface Mission

Our mission is to build the world best cryptocurrency exchange with a high performance trading engine and safety which can be trusted and enjoyed by users. Additionally we want to move the cryptocurrency exchange technology forward by providing support and add new features. 


SECURITY KNOWLEDGE IS A REQUIREMENT.

Surface cannot protect your customers when you leave your admin password 1234567, or open sensitive ports to public internet. No one can. Running an exchange is a very risky task because you're dealing with money directly. If you don't known how to make your exchange secure, hire an expert.

You must know what you're doing, there's no shortcut. Please get prepared before continue:

* Rails knowledge
* Security knowledge
* System administration


### Features

* Designed as high performance crypto currency exchange.
* Built-in high performance matching-engine.
* Built-in [Proof of Solvency](https://iwilcox.me.uk/2014/proving-bitcoin-reserves) Audit.
* Usability and scalibility.
* Websocket API and high frequency trading support.
* Support multiple digital currencies (eg. Bitcoin, Litecoin, Dogecoin etc.).
* Easy customization of payment processing for both fiat and digital currencies.
* SMS and Google Two-Factor authenticaton.
* [KYC Verification](http://en.wikipedia.org/wiki/Know_your_customer).
* Powerful admin dashboard and management tools.
* Highly configurable and extendable.
* Industry standard security out of box.



### Client who use our SurfaceOS

* [Bitvast.com](https://www.bitvast.com) - The world's premier Bitcoin Exchange
* [MarsX.io](https://acx.io) - Australian Cryptocurrency Exchange

### Mobile Apps ###

* [Boilr](https://github.com/andrefbsantos/boilr) - Cryptocurrency and bullion price alarms for Android

### Requirements

* Linux / Mac OSX
* Ruby 2.1.0
* Rails 4.0+
* Git 1.7.10+
* Redis 2.0+
* MySQL
* RabbitMQ

** More details are in the [doc](doc).


### Getting started

* [Setup on Mac OS X](doc/setup-local-osx.md)
* [Setup on Ubuntu](doc/setup-local-ubuntu.md)
* [Deploy production server](doc/deploy-production-server.md)

### API

You can interact with Peatio through API:

* [API v2](http://demo.peat.io/documents/api_v2?lang=en)
* [Websocket API](http://demo.peat.io/documents/websocket_api)

Here're some API clients and/or wrappers:

* [SurfaceOS-client-ruby](https://github.com/peatio/peatio-client-ruby) is the official ruby client of both HTTP/Websocket API.
* [SurfaceOS-client-python by JohnnyZhao](https://github.com/JohnnyZhao/peatio-client-python) is a python client written by JohnnyZhao.
* [SurfaceOS-client-python by czheo](https://github.com/JohnnyZhao/peatio-client-python) is a python wrapper similar to peatio-client-ruby written by czheo.
* [SurfaceOSJavaClient](https://github.com/classic1999/peatioJavaClient.git) is a java client written by classic1999.
* [SurfaceOS-client-php](https://github.com/panlilu/yunbi-client-php) is a php client written by panlilu.

### Custom Style

SurfaceOS front-end based Bootstrap 3.0 version and Sass, and you can custom exchange style for your mind.

* change bootstrap default variables in `vars/_bootstrap.css.scss`
* change SurfaceOS custom default variables in `vars/_basic.css.scss`
* add your custom variables in `vars/_custom.css.scss`
* add your custom css style in `layouts/_custom.css.scss`
* add or change features style in `features/_xyz.css.scss'

`vars/_custom.css.scss` can overwrite `vars/_basic.css.scss` defined variables
`layout/_custom.css.scss` can overwrite `layout/_basic.css.scss` and `layoputs/_header.css.scss` style
