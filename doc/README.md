Horrorcoin Core 0.10.2
=====================

Setup
---------------------
[Horrorcoin Core](http://Horrorcoin.org/en/download) is the original Horrorcoin client and it builds the backbone of the network. However, it downloads and stores the entire history of Horrorcoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once. If you would like the process to go faster you can [download the blockchain directly](bootstrap.md).

Running
---------------------
The following are some helpful notes on how to run Horrorcoin on your native platform. 

### Unix

You need the Qt4 run-time libraries to run Horrorcoin-Qt. On Debian or Ubuntu:

	sudo apt-get install libqtgui4

Unpack the files into a directory and run:

- bin/32/Horrorcoin-qt (GUI, 32-bit) or bin/32/Horrorcoind (headless, 32-bit)
- bin/64/Horrorcoin-qt (GUI, 64-bit) or bin/64/Horrorcoind (headless, 64-bit)



### Windows

Unpack the files into a directory, and then run Horrorcoin-qt.exe.

### OSX

Drag Horrorcoin-Qt to your applications folder, and then run Horrorcoin-Qt.

### Need Help?

* See the documentation at the [Horrorcoin Wiki](https://en.Horrorcoin.it/wiki/Main_Page)
for help and more information.
* Ask for help on [#Horrorcoin](http://webchat.freenode.net?channels=Horrorcoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=Horrorcoin).
* Ask for help on the [HorrorcoinTalk](https://Horrorcointalk.org/) forums, in the [Technical Support board](https://Horrorcointalk.org/index.php?board=4.0).

Building
---------------------
The following are developer notes on how to build Horrorcoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)

Development
---------------------
The Horrorcoin repo's [root README](https://github.com/Horrorcoin/Horrorcoin/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Coding Guidelines](coding.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/Horrorcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)

### Resources
* Discuss on the [HorrorcoinTalk](https://Horrorcointalk.org/) forums, in the [Development & Technical Discussion board](https://Horrorcointalk.org/index.php?board=6.0).
* Discuss on [#Horrorcoin-dev](http://webchat.freenode.net/?channels=Horrorcoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=Horrorcoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
