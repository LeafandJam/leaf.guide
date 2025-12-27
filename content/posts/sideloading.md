---
title: "Sideloading"
date: 2025-04-17
draft: false
categories: ["ios"]
weight: 2
---

# Sideloading

Sideloading is the iOS equivalent of installing APK's on Android. It allows for "sideloading" apps that are not available on the app store.  

There are way to do this for free involving using a VPN to block Apple's servers but the easiest and most reliable method is to buy a certificate.

## Buying a Cert

>These cert's last for a year and then another must be bought
### Shops
Explore the [r/sideloaded](https://reddit.com/r/sideloaded) subreddit to see what shops are currently recommended as these change often.

>Do not pay for a lifetime certificate as these are normally a scam.

After purchasing the cert you'll need to join their discord server to download your files. It can take up to 3 days for your cert to be ready (this is an Apple limitation).

Once you have your cert you'll have 3 files:  

1. ```xxxx.p12```
2. ```xxxx.mobileprovision```
3. ```password```
## Setting up Feather

1. Download the latest ```.ipa``` file of [Feather](https://github.com/khcrysalis/Feather/releases/)
>This app will be used to sign other apps once installed.

2. Go to [sign.ipasign.cc](https://sign.ipasign.cc/)
>As we don't have Feather installed yet we have to use a website just once to sign and install it. In the future Feather will do this job for other apps.
>> If Feather doesn't work for you after following these steps, this website can sign apps for you instead of having Feather as a dedicated signing app.
3. Add your files to the correct boxes
4. Click _Sign it now !_
5. Click install when prompted. This will start installing Feather

6. Once installed, open Feather
7. Go to settings and click _Add Certificate_
8. Click the _+_
9. Add your files into the correct boxes and click save

Now you can use Feather to sign apps.

## Signing Apps
To sign an app with Feather:
1. Go to the _Library_ page
2. Click _Import_
3. Chose your .ipa files
4. Now under _Downloaded Apps_, click the app and click _Sign xxx_
5. Under _Signed Apps_ click your app and click _Install xxx_
6. Click install when prompted

Your app will now install.
## Recommended Apps
- [YTlitePlus](https://ytliteplus.github.io/): Best YouTube .ipa including: Premium features + Sponsor block + more.

## Add Sources
1. Visit this [Pastebin](https://pastebin.com/VkvhMqUL) and copy everything
2. Go to the Sources page in Feather
3. Click _Add Repo_
4. Click _Import Repositories_

This will provide some sources for .ipa files to install.
>Note: These links are not maintained and some may stop working. Google "ipa repo" and look at reddit for more.
