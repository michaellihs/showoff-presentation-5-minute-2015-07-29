!SLIDE section_slide

# Twisted #

## Python Netzwerk Bibliothek ##



!SLIDE

# Was macht Twisted?

* Bibliothek für Netzwerkprotokolle
* Ermöglicht Schreiben von Client / Server Anwendungen
* z.B. ssh-Server



!SLIDE

# Und was können wir damit tun?

* ssh-Server "mocken"
* z.B. für Deployment Tests



!SLIDE code_slide

# Installation

    @@@
    pip install twisted
    pip install pyOpenSSL
    pip install service_identity



!SLIDE code_slide

# Testen der Installation

    @@@ sh
    $ python
    >>> import twisted
    >>> twisted.__version__
    '15.2.1'
    >>> import OpenSSL
    >>> import twisted.internet.ssl
    >>> twisted.internet.ssl.SSL
    <module 'OpenSSL.SSL' from ... >



!SLIDE

# Eigenen ssh-Server schreiben

* Siehe [Gist auf Github](https://gist.github.com/michaellihs/d2070d7a6d3bb65be18c)



!SLIDE section_slide

# Live-Demo

## Daumen drücken!!!
