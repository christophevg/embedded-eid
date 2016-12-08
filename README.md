# Embedded eID
An experiment to implement a minimalistic embedded library to read (Belgian) eID smart cards.  
Christophe VG <contact@christophe.vg>

## Introduction

This repository holds all information, designs and software collected while investigating the possibility to access a (Belgian) eID smart card from an embedded system, e.g. an Arduino,...

This means we don't have access to a full-blown card-reader, like [ACR38U](http://www.acs.com.hk/en/products/199/acr38u-i1-smart-card-reader/) or the likes, nor a PC or Mac to run some bloated Java-based middleware/runtime/... on top of some OS-based smart card driver infrastructure and so on.

The fact that it took me more than a few hours to find some basic protocol information on how to access it, proves the bad state of affaires. Soon, I hope, this repository will show that it doesn't have to be this way, and that accessing (Belgian) eID smart cards is simple and can be done in a fully transparant way. We'll see ;-)

## First Steps: Finding Information/Existing Work

* [https://github.com/Fedict/eid-mw](https://github.com/Fedict/eid-mw) - Home of the eID Middleware
* [https://sourceforge.net/projects/arduinosclib/](https://sourceforge.net/projects/arduinosclib/) - Actively maintained Arduino Smart Card access library
* [https://www.makomk.com/2011/02/25/iso-7816-smartcard-interface-for-arduino/](https://www.makomk.com/2011/02/25/iso-7816-smartcard-interface-for-arduino/) - An Arduino Sketch to access ISO-7816-based smart cards
* [https://www.foo.be/eID/opensc-belgium/](https://www.foo.be/eID/opensc-belgium/) - Older information, back from in the days when the information was much more straightforward and transparant.
* [http://homes.esat.kuleuven.be/~decockd/site/EidCards/belpic/mySlides/belgian.eid.card.technical.overview.pdf](http://homes.esat.kuleuven.be/~decockd/site/EidCards/belpic/mySlides/belgian.eid.card.technical.overview.pdf) - A presentation giving a holistic overview and some technical information.
* [https://en.wikipedia.org/wiki/ISO/IEC_7816](https://en.wikipedia.org/wiki/ISO/IEC_7816) - Wikipedia page on the ISO-7816 specification
* [https://www.maximintegrated.com/en/app-notes/index.mvp/id/4029](https://www.maximintegrated.com/en/app-notes/index.mvp/id/4029) - Detailed application note on low-level access methods to smart cards

## Project Status

Reading, learning,... :-)

To be continued...

