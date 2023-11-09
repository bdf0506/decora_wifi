# Leviton Decora Wi-Fi HACS

The Leviton Decora Wi-Fi component in Home Assistant has been neglected for quite some time. There's been a few unsuccessful pull requests that never have made it into the code. I took the work that [@connorwagner](https://github.com/connorwagner) did and made it as a drop-in replacement for the Decora Wi-Fi component via HACS.

In addition to allowing you to configure Decora Wi-Fi from the UI with a username and password, it also splits out fan controller model DW4SF and places it properly as a fan device.

References of pending/stalled PRs into the main HA code:

https://github.com/home-assistant/core/pull/68093

https://github.com/home-assistant/core/pull/68051

https://github.com/home-assistant/core/pull/51092
