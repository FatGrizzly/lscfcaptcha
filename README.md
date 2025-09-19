lscfcaptcha
========

Description
--------

The lscfcaptcha Go module is a custom Cloudflare Turnstile processor.
The Turnstile validation is still performed by Cloudflare. This executable
will check if the response is successful and if so, notify the web server
that the client successfully completed the Turnstile challenge.

Installation
--------

Copy the binary from the latest release into your server root path:
```bash
mv _recaptcha /usr/local/lsws/lsrecaptcha/_recaptcha
chmod 555 /usr/local/lsws/lsrecaptcha/_recaptcha
```
Replace the existing _recaptcha.shtml file in /usr/local/lsws/lsrecaptcha/ with the new one.
Restart the server to take effect.


