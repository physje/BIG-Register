BIG Registration Utils

A quick, hacked up connector to the Dutch government's  [BIG-register system](https://www.bigregister.nl/zoeken/zoeken_eigen_systeem/), an online list of health care professionals. This is a proof-of-concept. Mostly.

NuSOAP is used because the BIG-Register system triggers a particular issue in PHP's native SOAPClient, [causing many headaches](https://bugs.php.net/bug.php?id=60842). A bundled copy of NuSOAP is included.

NuSOAP is licensed under LGPL.
All other code is licensed as MIT.
