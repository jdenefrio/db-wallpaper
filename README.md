# DB Wallpaper

A small Windows app that rotates your desktop through the
[Digital Blasphemy](https://digitalblasphemy.com) wallpaper collection. On each monitor it only uses
images that DB offers at (nearly) that screen's exact size and shape. You can choose galleries,
favorites, minimum ratings, timing, time-of-day schedules and light or dark mode, and it pauses
while you're gaming or on battery.

> **Unofficial, fan-made app.** Not affiliated with or endorsed by Digital Blasphemy. You need your
> own Digital Blasphemy membership and API key. All wallpapers are © Digital Blasphemy.

## Download

Get the latest `DBWallpaper-<version>-win-x64.zip` from **[Releases](../../releases/latest)**.
Windows 10 or 11, 64-bit. Nothing else needs to be installed.

## Install

1. Right-click the zip, choose **Properties**, tick **Unblock** at the bottom (if it's there), and
   click **OK**. Without this, PCs with Smart App Control refuse to run the app because it isn't
   code-signed.
2. Right-click the zip and choose **Extract All…**, then run **DBWallpaper.exe** from the extracted
   folder.
3. If Windows shows "Windows protected your PC", click **More info → Run anyway**.
4. Click **Yes** to install it for your account (no admin needed). It's added to the Start menu.
5. Click **Open your API keys page**, copy your key from
   <https://digitalblasphemy.com/my-account/db-api-keys/>, paste it in, and click **Save key**.

## Updates

Version 1.3.0 and later update themselves. The app checks here once a day and offers new versions on
its **Account & app** tab and tray menu. Updates are cryptographically signed, and the app refuses any
update that isn't.

## Privacy

Your API key is stored encrypted for your Windows account and is only sent to Digital Blasphemy's own
API. The app's update check downloads two small files from this page. Nothing else leaves your PC.
