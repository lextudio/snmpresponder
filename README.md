
SNMP Command Responder
----------------------

[![PyPI](https://img.shields.io/pypi/v/snmpresponder.svg?maxAge=2592000)](https://pypi.org/project/snmpresponder)
[![PyPI Downloads](https://img.shields.io/pypi/dd/snmpresponder)](https://pypi.python.org/pypi/snmpresponder/)
[![Python Versions](https://img.shields.io/pypi/pyversions/snmpresponder.svg)](https://pypi.org/project/snmpresponder/)
[![GitHub license](https://img.shields.io/badge/license-BSD-blue.svg)](https://raw.githubusercontent.com/lextudio/snmpresponder/master/LICENSE.txt)

The SNMP Command Responder daemon runs one or more SNMP agents and maintains
one or more trees of SNMP managed objects (i.e. MIBs). The user can interface
those managed objects with the data they are willing to serve over SNMP.

SNMP requests received by any of the embedded SNMP agents can be routed to
any of the MIB trees for processing via a declarative mini-language.

The use-case for SNMP Command Responder is to serve user data over
SNMP.

Features
--------

* SNMPv1/v2c/v3 operations with built-in protocol and transport translation capabilities
* SNMPv3 USM supports MD5/SHA/SHA224/SHA256/SHA384/SHA512 auth and
  DES/3DES/AES128/AES192/AES256 privacy crypto algorithms
* Maintains multiple independent SNMP engines, network transports and MIB trees
* Discovers `pip`-installable MIB implementations
* Extension modules supporting SNMP PDU filtering and on-the-fly modification
* Works on Linux, Windows and OS X

Download & Install
------------------

SNMP Command Responder software is freely available for download from
[PyPI](https://pypi.org/project/snmpresponder).

Just run:

```bash
$ pip install snmpresponder
```

Alternatively, you can get it from [GitHub](https://github.com/lextudio/snmpresponder/releases).

How to use SNMP Command Responder
---------------------------------

First you need to configure the tool. It is largely driven by
[configuration files](https://www.pysnmp.com/snmpresponder/configuration/index.html)
written in a declarative mini-language. To help you started, we maintain
[a collection](https://www.pysnmp.com/snmpresponder/configuration/index.html#examples)
of configuration files designed to serve specific use-cases.

Getting help
------------

If something does not work as expected or we are missing an interesting feature,
[open an issue](https://github.com/lextudio/pysnmp/issues) at GitHub or
post your question [on Stack Overflow](https://stackoverflow.com/questions/ask).

Finally, your PRs are warmly welcome! ;-)

Copyright (c) 2019, [Ilya Etingof](mailto:etingof@gmail.com).
Copyright (c) 2022, [LeXtudio Inc.](mailto:support@lextudio.com).
All rights reserved.
