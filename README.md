# Simple balenaBlock Eyes

Yes, there are more sophisticated ways to put spooky eyes on a TFT display attached to a Raspberry Pi, but perhaps none simpler than this.

This lightweight project uses [balenaBlocks](https://github.com/balenablocks/) to deploy two of the three containers needed to display spooky eyes on almost any small screen. The [browser](https://github.com/balenablocks/browser) and [fbcp](https://github.com/balenablocks/fbcp) blocks are primitives you can use for any project you want to display something via Chromium on the device (or via an attached HDMI monitor).

The third container is `alpine` running `httpd` and serving up a simple HTML file and .gif.

[![balena deploy button](https://www.balena.io/deploy.png)](https://dashboard.balena-cloud.com/deploy)
