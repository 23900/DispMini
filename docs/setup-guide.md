# How to Use an iMac as a Monitor for a Mac mini

This guide sets up DispMini so your iMac works as an external display for an Apple silicon Mac mini or MacBook. It takes a few minutes and you only do it once.

## What you need

- **Sender:** Mac mini or MacBook with Apple silicon, macOS 14 or later
- **Receiver:** iMac from 2017 or later, macOS 13 or later
- **Cable:** Thunderbolt 3 or later, or USB4 data cable

A USB-C charging cable can look identical but won't work, because it doesn't support Thunderbolt or USB4 data links. Look for a Thunderbolt symbol or a 40Gbps USB4 marking on the cable.

If your Mac mini has no screen attached, connect one temporarily or use remote desktop for the first setup. macOS permission prompts must be clicked by hand.

## 1. Connect the Macs

Plug the cable directly into a Thunderbolt or USB4 port on both Macs. On a Mac mini with M4 or M4 Pro, use the ports on the back, because the front USB-C ports aren't Thunderbolt. You don't need to change any network settings.

## 2. Install the apps

Download both apps from [Releases](https://github.com/23900/DispMini/releases), then move each one to the Applications folder:

- **DispMini Sender** goes on the Mac mini or MacBook.
- **DispMini Receiver** goes on the iMac.

If macOS says it can't verify the developer, go to **System Settings → Privacy & Security** and click **Open Anyway**.

## 3. Set up the iMac

Open DispMini Receiver. On macOS 15 or later, allow **Local Network** access when asked. It then waits for a connection.

## 4. Set up the Mac mini

Open DispMini Sender. It runs in the menu bar, so no window or Dock icon appears. Allow these permissions:

- **Local Network** lets it find the iMac. macOS only asks for this on macOS 15 or later.
- **Screen Recording** lets it send the picture. Newer versions of macOS call this **Screen & System Audio Recording**.

If nothing happens after you allow Screen Recording, quit DispMini Sender and open it again.

The Sender finds the iMac and connects, and the iMac switches to fullscreen showing your Mac mini's desktop.

## 5. Start both apps automatically

Neither app starts automatically until you set this up:

- **On the Mac mini:** turn on **Launch at login** in DispMini Sender's settings.
- **On the iMac:** DispMini Receiver has no setting for this. Go to **System Settings → General → Login Items** (**Login Items & Extensions** on macOS 15 or later), click **+** under **Open at Login**, and choose **DispMiniReceiver**.

Apps only start after you log in. If your Mac mini has no screen, turn on automatic login in **System Settings → Users & Groups**, which lets anyone with physical access use that Mac. Automatic login isn't available while FileVault is on, and a Mac with FileVault on must be unlocked after each restart.

## Everyday use

Once both apps start automatically, turn on both Macs and they reconnect by themselves.

| To do this | Do this on the iMac |
|---|---|
| Switch to the iMac's own desktop | On a trackpad, swipe left or right with four fingers. On a Magic Mouse, swipe left or right with two fingers. On a keyboard, press **Ctrl+←** or **Ctrl+→** |
| Exit fullscreen | Press **Ctrl+Option+Esc** |
| Exit fullscreen when you aren't sharing the keyboard and mouse | Press **Ctrl+Option+Esc** or **Ctrl+Cmd+F** |

## Use the iMac's keyboard and mouse

Keyboard and mouse sharing is off by default.

1. On the iMac, turn on **Allow controlling the other Mac with this Mac's mouse and keyboard** in DispMini Receiver's settings.
2. On the Mac mini, allow **Accessibility** access when asked.

Input is only sent while the DispMini picture is fullscreen and on screen. Swipe to another desktop and your keyboard and mouse control the iMac again.

## Check your connection

Click the DispMini icon in the Mac mini's menu bar. The dot next to each device shows its status:

| Dot | Meaning |
|---|---|
| Gray | Device not found |
| Blue | Found, not connected |
| Red | Connected over Wi-Fi; use a cable if you can |
| Yellow | Connected by cable; this is fine for daily use |
| Green | Connected by cable with MTU 9000; this is the best state |

### Optional: turn the dot green

On **both** Macs:

1. Go to **System Settings → Network → Thunderbolt Bridge → Details → Hardware**.
2. Set **Configure** to **Manually** and **MTU** to **Jumbo (9000)**.
3. Reconnect DispMini.

To undo this, set **Configure** back to **Automatically**.

## Using Wi-Fi instead

By default, DispMini connects automatically when a cable is plugged in, and not otherwise. Without a cable, click the iMac in the Sender's menu bar panel to connect by hand. Put both Macs on the same 5 GHz network.

To maximize streaming performance and eliminate latency, DispMini does not add application-level encryption on top of the stream. While your Wi-Fi router provides link-layer encryption (WPA2/WPA3), others on the same network may be able to see or interfere with the stream—including keyboard input if keyboard and mouse sharing is on. Only use Wi-Fi on a trusted private home or office network, never on public or shared guest Wi-Fi.

If you only use Wi-Fi, set **Auto-connect** to **Thunderbolt or Wi-Fi** in the Sender's settings, then check the receivers that should connect over Wi-Fi.

## Next steps

- [FAQ](faq.md)
- [Troubleshooting](troubleshooting.md)
