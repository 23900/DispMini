# DispMini: Use an iMac as a Monitor for a Mac mini or MacBook

DispMini is a macOS app that turns a 2017-or-later iMac into an external display for an Apple silicon Mac mini or MacBook. It is a modern alternative to Target Display Mode, working over a direct Thunderbolt or USB4 cable. It's free for individuals (including freelancers), schools, non-profits and government bodies.

Your iMac may be stuck on an old version of macOS, but its 4K or 5K screen is still excellent. Keep the screen, and let your Mac mini do the work.

**[Download](https://github.com/23900/DispMini/releases)** · **[Setup guide](docs/setup-guide.md)** · **[FAQ](docs/faq.md)** · **[Troubleshooting](docs/troubleshooting.md)** · **[Website](https://dispmini.app)**

> DispMini is in pre-release. This repository hosts documentation and downloads; the source code isn't published here.

## Why DispMini

- **Sharp text:** the picture matches the iMac's real screen dimensions, so nothing is scaled or softened.
- **Smooth and quiet:** both Macs use their built-in hardware video engines.
- **Automatic:** once both apps are set to start at login, it reconnects on its own.
- **One keyboard and mouse:** optionally control the Mac mini from the iMac.
- **Still a computer:** swipe or use a keyboard shortcut to return to the iMac's own desktop.
- **No server in the middle:** the picture goes directly between your two Macs and is never uploaded.

## Requirements

| | Install on | Needs |
|---|---|---|
| **DispMini Sender** | Mac mini or MacBook with Apple silicon | macOS 14 or later |
| **DispMini Receiver** | iMac from 2017 or later | macOS 13 or later |

You also need a **Thunderbolt 3 or later, or USB4 data cable** between the two Macs. DispMini is designed for this cable. It can connect over Wi-Fi by hand, but Wi-Fi isn't what it's designed for.

The 21.5-inch iMac 4K (2017) and 27-inch iMac 5K (2017) have been tested on real hardware. DispMini is built mainly for the Mac mini, and DispMini Sender also works on a Mac Studio with Apple silicon.

## Quick start

1. Connect the two Macs with the cable.
2. Open DispMini Receiver on the iMac and DispMini Sender on the Mac mini.
3. Allow the permissions macOS asks for.

The iMac then shows your Mac mini's desktop. See the [setup guide](docs/setup-guide.md) for details.

## Privacy

The picture is never uploaded. DispMini is designed for a direct cable between your Macs, so the connection isn't encrypted; Wi-Fi and other networks aren't what it's designed for. Update checks send limited device information, and we store the approximate location (country, region and city) that Cloudflare derives from your IP address. See the [Privacy Policy](PRIVACY.md).

## License

DispMini is free for individuals (including freelancers), schools, non-profits and government bodies. Companies and other businesses need a separate agreement: email support@dispmini.app. It isn't open source. See the [license agreement](LICENSE.md).

---

DispMini is an independent project and isn't affiliated with Apple. Mac, iMac, Mac mini, Mac Studio and MacBook are trademarks of Apple Inc.
