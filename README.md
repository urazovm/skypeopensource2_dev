# skypeopensource2

First in world selfmade client to Skype Network based on reversing original Skype 5.5 client.

For now, only message receive and sending.

Try to compile it (with Visual Studio 2010) and test by youself or use already compiled binaries.

License:
LGPL 3.0 

Commercial license also avaiable on request.

Links:

Protocol brief overview: 
http://skype-open-source2.blogspot.ru/2016/06/skype-protocol-dumps.html

Release post: 
http://skype-open-source2.blogspot.ru/2016/09/first-in-world-skype-network-compatible.html

Binaries:
http://epycs.ru/files/EpycsMessenger2_20160901.zip
http://yadi.sk/d/xvKhmImdugThn

Sources (same as on github here):
http://epycs.ru/files/EpycsMessenger2_20160901_src.zip
http://yadi.sk/d/V_IWJT-fugvND


Add (04.09.2016):

ISSUE by @bugaevc

The README should clearly state:
*  whether or not this client is a complete **re-implementation**
* whether or not it includes **disassembled** code from the other Skype clients
* whether or not it is a **clean-room reverse-engineered** code, like Wine/ReactOS
* why the specified **license is valid** and legal to use for the project
* what are the **legal complications**, if any, to developing the project and to using it personally or commercially

REPLY ON ISSUE

> whether or not this client is a complete re-implementation

Yes. Its complete re-implementation of proprietary Skype Network protocol.

> whether or not it includes disassembled code from the other Skype clients

Well, may be a little :) unpack-4142.c and pack-4142.c is HexRays decompiled code. And should be rewrited... But i dont have time for this now.

> whether or not it is a clean-room reverse-engineered code, like Wine/ReactOS

No. Not clean room, not chinese wall.

> why the specified license is valid and legal to use for the project

Its my own code, i write it, i am the author of most code. And hold all copyrights rights.

Well, except some login pieces (skyauth3/skype_login.c) which copyrighted by Sean O'Neil from [VEST Corporation](https://en.wikipedia.org/wiki/VEST) in 2009.

> what are the legal complications, if any, to developing the project and to using it personally or commercially

1) The pack-4142.c/unpack41-42.c mentioned above. 
2) Also, it contain MIRACL for RSA and big numbers multiply arithmetics. 

> MIRACL Cryptographic SDK: Multiprecision Integer and Rational Arithmetic Cryptographic Library is a C software library that is widely regarded by developers as the gold standard open source SDK for elliptic curve cryptography (ECC). http://miracl.com https://github.com/miracl/MIRACL

For commercial usage and license bring me email to: skypeopensource@gmail.com
