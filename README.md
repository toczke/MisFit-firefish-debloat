# MisFit-firefish-debloat
#ADB Script for debloating Misfit Vaport 2 WearOS Smartwatch

>adb connect IP_Address:5555
>adb shell 
>(accept debugging on watch)

pm uninstall --user 0 com.google.android.theme.firefish.ms </ br>
pm uninstall --user 0 com.fossil.elabel
pm uninstall --user 0 com.fossil.oemsetup.firefish
pm uninstall --user 0 com.fossil.wearables.ms
pm uninstall --user 0 com.fossil.charge.firefish
pm uninstall --user 0 com.dianping.v1   
pm uninstall --user 0 com.google.android.wearable.smarthome
pm uninstall --user 0 com.sogou.map.android.maps
pm uninstall --user 0 com.mobvoi.wear.fitness.aw
pm uninstall --user 0 com.mobvoi.ticwear.sidewearvoicesearch
pm uninstall --user 0 com.mobvoi.wear.social.aw
pm uninstall --user 0 com.mobvoi.wear.account.aw
pm uninstall --user 0 com.fossil.wearables.ds
pm uninstall --user 0 com.fossil.wearables.ks
pm uninstall --user 0 com.fossil.wearables.mk
pm uninstall --user 0 com.fossil.wearables.ms
pm uninstall --user 0 com.fossil.wearables.pu
pm uninstall --user 0 com.mobvoi.wear.appsservice
pm uninstall --user 0 com.mobvoi.wear.health.aw
pm uninstall --user 0 com.mobvoi.wear.neteasemusic.aw
pm uninstall --user 0 com.google.android.inputmethod.pinyin
pm uninstall --user 0 com.mobvoi.ticwear.aw.appstore
pm uninstall --user 0 com.amberweather.watch
pm uninstall --user 0 com.eg.android.AlipayGphone
pm uninstall --user 0 ctrip.android.view
pm uninstall --user 0 com.gotokeep.androidwear
pm uninstall --user 0 com.fossil.twm
pm uninstall --user 0 com.fossil.elabel
pm uninstall --user 0 com.fossil.wearables.savedfaceservice
pm uninstall --user 0 com.google.android.clockwork.gestures.tutorial
pm uninstall --user 0 com.fossil.wearable.pay
pm uninstall --user 0 com.spotify.music
pm uninstall --user 0 com.fossil.wearables.tos
pm uninstall --user 0 com.cei.servicetool
pm uninstall --user 0 com.safetrekapp.safetrek
pm uninstall --user 0 com.google.android.apps.handwriting.ime
pm uninstall --user 0 com.fossil.wearables.watchfaces
reboot


Done!
