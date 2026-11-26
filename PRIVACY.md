# DispMini Privacy Policy

Last updated: November 26, 2026

This policy covers DispMiniSender, DispMini on the Mac you use as a display (DispMiniReceiver), and the DispMini website. DispMini is run by James (GitHub: @23900) from New Zealand.

## Summary

- Your picture, audio, keyboard, and mouse input stay between your two Macs and aren't sent to any DispMini server.
- Update checks send basic details, such as the app version, macOS version, and Mac model, with no identifier for you or your Mac, so we can't tell who a check came from. We don't sell this data. See [Update checks](#update-checks) for the full list, including approximate location.
- The picture and sound between your Macs aren't encrypted. After the two Macs pair, keyboard and mouse input goes over an encrypted connection. Over Wi-Fi, use a trusted private network.

## Between your two Macs

DispMini sends the picture and audio directly from the Sender to the display. If you turn on keyboard and mouse sharing, your input goes from the display to the Sender.

DispMini on the display also shares its Mac model, app version, macOS version, and language with the Sender. It announces these on your local network so the Sender can find it.

DispMini is designed for a direct Thunderbolt or USB4 cable between your two Macs. The first time two Macs connect, they pair. After that, the Sender only creates its display for a display Mac it has paired with, and keyboard and mouse input goes over an encrypted connection. The pairing keys are created and kept on your two Macs and aren't sent to any server. To keep latency low, the picture and sound aren't encrypted. Only paired Macs can connect. By default, it only connects automatically over a cable. It uses Wi-Fi only if you connect by hand or set **Auto-connect** to **Thunderbolt or Wi-Fi** in the Sender's settings. While Wi-Fi provides link-layer encryption (such as WPA2/WPA3), others on the same local network may be able to see or interfere with the picture and sound. We recommend using a direct cable or a trusted private network rather than public or shared Wi-Fi.

## Update checks

DispMini's apps check for updates by themselves at most once a day, and you can also check by hand in each app's **About** tab. A check can send:

- The app and its version, including whether it's a release candidate or a development build
- macOS version
- Mac model
- Language
- Whether the app is paired with or connected to another Mac, and the same details for the Mac it's connected to

We use this data to choose which update information to show you, plan compatibility work, and count usage.

We store these details with each check, along with the date and time. Cloudflare also tells us the approximate location it derives from your IP address (country, region, and city), and we store that too. We don't store the IP address itself or add any identifier for you or your Mac.

To stop automatic checks, turn them off in each app's **About** tab.

## How long we keep data

We haven't set an automatic deletion period for usage statistics. Because they contain no account or device identifier, we generally can't find the records that came from a particular person.

## On your Mac

The apps store their settings and the list of known displays on your Mac. Deleting the apps and their settings removes this data.

## Website

The website doesn't use analytics or advertising cookies. If you switch the site's language, your choice is saved in your browser.

## Other services

These services handle data under their own privacy policies:

- **Cloudflare** hosts the update server and website, and processes your IP address to deliver them.
- **GitHub** hosts downloads and this documentation.
- **Buy Me a Coffee** handles sponsorship if you choose to sponsor.

## Your rights

You may have rights under the New Zealand Privacy Act 2020 or the privacy laws of your own country. To ask a question or make a request, email support@dispmini.app.

## Changes

We'll update this page when these practices change, and change the date at the top.
