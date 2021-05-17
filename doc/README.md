Tushcoin Core 0.14.2
=====================

Setup
---------------------
Tushcoin Core is the original Tushcoin client and it builds the backbone of the network. However, it downloads and stores the entire history of Tushcoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Tushcoin Core, visit [tushcoin.org](https://tushcoin.org).

Running
---------------------
The following are some helpful notes on how to run Tushcoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/tushcoin-qt` (GUI) or
- `bin/tushcoind` (headless)

### Windows

Unpack the files into a directory, and then run tushcoin-qt.exe.

### OS X

Drag Tushcoin-Core to your applications folder, and then run Tushcoin-Core.

### Need Help?

* See the documentation at the [Tushcoin Wiki](https://tushcoin.info/)
for help and more information.
* Ask for help on [#tushcoin](http://webchat.freenode.net?channels=tushcoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=tushcoin).
* Ask for help on the [TushcoinTalk](https://tushcointalk.io/) forums.

Building
---------------------
The following are developer notes on how to build Tushcoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Tushcoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/tushcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [TushcoinTalk](https://tushcointalk.io/) forums.
* Discuss general Tushcoin development on #tushcoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=tushcoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
