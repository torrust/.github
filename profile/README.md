# Welcome to the GitHub of the Torrust Project.

**Torrust** is a community supported project that currently is sponsored by [Nautilus Cyberneering][nautilus].

## Torrust

**"Tor-rust"** is a play on the words "Bit-***Tor***-ent", and "***Rust***"

This summaries our focus on mixing the great [BitTorrent Protocol][bittorrent] with the excellent [Rust Programming Language][Rust].

We strive to grow a fantastic, kind, and passionate community. [__New contributors are always welcome to join__]((https://github.com/torrust/.github/blob/main/info/contributing.md)!

> For more information, please consider visiting our website: __<https://torrust.com/>__.

## Repositories

Our focus is on two parts of BitTorrent Infrastructure, the **Tracker**, and the **Index**:

### Tracker

Our *BitTorrent Tracker* is a conventional tracker written in rust. When hosted it can matchmaking and statistic keeping capabilities to the BitTorrent Network.

 - [__torrust-tracker__ (Torrent Tracker)][tracker]

### Index

Our *BitTorrent Index* is a conventional torrent metadata index. When hosted it can provide the BitTorrent Community with a collaborative interface for building databases of torrent information, and monitoring of it's related torrent swarms.

We split the index into to parts: *"The Index"*, and *"The Index Graphical User Interface (GUI)"*:

#### "The Index"
The index is a set of software that provides a set of machine API's that allow the management and maintenance of community collections of torrents

 - [__torrust-index__ (Torrust Index)][index]

> Note: This software provides an interfaces for other programers. Not end-users.

#### "The Index GUI"
This software connects to the index (and other services), to provide a nice web-interface for humans to use.

 - [__torrust-index-gui__ (Torrust Index GUI)][gui]


[nautilus]: https://github.com/orgs/Nautilus-Cyberneering/
[bittorrent]: http://bittorrent.org/
[rust]: https://www.rust-lang.org/

[tracker]: https://github.com/torrust/torrust-tracker
[index]: https://github.com/torrust/torrust-index
[gui]: https://github.com/torrust/torrust-index-gui
