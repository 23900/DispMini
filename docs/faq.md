# DispMini FAQ

## Can I use my iMac as a monitor for a Mac mini?

Yes. Install DispMini on both Macs and connect them with a Thunderbolt or USB4 cable. Your iMac then works as an external display for your Mac mini or MacBook. See the [setup guide](setup-guide.md).

## Is DispMini the same as Target Display Mode?

It does the same job in a different way. Apple's Target Display Mode isn't available on iMacs from 2017 onward or on Apple silicon Macs. DispMini sends the picture over a normal data link between the two Macs, so it works on machines that never had Target Display Mode.

## Which iMacs work with DispMini?

iMacs from 2017 or later running macOS 13 or later. The 21.5-inch iMac 4K (2017) and 27-inch iMac 5K (2017) have been tested on real hardware.

iMacs from before 2017 aren't supported.

## Which Macs can send the picture?

A Mac mini or MacBook with Apple silicon, running macOS 14 or later. Intel-based Macs aren't supported as the sender.

## Does DispMini work with a Mac Studio?

Yes. DispMini is built mainly for the Mac mini, but DispMini Sender also works on a Mac Studio with Apple silicon, running macOS 14 or later. On a Mac Studio with a Max chip, use the Thunderbolt ports on the back.

## Do I need a cable?

Yes. DispMini is designed for a Thunderbolt 3 or later, or USB4 data cable. Sending a full 4K or 5K picture in real time takes a lot of bandwidth, and a direct cable provides it reliably. It can connect over Wi-Fi by hand, but that isn't what it's designed for.

## Does DispMini work over Wi-Fi?

It can connect, but DispMini isn't designed for Wi-Fi. By default, it only connects automatically over a cable. It uses Wi-Fi only if you connect by hand or set **Auto-connect** to **Thunderbolt or Wi-Fi** in the Sender's settings. Picture quality and responsiveness then depend on your network, and the connection isn't encrypted.

## Is there any lag?

With a cable, everyday work such as typing, coding, browsing and video calls keeps up well. It isn't recommended for professional color grading, and results over Wi-Fi vary.

## How is it different from AirPlay or Screen Sharing?

Those are designed for occasional use and may scale or heavily compress the picture. DispMini is designed to be a permanent display: it matches the iMac's real screen dimensions and reconnects automatically.

## Can I control the Mac mini with the iMac's keyboard and mouse?

Yes. Turn this on in DispMini Receiver's settings and allow Accessibility access on the Mac mini. It's off by default.

## Can I still use the iMac as a computer?

Yes. The DispMini picture is on its own desktop, so you can [swipe or use a keyboard shortcut](setup-guide.md#everyday-use) to go back to the iMac's own desktop. Quit the app whenever you like.

## Does it play sound through the iMac?

Yes. Turn on **Transmit audio** in the Sender's settings.

## Does my Mac mini need its own monitor?

Only for the first setup, because macOS permission prompts must be clicked by hand. A temporary monitor or remote desktop works. After that, it can start and connect without one if you [set it to start automatically](setup-guide.md#5-start-both-apps-automatically) and turn on automatic login.

## Is my screen content private?

The picture goes directly between your two Macs and is never uploaded or relayed. DispMini is designed for a direct cable, which keeps the connection between the two Macs, so the connection isn't encrypted. Wi-Fi and other networks aren't what it's designed for, and others on those networks may be able to see or interfere with it. If you also share the keyboard and mouse, they may be able to see what you type, including passwords. See the [Privacy Policy](../PRIVACY.md).

## How much does DispMini cost?

It's free for individuals (including freelancers), schools, non-profits and government bodies, and sustained by voluntary sponsorship. Companies and other businesses need a separate agreement.

## Can my school, non-profit or company use DispMini?

Schools, non-profits and government bodies can use it for free, and so can freelancers working for themselves. Companies and other businesses need a separate agreement: email support@dispmini.app. See the [license agreement](../LICENSE.md).

## Is DispMini open source?

No. This repository hosts the documentation and downloads only.
