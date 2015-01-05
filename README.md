systemui-overlay-sample
=======================

change the homeButton PNG via systemui-overlay.apk


With this sample we replace only one PNG file for the systemUI's HomeButton with a gray one for portrait- and landscape-mode!

See the /res Folder and the AndroidManifest.xml (for the Target-Kay-String)...

The PNG filename(s) have to match the original PNG-FileNames in /res/drawable-sw600dp-xhdpi/ 
of the original target.apk 'SystemUI.apk/res7drawable-sw600dp-xhdpi'


The packageName in AndroidManifest.xml of the new overla.apk has to match the android:packageName of the target.apk...

