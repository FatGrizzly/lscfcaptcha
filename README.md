lsrecaptcha
========

Description
--------

The lscfcaptcha Go module is a custom turnstile processor.
The turnstile validation is still performed by cloudflare. This executable
will check if the response is successful and if so, notify the web server
that the client successfully completed the turnstile challenge.

Compilation
--------

If desired, the module can be compiled manually. The only prerequisites
are that Golang is installed and the GOROOT environment variable is set.

After that, run `build_lsrecaptcha.sh`. This should generate a binary
named `_recaptcha`. This binary should be copied to `$SERVER_ROOT/lsrecaptcha/`
and installation is complete.

Forked from:
https://github.com/litespeedtech/openlitespeed

Edit _recaptcha.shtml appropriately and use, feel free to open an issue.
