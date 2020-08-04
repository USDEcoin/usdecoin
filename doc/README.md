usdecoin Core 1.0.0
=====================

This is the official reference wallet for usdecoin digital currency and comprises the backbone of the usdecoin peer-to-peer network. You can [download usdecoin Core](https://www.usdecoin.org/downloads/) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run usdecoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/usdecoin-qt` (GUI) or
- `bin/usdecoind` (headless)

### Windows

Unpack the files into a directory, and then run usdecoin-qt.exe.

### OS X

Drag usdecoin-Qt to your applications folder, and then run usdecoin-Qt.

### Need Help?

* See the [usdecoin documentation](https://usdecoinpay.atlassian.net/wiki/display/DOC)
for help and more information.
* Ask for help on [#usdecoinpay](http://webchat.freenode.net?channels=usdecoinpay) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=usdecoinpay).
* Ask for help on the [usdecoinTalk](https://usdecointalk.org/) forums.

Building
---------------------
The following are developer notes on how to build usdecoin Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The usdecoin Core repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [usdecoinTalk](https://usdecointalk.org/) forums, in the Development & Technical Discussion board.
* Discuss on [#usdecoinpay](http://webchat.freenode.net/?channels=usdecoinpay) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=usdecoinpay).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
