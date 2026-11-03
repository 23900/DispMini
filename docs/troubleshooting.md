# DispMini Troubleshooting

Start by clicking the DispMini icon in the Mac mini's menu bar and checking the device's status dot. The [setup guide](setup-guide.md#check-your-connection) explains the colors.

## macOS says it can't verify the developer

Go to **System Settings → Privacy & Security** and click **Open Anyway**. You only need to do this once for each app.

## The Mac mini can't find the iMac

1. Check that the cable is plugged in at both ends and is a Thunderbolt or USB4 data cable, not a charging cable.
2. Open DispMiniReceiver on the iMac and check that it's listening.
3. On any Mac running macOS 15 or later, go to **System Settings → Privacy & Security → Local Network** and check that the DispMini app is allowed. Earlier versions of macOS don't have this setting.
4. Click the iMac in the Sender's menu bar panel to connect by hand.

## It doesn't connect automatically without a cable

This is the default. DispMini connects automatically only when a cable is plugged in. Connect by hand, or set **Auto-connect** to **Thunderbolt or Wi-Fi** in the Sender's settings and check that receiver.

## It's connected, but there's no picture

1. Check that **Screen Recording** (**Screen & System Audio Recording** on newer versions of macOS) is allowed on the Mac mini, then quit and reopen DispMiniSender.
2. Disconnect and reconnect from the Sender's menu bar panel.

## The picture stutters or shows artifacts

- **Red dot:** you're on Wi-Fi. Plug in a Thunderbolt or USB4 cable.
- **Still red with a cable:** try another port or another cable. It may be a charging cable.
- **Yellow dot:** this is normally fine. If you still see problems, [set the MTU to 9000](setup-guide.md#optional-turn-the-dot-green).
- **Stuck on Wi-Fi:** use the 5 GHz band, move closer to the router, and pause large downloads.

## There's no sound

Check that **Transmit audio** is on in the Sender's settings and that the iMac isn't muted. If sound still doesn't play, quit and reopen DispMiniSender, or check that **Screen & System Audio Recording** permission is enabled on the Mac mini.

## The keyboard and mouse don't control the Mac mini

1. Check that **Allow controlling the other Mac with this Mac's mouse and keyboard** is on in DispMiniReceiver's settings.
2. Check that DispMiniSender is allowed under **System Settings → Privacy & Security → Accessibility** on the Mac mini.
3. Make sure the DispMini picture is fullscreen and on screen.

## I can't exit fullscreen

- Press **Ctrl+Option+Esc**. Esc on its own doesn't exit fullscreen.
- If that doesn't work, [switch to the iMac's own desktop](setup-guide.md#everyday-use) and quit DispMiniReceiver from there.

## It doesn't start or reconnect after a restart

Check that both apps are [set to start automatically](setup-guide.md#5-start-both-apps-automatically). Apps only start after you log in, so a Mac mini with no screen also needs automatic login. If FileVault is on, the Mac must be unlocked first.

## The iMac screen is black

The display has probably gone to sleep, so move the mouse or press a key. If that doesn't help, quit DispMiniReceiver and open it again.

## The picture freezes when the Mac mini sleeps

This is expected, because a sleeping Mac stops producing a picture. It comes back when the Mac mini wakes. To avoid seeing a frozen picture, turn on **Automatically exit fullscreen when the sender's Mac sleeps** in DispMiniReceiver's settings.

## Still stuck?

[Open an issue](https://github.com/23900/DispMini/issues) and include:

- The step where you got stuck
- Any on-screen message, or a screenshot
- The model and macOS version of both Macs
