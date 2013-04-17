libmagic-universal
==================

Libmagic universal binaries.  Useful if you need to sometimes run against 32 bit.

I somehow built universal libmagic binaries, but didn't document what I did and haven't been able to build them again.  This project is essentially a backup of those binaries.  Occasionally I need to run my python setup in 32 bit (oracle sucks).  Beacause of this I need libmagic to work in 32 bit.  The default brew install of libmagic just builds the 64 bit version.  These universal binaries solve that problem.

Installation
------------
After brew installing libmagic, simply copy the content of the libmagic folder in this repo to /usr/local/lib
