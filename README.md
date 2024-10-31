### 使用方式

1. 安著手機打開開發者模式，允許Debug
2. Android Studio 連接安著手機
3. 使用此工具 adb.exe 對安卓手機調試

### 移除小米手機系統app的指令

```sh
adb shell pm uninstall --user 0 com.miui.msa.global
adb shell pm uninstall --user 0 com.miui.analytics
adb shell pm uninstall --user 0 com.miui.miservice
adb shell pm uninstall --user 0 com.miui.bugreport
adb shell pm uninstall --user 0 com.miui.daemon
adb shell pm uninstall --user 0 com.miui.securityadd
adb shell pm uninstall --user 0 com.xiaomi.mipicks
adb shell pm uninstall --user 0 com.xiaomi.account
adb shell pm uninstall --user 0 com.xiaomi.payment
adb shell pm uninstall --user 0 com.xiaomi.scanner
adb shell pm uninstall --user 0 com.xiaomi.midrop
adb shell pm uninstall --user 0 com.xiaomi.joyose  # 小米記步
adb shell pm uninstall --user 0 com.mipay.wallet.in
adb shell pm uninstall --user 0 com.miui.yellowpage
adb shell pm uninstall --user 0 com.miui.hybrid
adb shell pm uninstall --user 0 com.miui.hybrid.accessory
adb shell pm uninstall --user 0 com.miui.videoplayer
adb shell pm uninstall --user 0 com.miui.cloudservice
adb shell pm uninstall --user 0 com.miui.cloudservice.sysbase
adb shell pm uninstall --user 0 com.miui.micloudsync
adb shell pm uninstall --user 0 com.miui.cloudbackup
adb shell pm uninstall --user 0 com.miui.compass
adb shell pm uninstall --user 0 com.xiaomi.mircs
adb shell pm uninstall --user 0 com.xiaomi.xmsf   # 小米搜尋
adb shell pm uninstall --user 0 com.xiaomi.xmsfkeeper
adb shell pm uninstall --user 0 com.xiaomi.micloud.sdk  # ###
adb shell pm uninstall --user 0 com.xiaomi.mi_connect_service
adb shell pm uninstall --user 0 com.xiaomi.miplay_client
adb shell pm uninstall --user 0 com.xiaomi.glgm  # 小米遊戲
adb shell pm uninstall --user 0 com.xiaomi.simactivate.service  # 小米SIM卡服務
adb shell pm uninstall --user 0 com.milink.service
adb shell pm uninstall --user 0 com.mi.android.globalminusscreen  # 資訊助手
adb shell pm uninstall --user 0 com.miui.global.packageinstaller  # 套件安裝 ###
adb shell pm uninstall --user 0 com.xiaomi.discover  # 系統應用升級
adb shell pm uninstall --user 0 com.android.thememanager  # 主題
adb shell pm uninstall --user 0 com.android.providers.downloads  # 下載管理
adb shell pm uninstall --user 0 com.android.providers.downloads.ui
adb shell pm uninstall --user 0 com.facebook.system
adb shell pm uninstall --user 0 com.facebook.appmanager
adb shell pm uninstall --user 0 com.facebook.services
adb shell pm uninstall --user 0 com.android.soundrecorder  # 錄音機
adb shell pm uninstall --user 0 com.miui.gallery  # 相簿
adb shell pm uninstall --user 0 com.miui.fm  # 收音機
adb shell pm uninstall --user 0 com.miui.fmservice
adb shell pm uninstall --user 0 com.miui.player  # 音樂
adb shell pm uninstall --user 0 com.miui.weather2  # 天氣
adb shell pm uninstall --user 0 com.miui.screenrecorder  # 螢幕錄影
adb shell pm uninstall --user 0 com.miui.cleanmaster  # 深度清理
adb shell pm uninstall --user 0 com.google.android.apps.subscriptions.red
adb shell pm uninstall --user 0 com.google.android.apps.googleassistant
adb shell pm uninstall --user 0 com.android.nfc
```

### 備註
1. 官網也有載點: https://developer.android.com/tools/releases/platform-tools?hl=zh-tw
2. 切記 uninstall 前要先看過 ，像我的同事 Ted 給我uninstall NFC 功能的指令，直接把我手機的NFC整沒了
