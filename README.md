# POCO X8 Pro Max — Personal Debloat List

A personal list of [ADB](https://developer.android.com/studio/command-line/adb) commands to remove bloatware from my POCO X8 Pro Max running HyperOS.

> **USE AT YOUR OWN RISK.** All removals use `pm uninstall -k --user 0`, which is reversible per-user and keeps app data intact. Still, review the list before running it and back up anything important.

---

## Prerequisites

1. **Install ADB** on your computer:
   - Quick setup: [Minimal ADB and Fastboot](https://xdaforums.com/t/tool-minimal-adb-and-fastboot-2-9-18.2317790/) (XDA)
   - Official: [Android SDK Platform Tools](https://developer.android.com/studio/releases/platform-tools)

2. **Enable Developer Options** on the phone:
   - `Settings > About phone` — tap `OS version` repeatedly until you see "You are now a developer!"

3. **Enable USB Debugging:**
   - `Settings > Additional settings > Developer options`
   - Toggle on `Developer options` and `USB debugging`

---

## How to Run

1. Connect the phone via USB.

2. Verify the connection:
   ```shell
   adb devices
   ```
   If it shows `unauthorized`, accept the prompt on the phone.

3. Enter the device shell:
   ```shell
   adb shell
   ```

4. Copy and paste the commands below into the shell.

---

## Debloat Commands

```shell
pm uninstall -k --user 0 cn.wps.moffice_eng
pm uninstall -k --user 0 cn.wps.xiaomi.abroad.lite
pm uninstall -k --user 0 com.alibaba.aliexpresshd
pm uninstall -k --user 0 com.amazon.appmanager
pm uninstall -k --user 0 com.amazon.fv
pm uninstall -k --user 0 com.amazon.kindle
pm uninstall -k --user 0 com.amazon.mp3
pm uninstall -k --user 0 com.amazon.mshop.android
pm uninstall -k --user 0 com.amazon.mshop.android.shopping
pm uninstall -k --user 0 com.amazon.venezia
pm uninstall -k --user 0 com.android.providers.downloads.ui
pm uninstall -k --user 0 com.audible.application
pm uninstall -k --user 0 com.bitdefender.security
pm uninstall -k --user 0 com.block.juggle
pm uninstall -k --user 0 com.block.puzzle.game.hippo.mi
pm uninstall -k --user 0 com.blurb.checkout
pm uninstall -k --user 0 com.booking
pm uninstall -k --user 0 com.cnn.mobile.android.phone.edgepanel
pm uninstall -k --user 0 com.crazy.juicer.xm
pm uninstall -k --user 0 com.duokan.phone.remotecontroller
pm uninstall -k --user 0 com.einnovation.temu
pm uninstall -k --user 0 com.enhance.gameservice
pm uninstall -k --user 0 com.flipboard.app
pm uninstall -k --user 0 com.flipboard.boxer.app
pm uninstall -k --user 0 com.fugo.wow
pm uninstall -k --user 0 com.funtomic.matchmasters
pm uninstall -k --user 0 com.gameduell.tarot
pm uninstall -k --user 0 com.google.android.apps.books
pm uninstall -k --user 0 com.google.android.apps.magazines
pm uninstall -k --user 0 com.google.android.apps.plus
pm uninstall -k --user 0 com.google.android.apps.subscriptions.red
pm uninstall -k --user 0 com.google.android.apps.tachyon
pm uninstall -k --user 0 com.google.android.apps.youtube.music
pm uninstall -k --user 0 com.google.android.music
pm uninstall -k --user 0 com.google.android.talk
pm uninstall -k --user 0 com.google.android.videos
pm uninstall -k --user 0 com.google.audio.hearing.visualization.accessibility.scribe
pm uninstall -k --user 0 com.imdb.mobile
pm uninstall -k --user 0 com.infraware.polarisoffice5
pm uninstall -k --user 0 com.jewelsblast.ivygames.adventure.free
pm uninstall -k --user 0 com.lemon.lvoverseas
pm uninstall -k --user 0 com.mi.global.pocobbs
pm uninstall -k --user 0 com.mi.global.pocostore
pm uninstall -k --user 0 com.mi.globalbrowser
pm uninstall -k --user 0 com.micredit.in
pm uninstall -k --user 0 com.microsoft.office.excel
pm uninstall -k --user 0 com.microsoft.office.officehubrow
pm uninstall -k --user 0 com.microsoft.office.outlook
pm uninstall -k --user 0 com.microsoft.office.powerpoint
pm uninstall -k --user 0 com.microsoft.office.word
pm uninstall -k --user 0 com.microsoft.skydrive
pm uninstall -k --user 0 com.miui.backup
pm uninstall -k --user 0 com.miui.cleaner
pm uninstall -k --user 0 com.miui.compass
pm uninstall -k --user 0 com.miui.extraphoto
pm uninstall -k --user 0 com.miui.misightservice
pm uninstall -k --user 0 com.miui.miwallpaper
pm uninstall -k --user 0 com.miui.miwallpaper.overlay.*
pm uninstall -k --user 0 com.miui.notes
pm uninstall -k --user 0 com.miui.notification
pm uninstall -k --user 0 com.miui.weather2
pm uninstall -k --user 0 com.mygalaxy
pm uninstall -k --user 0 com.netflix.mediaclient
pm uninstall -k --user 0 com.netflix.partner.activation
pm uninstall -k --user 0 com.nf.snake
pm uninstall -k --user 0 com.oakever.tiletrip
pm uninstall -k --user 0 com.opera.browser
pm uninstall -k --user 0 com.opera.max.oem
pm uninstall -k --user 0 com.opera.preinstall
pm uninstall -k --user 0 com.plarium.raidlegends
pm uninstall -k --user 0 com.sec.android.app.withtv
pm uninstall -k --user 0 com.singtel.mysingtel
pm uninstall -k --user 0 com.skype.raider
pm uninstall -k --user 0 com.sohu.inputmethod.sogou.xiaomi
pm uninstall -k --user 0 com.soulcompany.bubbleshooter.relaxing
pm uninstall -k --user 0 com.sukhavati.gotoplaying.bubble.bubbleshooter.mint
pm uninstall -k --user 0 com.touchtype.swiftkey
pm uninstall -k --user 0 com.tripadvisor.tripadvisor
pm uninstall -k --user 0 com.tripledot.solitaire
pm uninstall -k --user 0 com.vitastudio.mahjong
pm uninstall -k --user 0 com.vlingo.midas
pm uninstall -k --user 0 com.xiaomi.discover
pm uninstall -k --user 0 com.xiaomi.finddevice
pm uninstall -k --user 0 com.xiaomi.midrop
pm uninstall -k --user 0 com.xiaomi.ugd
pm uninstall -k --user 0 com.zhiliaoapp.musically
pm uninstall -k --user 0 de.autodoc.gmbh
pm uninstall -k --user 0 net.wooga.junes_journey_hidden_object_mystery_game
```

---

## Useful Commands

### Find a package name

```shell
pm list packages | grep '<query>'
```

### Restore a removed app

```shell
adb shell pm install-existing --user 0 <package_name>
```

---

## Troubleshooting & Common Fixes

### Wallpapers broken

```shell
adb shell pm install-existing --user 0 com.android.wallpaper.livepicker
adb shell pm install-existing --user 0 com.android.wallpapercropper
adb shell pm install-existing --user 0 com.miui.miwallpaper
```

### Android Auto not working

```shell
adb shell pm install-existing --user 0 com.google.android.projection.gearhead
```

### Bluetooth issues

```shell
adb shell pm install-existing --user 0 com.miui.miservice
adb shell pm install-existing --user 0 com.xiaomi.bluetooth
```

### OTA updates not working

```shell
adb shell pm install-existing --user 0 com.xiaomi.xmsf
adb shell pm install-existing --user 0 com.xiaomi.xmsfkeeper
adb shell pm install-existing --user 0 com.miui.cloudservice
adb shell pm install-existing --user 0 com.miui.cloudservice.sysbase
adb shell pm install-existing --user 0 com.xiaomi.micloud.sdk
adb shell pm install-existing --user 0 com.miui.daemon
adb shell pm install-existing --user 0 com.xiaomi.simactivate.service
```

Then reboot and set your region: `Settings > Additional settings > Region`.

---

## License

[MIT](LICENSE)
