Ducats - Money without banks
====================

Ducats Payments is the future of online money at your fingertips. 
Only a wallet and internet connection is required to send and receive money. 
Ducats is a decentralised currency without the need for banks.

Read more at [DucPay.com](http://ducpay.com/).

Specifications
---------------------
- Cryptography: secure mixed hashing
- Mining: CPU
- Premine: No
- Block generation: 3 minutes
- Block reward: dynamic, 1000 coin per block maximum
- Block confirmations: 40
- Difficulty: retargets every 15 minutes
- Maximum available coins: 50,000,000

Mining Ducats
---------------------
Please open network port 25857 on your router to connect.

Use the following configuration file named "Ducats.conf" and place it in your application directory:

<pre><code>rpcuser=username
rpcpassword=password
rpcport=25858
addnode=95.85.53.161
daemon=1
server=1
gen=1
</code></pre>

Other Pages
---------------------
- [Unix Build Notes](build-unix.md)
- [OSX Build Notes](build-osx.md)
- [Windows Build Notes](build-msw.md)
- [Coding Guidelines](coding.md)
- [Release Process](release-process.md)
- [Release Notes](release-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Unit Tests](unit-tests.md)
- [Translation Process](translation_process.md)

Copyright
---------------------
Copyright (c) 2009-2013 Bitcoin Developers
Copyright (c) 2013 Ducats Developers

Distributed under the MIT/X11 software license, see the accompanying
file COPYING or http://www.opensource.org/licenses/mit-license.php.
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](http://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), UPnP software written by Thomas Bernard and
sphlib 3.0 by Thomas Pornin.