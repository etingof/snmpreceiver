
SNMP Notificaton Receiver
-------------------------

[![PyPI](https://img.shields.io/pypi/v/snmpreceiver.svg?maxAge=2592000)](https://pypi.org/project/snmpreceiver)
[![Python Versions](https://img.shields.io/pypi/pyversions/snmpreceiver.svg)](https://pypi.org/project/snmpreceiver/)
[![Status](https://img.shields.io/pypi/status/snmpreceiver.svg)](https://github.com/etingof/snmpreceiver/)
[![Build status](https://travis-ci.org/etingof/snmpreceiver.svg?branch=master)](https://travis-ci.org/etingof/snmpreceiver)
[![GitHub license](https://img.shields.io/badge/license-BSD-blue.svg)](https://raw.githubusercontent.com/etingof/snmpreceiver/master/LICENSE.txt)

The SNMP Notification Receiver daemon runs one or more SNMP notification
receivers and maintains one or more "sinks" to funnel received notifications
to.

Received SNMP notifications can be routed to one or more synks
for processing via a declarative mini-language.

Features
--------

* SNMPv1/v2c/v3 operations with built-in protocol and transport
  translation capabilities
* SNMPv3 USM supports MD5/SHA/SHA224/SHA256/SHA384/SHA512 auth and
  DES/3DES/AES128/AES192/AES256 privacy crypto algorithms
* Supports SNMP TRAP and INFORM notifications
* Maintains multiple independent SNMP engines, network transports and
  sinks
* Offers versatile SNMP PDU routing towards one or more sinks
* Extension modules supporting SNMP PDU filtering and on-the-fly
  modification
* Works on Linux, Windows and OS X

Download & Install
------------------

SNMP Notification Receiver software is freely available for download from
[PyPI](https://pypi.org/project/snmpreceiver).

Just run:

```bash
$ pip install snmpreceiver
```

Alternatively, you can get it from [GitHub](https://github.com/etingof/snmpreceiver/releases).

How to use SNMP Notification Receiver
-------------------------------------

First you need to configure the tool. It is largely driven by
[configuration files](http://snmplabs.com/snmpreceiver/configuration/index.html)
written in a declarative mini-language. To help you started, we maintain
[a collection](http://snmplabs.com/snmpreceiver/configuration/index.html#examples)
of configuration files designed to serve specific use-cases.

Getting help
------------

If something does not work as expected or we are missing an interesting feature,
[open an issue](https://github.com/etingof/snmpreceiver/issues) at GitHub or
post your question [on Stack Overflow](https://stackoverflow.com/questions/ask).

Finally, your PRs are warmly welcome! ;-)

Copyright (c) 2019, [Ilya Etingof](mailto:etingof@gmail.com). All rights reserved.
