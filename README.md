# DispMini: Use an iMac as a Monitor for a Mac mini or MacBook

DispMini is a macOS app that turns a 2017-or-later iMac into an external display for an Apple silicon Mac mini or MacBook. It is a modern alternative to Target Display Mode, working over a direct Thunderbolt or USB4 cable. It is free for personal, educational, and non-profit use.

Your iMac may be stuck on an old version of macOS, but its 4K or 5K screen is still excellent. Keep the screen, and let your Mac mini do the work.

**[Download](https://github.com/23900/DispMini/releases)** · **[Setup guide](docs/setup-guide.md)** · **[FAQ](docs/faq.md)** · **[Troubleshooting](docs/troubleshooting.md)** · **[Website](https://dispmini.app)** · **[❤️ Sponsor](https://buymeacoffee.com/dispmini)**

> DispMini is in pre-release. This repository hosts documentation and downloads; the source code isn't published here.

## Why DispMini

- **Sharp text:** the picture matches the iMac's real screen dimensions, so nothing is scaled or softened.
- **Smooth and quiet:** both Macs use their built-in hardware video engines.
- **Automatic:** once both apps are set to start at login, it reconnects on its own.
- **One keyboard and mouse:** optionally control the Mac mini from the iMac.
- **Audio included:** routes your Mac mini's sound directly through the iMac's built-in speakers.
- **Still a computer:** swipe or use a keyboard shortcut to return to the iMac's own desktop.
- **No server in the middle:** the picture goes directly between your two Macs and is never uploaded.

## Requirements

| | Install on | Needs |
|---|---|---|
| **DispMiniSender** | Mac mini or MacBook with Apple silicon | macOS 14 or later |
| **DispMiniReceiver** | iMac from 2017 or later | macOS 13 or later |

You also need a **Thunderbolt 3/4 or USB4 data cable** between the two Macs for full performance (manual Wi-Fi connection is also supported as a fallback).

The 21.5-inch iMac 4K (2017) and 27-inch iMac 5K (2017) have been tested on real hardware. DispMini is built mainly for the Mac mini, and DispMiniSender also works on a Mac Studio with Apple silicon.

## Quick start

1. Connect the two Macs with the cable.
2. Open DispMiniReceiver on the iMac and DispMiniSender on the Mac mini.
3. Allow the permissions macOS asks for.

The iMac then shows your Mac mini's desktop. See the [setup guide](docs/setup-guide.md) for details.

## Network & Privacy

All video, audio, and input data streams directly between your Macs over the local connection—nothing is sent to external servers or the cloud.

To maximize streaming performance and eliminate latency, DispMini does not add application-level encryption on top of the stream. While your Wi-Fi network itself provides link-layer encryption (such as WPA2/WPA3), we recommend using a direct Thunderbolt/USB4 cable or a trusted private home/office network rather than public Wi-Fi.

Update checks send basic device info and anonymous region metadata to verify latest versions. See the [Privacy Policy](PRIVACY.md).

## Support & License

DispMini is free for individuals (including freelancers), schools, non-profits, and government bodies, with no ads or subscriptions. If it gave your 4K or 5K iMac a second life and saved you the cost of a new monitor, consider **[buying me a coffee](https://buymeacoffee.com/dispmini)** to help cover Apple Developer membership costs and ongoing macOS compatibility.

Companies and other businesses need a separate agreement: email support@dispmini.app. It isn't open source—see the [license agreement](LICENSE.md).

---

DispMini is an independent project and isn't affiliated with Apple. Mac, iMac, Mac mini, Mac Studio, and MacBook are trademarks of Apple Inc.
