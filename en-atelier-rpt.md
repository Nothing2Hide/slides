---
layout: slide
lang: EN
title: "Smartphones"
transition: slide
permalink: /en/atelier-rpt.html
onhome: false
categories: [Digital security]
license: "CC BY 3.0"
---

<section data-markdown>
{{page.title}}
====
</section>

<section>

<section data-markdown>
The basics: Passwords
----
[Is your password strong enough](https://nothing2hide.org/fr/verifier-la-robustesse-de-votre-mot-de-passe/")?
</section>
<section>
<ul>
<li>Forget <del>passwords</del>, use <a href="https://www.xkcd.com/936/">passphrases</a></li>
<li class="fragment">The more characters in your passphrase, the harder it will be to crack</li>
<li class="fragment">Avoid movie titles, novel titles or any personal information that is easy to guess</li>
<li class="fragment"><strong>Use a different phrase per department</strong></li>
<li class="fragment">Help yourself with password managers: <a href="https://bitwarden.com/">Bitwarden</a>, <a href="https://www.dashlane.com/">Dashlane</a> or <a href="http://keepass.info/">KeePass</a></li>
</ul>
</section>
<section data-markdown>
Enable **double authentication** on your accounts
-   [Google](https://myaccount.google.com/security)
-   [Microsoft](https://docs.microsoft.com/fr-fr/microsoft-365/admin/security-and-compliance/set-up-multi-factor-authentication?view=o365-worldwide)
-   [Apple](https://www.moyens.net/comment/comment-verifier-qui-a-acces-a-votre-iphone-et-a-votre-compte-apple/)
-   [Twitter](https://twitter.com/settings/account/login_verification)
-   [Facebook](https://www.facebook.com/settings?tab=security&section=approvals&view)
-   [Instagram](https://help.instagram.com/566810106808145)
</section>
</section>


<section>
<section data-markdown>
Data sent by your smartphone
=======================
</section>
<section data-markdown>
In communication
----------------
-   The GSM network encryption algorithm has been compromised for a long
    time
-   Legal interception: since 2015 and the intelligence law, the use of
    IMSI catchers is allowed
</section>
<section data-markdown>
Standby mode
--------
-   IMSI#: unique identifier your SIM card
-   IMEI#: unique identifier your phone (changing sim is not enough)
-   The network cell: from a few meters to several kilometers
</section>
<section data-markdown>
Bonus #1
---------
[Many software programs](http://www.gsmespion.com/) can turn your smartphone into a spy microphone. However, they must be installed on your phone.
</section>
<section data-markdown>
Bonus #2
---------
<img src="{{site.url}}{{site.baseurl}}/assets/i/iphone-puce.jpg" alt="spy chip" title="spy chip" />
<aside class="notes">
For as little as $15 you can buy spy equipment on Alibaba. Here a chip found in the iphone of a Russian activist.
</aside>
</section>
<section data-markdown>
Turned off
----------
The battery, plugged in, is still a source of energy. With the collaboration of the telephone operator, which can access the packets sent to the SIM card (Application Protocol Data Unit), the phone can theoretically be activated.
</section>
<section data-markdown>
Battery removed
---------------
Without a battery, there is no power, no transmitted signals, no monitoring.
</section>
<section data-markdown>
> In my fridge ← Snowden
Note: it is impossible to remove the battery on an iphone
</section>
</section>

<section>
<section data-markdown>
Application rights and permissions
==================================
Just like on a computer workstation you don\'t install just any
application on your smartphone. You have to check the rights that an
application claims on your smartphone. Ex: is it normal that a
flashlight application claims access to your contacts?
</section>
<section data-markdown>
There are 2 major application ecosystems today which are Android and Apple.
1.  Apple is known for its controls and validations before public release.
2.  Android (Google) unfortunately much less
</section>
<section data-markdown>
![Those apps all conatin malware have been downloaded more than More than 280 000 times on Google plays store](/assets/i/android-apps-malwares.png "Those apps all contain malware have been downloaded more than More than 280 000 times on Google Play store")

Those apps which all contain malware have been downloaded more than **280 000** times on Google plays store before they have been removed.
</section>
<section data-markdown>
[Check app permissions](https://support.google.com/android/answer/9431959?hl=en) on your Android phone
</section>
<section data-markdown>
Depending on your Android version (6 and above), you will most often
need to look in Settings \> Applications \> ( sometimes Advanced
Settings) \> Apps Permissions.
</section>
<section data-markdown>
In order to check what an app will do on your Android, take a look at
the [Exodus Privacy](https://exodus-privacy.eu.org/fr/page/what/)
project.
</section>
</section>

<section>
<section data-markdown>
How to protect your data
====
</section>
<section data-markdown>
Data everywhere
---------------
-   On the sim card
-   In the phone memory
-   On the SD card
-   In the "cloud"
</section>
<section data-markdown>
The Basics
----
-   Protect your Android or [iOS](https://support.apple.com/fr-fr/HT204060) smartphone with a password (more than 20 characters or delete after 10 attempts)
-   Encrypt the content of your smartphone on, [Android](https://support.google.com/pixelphone/answer/2844831?hl=en&sjid=14526544971493108138-EU) or [iOS](https://www.apple.com/privacy/government-information-requests/)
Note: Under ios the content is encrypted automatically, from the moment you set a code. Do not forget the data on external memories (SD cards, sim card) and possibly stored in the cloud (automatically encrypted under ios but not necessarily with other services).
</aside>
</section>
<section data-markdown>
Use a local safe
-------------------
[Tella](https://play.google.com/store/apps/details?id=org.hzontal.tella&hl)
is an android app that allows you to take photos and videos and store
them encrypted, camouflage them, or even erase them in case of
emergency.
</section>
<section data-markdown>
![Tella](/assets/i/tella.webp "Tella")
</section>
</section>

<section data-markdown>
How to protect your web browsing
====
Android
-   [Tor
    Browser](https://guardianproject.info/apps/org.torproject.torbrowser/)
    for Android
-   [Onion
    browser](https://itunes.apple.com/us/app/onion-browser/id519296448)
    for iPhone
-   Openvpn connect for
    [Android](https://play.google.com/store/apps/details?id=net.openvpn.openvpn)
    and
    [Iphone](https://itunes.apple.com/fr/app/openvpn-connect/id590379981?mt=8)
</section>

<section>
<section data-markdown>
How to protect your communication
==============
-   [Signal](https://signal.org/) for [Android](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms) and [Iphone](https://itunes.apple.com/us/app/signal-private-messenger/id874139669?mt=8)
-   [Wire](https://wire.com/en/) for [iOS](https://itunes.apple.com/app/wire/id930944768?mt=8) or [Android](https://play.google.com/store/apps/details?id=com.wire)
-   Avoid [Whatsapp](https://www.whatsapp.com/) following the recent [terms of use
    changes](https://www.francetvinfo.fr/internet/reseaux-sociaux/facebook/quatre-questions-sur-la-nouvelle-politique-de-partage-de-donnees-entre-facebook-et-whatsapp_4254337.html)
-   There are many [other](https://wiki.nothing2hide.org/doku.php?id=formations:smartphones:app-communications-securisees) secure communication apps
</section>
</section>

<section>
<section data-markdown>
Emergency plan in case your device got sized or stolen
=================
</section>
<section data-markdown>
- Make a a list of your sensitive accounts 
- Use passphrases for these accounts and enable dual authentication
- Don't forget to download backup codes that will allow you to unlock your accounts in case your smartphone is stolen or seized
- Change the passwords of your accounts
</section>
<section data-markdown>
### Android
- Go to the [devices](https://myaccount.google.com/device-activity) security section of your Google account
- Make it ring, locate it or erase remotely your data
</section>
<section data-markdown>
### iOS
Activate the Find app on your phone and go to [icloud.com/find](https://www.icloud.com/find)
- [Find a lost device](https://support.apple.com/fr-fr/HT210515#erasedevice)
- [Erase remotely your data](https://support.apple.com/fr-fr/HT210515#erasedevice)
</section>
</section>

<section>
<section data-markdown>
Another option
-----
</section>
<section data-background="{{site.url}}{{site.baseurl}}/assets/i/dumbphone.jpg">
    <aside class="notes">Burner phone. Image from <a href="http://in30minutes.com">In 30 Minutes guides</a> licensed under CC 2.0</aside>
</section>
</section>

<section data-markdown data-background="{{site.url}}{{site.baseurl}}/assets/i/questions-willsmith.gif" data-background-transition="zoom">
Questions?
======
</section>

