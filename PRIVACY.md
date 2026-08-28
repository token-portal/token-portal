# Privacy

Token Portal is built so there is nothing to worry about. This page says exactly what the plugin
does with your data, and it is short because the plugin does very little with it.

## What the plugin reads

Your Figma variables, text styles and shadows — in the file where you run it, when you press
**Get started** and again when you return to the plugin. When a variable references one from a
library you have enabled, the plugin follows the reference and reads that value too. Reading
sends nothing anywhere.

## Where your data goes

To exactly one place: the Git repository **you** name — GitHub or GitLab — and only when you
press **Connect**, **Check the repository** or **Publish**. The plugin's network access is
declared to Figma and limited to those two hosts; it cannot talk to anything else.

There is no server of ours, no account, no analytics, no telemetry, no crash reporting. Nothing
runs in the background. If you only use **Download ZIP**, nothing leaves your machine at all.

## The access token

The token you paste is stored by Figma on your computer, and only if you tick **Remember this
token on this computer**. Figma stores it unencrypted — the plugin says so right next to the
checkbox. **Disconnect** removes the token; the repository address stays.

## What we know about you

Nothing. We cannot see your design system, your repositories, your token, your name or whether
you have paid — payment status, when payments exist, is known only to Figma.

## Questions

Ask on the [issues page](https://github.com/token-portal/token-portal/issues). If this page and
the plugin ever disagree, that is a bug — please report it.
