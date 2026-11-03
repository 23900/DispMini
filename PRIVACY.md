# DispMini Privacy Policy

Last updated: November 3, 2026

This policy covers DispMini Sender, DispMini Receiver and the DispMini website. DispMini is run by James (GitHub: @23900) from New Zealand.

## Summary

- Your picture, audio, keyboard and mouse input aren't sent to any DispMini server.
- The only data sent to a DispMini server comes from update checks: app version, macOS version, Mac model and language.
- We also store the approximate location (country, region and city) that Cloudflare derives from your IP address.
- We don't store your IP address, and we don't sell your data.
- DispMini is designed for a direct cable between your Macs, so the connection isn't encrypted. Wi-Fi and other networks aren't what it's designed for.

## Between your two Macs

DispMini sends the picture and audio directly from the Sender to the Receiver. If you turn on keyboard and mouse sharing, your input goes from the Receiver to the Sender.

The Receiver also shares its Mac model, app version, macOS version and language with the Sender. It announces these on your local network so the Sender can find it.

DispMini is designed for a direct Thunderbolt or USB4 cable between your two Macs. Because that link stays between the two Macs, the connection isn't encrypted or authenticated. Wi-Fi and other networks aren't what DispMini is designed for. By default, it only connects automatically over a cable. It uses Wi-Fi only if you connect by hand or set **Auto-connect** to **Thunderbolt or Wi-Fi** in the Sender's settings. If you do, others on the network may be able to see or interfere with the connection. If you also share the keyboard and mouse, they may be able to see what you type, including passwords.

## Update checks

After connecting, DispMini Sender checks for updates at most once a day. You can also check by hand in its settings. DispMini Receiver doesn't contact the server.

Each check sends:

| Data | Mac |
|---|---|
| App version, including whether it's a release candidate or a development build | Sender and Receiver |
| macOS version | Sender and Receiver |
| Mac model | Sender and Receiver |
| Language | Sender and Receiver |

We use this data to choose which update information to show you, plan compatibility work and count usage.

We store these details with each check, along with the date and time, except the Receiver's language. Cloudflare also tells us the approximate location it derives from your IP address (country, region and city), and we store that too. We don't store the IP address itself or add any identifier for you or your Mac.

To stop automatic checks, turn them off in the Sender's settings.

## How long we keep data

We haven't set an automatic deletion period for usage statistics. Because they contain no account or device identifier, we generally can't find the records that came from a particular person.

## On your Mac

The apps store their settings and the list of known Receivers on your Mac. Deleting the apps and their settings removes this data.

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
