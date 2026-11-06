# QuantoBooks desktop

Installers for the QuantoBooks desktop app: the QuantoBooks accounting workspace in its own window for Mac and Windows.

**Download the latest version from the [Releases](https://github.com/QuantoTechnologyLabs/quantobooks-desktop-releases/releases/latest) page**, or from the Learn Portal inside QuantoBooks (Learn → Desktop app), which shows the right installer for your computer.

| Platform | File |
|---|---|
| Mac (Apple silicon and Intel) | `QuantoBooks-<version>-mac-universal.dmg` |
| Windows 10/11 (64-bit) | `QuantoBooks-<version>-win-x64.exe` |

## Opening a pilot build

Pilot builds are not yet signed with an Apple Developer ID or a Windows code-signing certificate, so each platform shows a one-time warning on first launch.

**Mac:** open the DMG and drag QuantoBooks to Applications. Open it once; macOS will say it could not verify the app. Click **Done**, then go to **System Settings → Privacy & Security**, scroll to the QuantoBooks message and click **Open Anyway**. Open the app again and confirm. You only do this once per version.

**Windows:** run the installer. When SmartScreen says the publisher is unrecognized, click **More info**, then **Run anyway**.

## Updating

Pilot builds do not update themselves. Install the newer version from the Releases page over the old one; your sign-in and settings are kept.

## Support

Email [support@tryquanto.com](mailto:support@tryquanto.com). This repository holds releases only; the app's source lives in Quanto's private monorepo.
