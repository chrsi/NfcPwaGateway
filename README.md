# NFC PWA Gateway
A simple Gateway for opening Progressive Web Applications on Android Devices using a NFC tag.

When scanning a URL on a NFC tag, the browser will open the page. It is currently not possible to launch the associated PWA using this method. As a workaround a page from a different origin has to be opened that redirects to the PWA.

With this gateway application hosted under https://chrsi.github.io/NfcPwaGateway you can simply open any PWA (except the ones hosted on github) using a NFC tag.

# Documentation
## PWA Location
Just provide a pwa parameter that specifies the location of your PWA. If you have a PWA on your phone linked with this url, it will launch automatically.

e.g. this will redirect you to the "https://www.orf.at" application:

`https://chrsi.github.io/NfcPwaGateway?pwa=https%3A%2F%2Fwww.orf.at`
