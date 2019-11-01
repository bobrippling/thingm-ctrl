A hacky set of scripts to control a `blink(1)` from [thingm]

- [`ctrl`]: A perl script to write to the device files, can set one or both of the leds.
- [`server`]: Hacky server to host [`ui.html`] and parse the response that come back, passing the colours to [`ctrl`].
- [`ui.html`]: Simple page containing a colour control and logic to send the colours back to the server.

[thingm]: https://blink1.thingm.com/
[`ctrl`]: ctrl
[`server`]: server
[`ui.html`]: ui.html
