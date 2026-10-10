JR~XAU — Android installable web app package

WHAT'S INCLUDED
- index.html: current signal dashboard, renamed JR~XAU
- manifest.webmanifest: app name, icon and standalone display settings
- sw.js: basic app-shell caching for repeat loads
- icons/: Android/PWA icons

IMPORTANT
This is an installable PWA package, not a signed Android APK. To install it as an app, these files must be hosted on an HTTPS website (or localhost). Opening index.html directly from Downloads will not enable PWA installation or service-worker caching.

The dashboard still depends on its external data provider and does not run as a hosted 24/7 service by itself. Its feed is not verified as identical to HFM quotes, it does not connect to HFM MT5, and signal lock/closure verification is manual. Never treat a LIVE label as proof that a setup is profitable; check the feed timestamps and test before trading.
