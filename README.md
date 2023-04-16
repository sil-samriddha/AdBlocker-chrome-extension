# AD-Blocker Chrome Extension
This extension blocks ads on websites to improve user experience. 

[![GitHub manifest version](https://img.shields.io/github/manifest-json/v/sil-samriddha/AdBlocker-chrome-extension)](manifest.json)
![GitHub Repo stars](https://img.shields.io/github/stars/sil-samriddha/AdBlocker-chrome-extension?style=social)

* 74% of ads can be blocked
* Cosmetic Filters and AdScripts filters not provided
<br><br>![64x64](https://user-images.githubusercontent.com/95685662/232325307-cdaa4569-0ab1-489d-94ee-360d55850680.png)


# How to use it?
<ul>
  <li>Download this repo as a ZIP.</li>
  <li>Unzip the file.</li>
  <li>Go to <a herf="chrome://extensions" target="_blank">chrome://extensions</a></li>
  <li>Enable Developer Mode.</li>
  <li>Load Unpacked by selecting the folder where you extracted the Zip</li>
  <li>Turn the extension on</li>
</ul>

# Result
![Result](https://user-images.githubusercontent.com/95685662/232324392-2728a9ba-689c-453b-a70b-23108b9abf66.png)

```bash
script_ads : false
script_pagead : false
script_partenrads : false

-------------------------
Amazon => n° tests => 5
Google Ads => n° tests => 4
Doubleclick.net => n° tests => 5
Adcolony => n° tests => 4
Media.net => n° tests => 3
Ads => Total n° tests => 21
-------------------------
Google Analytics => n° tests => 5
Hotjar => n° tests => 7
MouseFlow => n° tests => 4
FreshWorks => n° tests => 3
Luckyorange => n° tests => 8
Stats WP Plugin => n° tests => 1
Analytics => Total n° tests => 28
-------------------------
Bugsnag => n° tests => 4
Sentry => n° tests => 2
Error Trackers => Total n° tests => 6
-------------------------
Facebook => n° tests => 2
Twitter => n° tests => 2
LinkedIn => n° tests => 2
Pinterest => n° tests => 5
Reddit => n° tests => 2
YouTube => n° tests => 1
TikTok => n° tests => 7
Social Trackers => Total n° tests => 21
-------------------------
Yahoo => n° tests => 11
Yandex => n° tests => 7
Unity => n° tests => 4
Mix => Total n° tests => 22
-------------------------
Realme => n° tests => 4
Xiaomi => n° tests => 8
Oppo => n° tests => 4
Huawei => n° tests => 6
OnePlus => n° tests => 2
Samsung => n° tests => 5
Apple => n° tests => 10
OEMs => Total n° tests => 39
-------------------------
cosmetic_static_ad : false

-------------------------
cosmetic_dynamic_ad : false

-------------------------

adtago.s3.amazonaws.com - blocked
analyticsengine.s3.amazonaws.com - blocked
analytics.s3.amazonaws.com - blocked
advice-ads.s3.amazonaws.com - blocked
advertising-api-eu.amazon.com - blocked
pagead2.googlesyndication.com - blocked
adservice.google.com - blocked
pagead2.googleadservices.com - blocked
afs.googlesyndication.com - blocked
stats.g.doubleclick.net - blocked
ad.doubleclick.net - blocked
static.doubleclick.net - blocked
m.doubleclick.net - blocked
mediavisor.doubleclick.net - blocked
ads30.adcolony.com - blocked
adc3-launch.adcolony.com - blocked
events3alt.adcolony.com - blocked
wd.adcolony.com - blocked
static.media.net - blocked
adservetx.media.net - blocked
app-measurement.com - blocked
analytics.google.com - blocked
click.googleanalytics.com - blocked
google-analytics.com - blocked
ssl.google-analytics.com - blocked
adm.hotjar.com - blocked
identify.hotjar.com - blocked
insights.hotjar.com - blocked
script.hotjar.com - blocked
surveys.hotjar.com - blocked
careers.hotjar.com - blocked
mouseflow.com - blocked
api.mouseflow.com - blocked
tools.mouseflow.com - blocked
cdn-test.mouseflow.com - blocked
freshmarketer.com - blocked
claritybt.freshmarketer.com - blocked
fwtracks.freshmarketer.com - blocked
luckyorange.com - blocked
api.luckyorange.com - blocked
realtime.luckyorange.com - blocked
cdn.luckyorange.com - blocked
w1.luckyorange.com - blocked
upload.luckyorange.net - blocked
cs.luckyorange.net - blocked
settings.luckyorange.net - blocked
notify.bugsnag.com - blocked
sessions.bugsnag.com - blocked
api.bugsnag.com - blocked
app.bugsnag.com - blocked
pixel.facebook.com - blocked
an.facebook.com - blocked
static.ads-twitter.com - blocked
ads.linkedin.com - blocked
analytics.pointdrive.linkedin.com - blocked
ads.pinterest.com - blocked
log.pinterest.com - blocked
analytics.pinterest.com - blocked
trk.pinterest.com - blocked
widgets.pinterest.com - blocked
ads.youtube.com - blocked
ads.yahoo.com - blocked
analytics.yahoo.com - blocked
geo.yahoo.com - blocked
advertising.yahoo.com - blocked
analytics.query.yahoo.com - blocked
partnerads.ysm.yahoo.com - blocked
log.fc.yahoo.com - blocked
gemini.yahoo.com - blocked
extmaps-api.yandex.net - blocked
appmetrica.yandex.ru - blocked
adfstat.yandex.ru - blocked
metrika.yandex.ru - blocked
advertising.yandex.ru - blocked
offerwall.yandex.net - blocked
adfox.yandex.ru - blocked
auction.unityads.unity3d.com - blocked
webview.unityads.unity3d.com - blocked
config.unityads.unity3d.com - blocked
adserver.unityads.unity3d.com - blocked
api.ad.xiaomi.com - blocked
sdkconfig.ad.xiaomi.com - blocked
sdkconfig.ad.intl.xiaomi.com - blocked
globalapi.ad.xiaomi.com - blocked
adsfs.oppomobile.com - blocked
adx.ads.oppomobile.com - blocked
ck.ads.oppomobile.com - blocked
data.ads.oppomobile.com - blocked
metrics.data.hicloud.com - blocked
metrics2.data.hicloud.com - blocked
grs.hicloud.com - blocked
logservice.hicloud.com - blocked
logservice1.hicloud.com - blocked
logbak.hicloud.com - blocked
click.oneplus.cn - blocked
samsungads.com - blocked
nmetrics.samsung.com - blocked
advertising.apple.com - blocked
tr.iadsdk.apple.com - blocked
iadsdk.apple.com - blocked
api-adservices.apple.com - blocked
events.reddit.com - not blocked
ads-api.twitter.com - not blocked
bdapi-in-ads.realmemobile.com - not blocked
weather-analytics-events.apple.com - not blocked
notes-analytics-events.apple.com - not blocked
books-analytics-events.apple.com - not blocked
data.mistat.xiaomi.com - not blocked
iot-logser.realme.com - not blocked
browser.sentry-cdn.com - not blocked
events.hotjar.io - not blocked
events.redditmedia.com - not blocked
udc.yahoo.com - not blocked
udcm.yahoo.com - not blocked
bdapi-ads.realmemobile.com - not blocked
iot-eu-logser.realme.com - not blocked
app.getsentry.com - not blocked
tracking.rus.miui.com - not blocked
metrics.mzstatic.com - not blocked
smetrics.samsung.com - not blocked
data.mistat.india.xiaomi.com - not blocked
metrics.icloud.com - not blocked
data.mistat.rus.xiaomi.com - not blocked
open.oneplus.net - not blocked
adtech.yahooinc.com - not blocked
stats.wp.com - not blocked
metrics.apple.com - blocked
samsung-com.112.2o7.net - not blocked
media.net - not blocked
analytics-api.samsunghealthcn.com - not blocked
ads-api.tiktok.com - blocked
analytics.tiktok.com - blocked
ads-sg.tiktok.com - blocked
analytics-sg.tiktok.com - blocked
business-api.tiktok.com - blocked
ads.tiktok.com - blocked
log.byteoversea.com - blocked
-----
Total : 147
Blocked : 109
Not Blocked : 38
```
