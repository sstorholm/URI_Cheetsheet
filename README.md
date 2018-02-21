# URI_Cheatsheet
Cheat sheet for weird and wonderful URI and URL formats

## RFC 3986

[RFC 3986](https://tools.ietf.org/html/rfc3986) defines the generic syntax and format for URIs and is a good primer on what's possible with URIs. 

## Contact URIs

### E-mail Addresses
Uses the `mailto:` URI to signal the client to open a new e-mail message addressed to the recipient following the `mailto:` identifier in the default e-mail application.

`<a href="mailto:nobody@example.com">Feedback</a>`

Please read [RFC 6068](http://www.ietf.org/rfc/rfc6068.txt) for more information regarding advanced formatting. 


### Telephone Numbers
Works similar to `mailto:`

`<a href="tel:+31123456789">Call us</a>`

Please read [RFC 3966](http://www.ietf.org/rfc/rfc3966.txt) for more information regarding advanced formatting. 

### SIP/SIPS
SIP and SIPS URIs direct the client to make a SIP connection to a specific URN, over ports 5060 and 5061 respectivly, and (possibly) ask for a connection to a specific phone number.

`<a href="sip:1-999-123-4567@voip-provider.example.net">Call us</a>`

`<a href="sips:1-999-123-4567@voip-provider.example.net">Call us</a>`

[Wikipedia](https://en.wikipedia.org/wiki/SIP_URI_scheme) has a short article regarding `sip:` URIs. 

### Geolocation

Also similar to `mailto:` but support is a lot rarer.

`<a href="geo:37.786971,-122.399677;u=35">Wikimedia Headquarters</a>`

[Wikipedia](https://en.wikipedia.org/wiki/Geo_URI_scheme) has a short but sweet article regarding `geo:` URIs. 

## Currency

### Bitcoin

Similar to `mailto:`, opens a supported client for sending bitcoint to a wallet, if such a client exists.

`<a href="bitcoin:3QJmV3qfvAf3sRCW3qSinyC">Send me Bitcoin!</a>`
