.. image:: https://api.cirrus-ci.com/github/spesmilo/electrumx.svg?branch=master
    :target: https://cirrus-ci.com/github/spesmilo/electrumx
.. image:: https://coveralls.io/repos/github/spesmilo/electrumx/badge.svg
    :target: https://coveralls.io/github/spesmilo/electrumx

=========================================
Electrum-ADA - Electrum Wallet for ADA
=========================================

:Licence: MIT
:Language: Python (>= 3.8)
:Original Author: Neil Booth

Electrum Wallet for ADA version 3.3.8
=====================================

Download
========

You can download the latest version from the links below:

- `Windows <https://github.com/Electrum-Cardano/electrum-ada/releases/download/v3.3.8/electrum-ada-3.3.8-setup.exe>`_
- `macOS <https://github.com/Electrum-Cardano/electrum-ada/releases/download/v3.3.8/electrum-ada-3.3.8.dmg>`_
- `Linux <https://github.com/Electrum-Cardano/electrum-ada/releases/download/v3.3.8/electrum-ada-3.3.8-x86_64.AppImage>`_

Description
===========

Electrum-ADA is a secure and user-friendly wallet for managing your ADA tokens. Supports Windows, macOS, and Linux.

This project is a fork of `kyuupichan/electrumx <https://github.com/kyuupichan/electrumx>`_. The original author dropped support for Bitcoin, which we intend to keep.

Electrum-ADA allows users to run their own Electrum server. It connects to your full node and indexes the blockchain, allowing efficient querying of the history of arbitrary addresses. The server can be exposed publicly, and joined to the public network of servers via peer discovery. As of May 2020, a significant chunk of the public Electrum server network runs ElectrumX.

Installation
============

Windows
-------

1. Download the `electrum-ada-3.3.8-setup.exe <https://github.com/Electrum-Cardano/electrum-ada/releases/download/v3.3.8/electrum-ada-3.3.8-setup.exe>`_ file.
2. Run the installer and follow the instructions.

macOS
-----

1. Download the `electrum-ada-3.3.8.dmg <https://github.com/Electrum-Cardano/electrum-ada/releases/download/v3.3.8/electrum-ada-3.3.8.dmg>`_ file.
2. Open the file and drag the application to the `Applications` folder.

Linux
-----

1. Download the `electrum-ada-3.3.8-x86_64.AppImage <https://github.com/Electrum-Cardano/electrum-ada/releases/download/v3.3.8/electrum-ada-3.3.8-x86_64.AppImage>`_ file.
2. Make the file executable: open a terminal and run ``chmod +x electrum-ada-3.3.8-x86_64.AppImage``.
3. Run the application by double-clicking the file or via the terminal.

Documentation
=============

See `readthedocs <https://electrumx-spesmilo.readthedocs.io/>`_ for more information.

License
=======

This project is licensed under the MIT License. See the `LICENSE <LICENSE>`_ file for details.
