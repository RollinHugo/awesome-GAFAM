# awesome-GAFAM
Awesome-GAFAM is a tutorial to escape (a bit) the influence of GAFAM on your life.
Each step in this list is optionnal and can be skipped if you think it's too much pain.
(But you definitely should follow most :) )

## 1. Simple steps

The first step to escape GAFAM is to change some of your everyday softwares that are tracking you.
This migration should be painless and can greatly improve your privacy!

### 1.1. Browsing the internet

If you belong to the 63.5% of people using Google Chrome, good news! Simply removing it will greatly increase your privacy.
There are tons of alternatives out there but I will advise sticking with an open-source web browser.
Two popular choices are **Mozilla Firefox** and **Chromium**, the latter being the closest to your Google Chrome experience.
**Brave** is also a browser based on privacy that you might want to check.

| Name | Link | Importing bookmarks |
| --- | --- | --- |
| Mozilla Firefox | [here](https://www.mozilla.org/en-US/firefox/download/thanks/) | [this](https://www.howtogeek.com/810747/import-chrome-bookmarks-to-firefox/) tutorial |
| Chromium | [here](https://www.chromium.org/getting-involved/download-chromium/) | [this](https://techwiser.com/export-bookmarks-from-google-chrome/) tutorial |
| Brave | [here](https://brave.com/linux/#release-channel-installation) | [this](https://techwiser.com/export-bookmarks-from-google-chrome/) tutorial |

Of course if you are on linux you can install the `firefox` or the `chromium-browser` packages.
Brave installation on Linux is a bit more complex by very acceptable.

The next step is to change your **search engine**. Several search engines are focused on privacy (list [here](https://restoreprivacy.com/private-search-engine/)), but I will advise a few.
**DuckDuckGo** has an interface very close to Google and has great search results.
**Qwant** is a bit different but adopting it should still be a breeze. And Brave comes with its own search engine.

To change your default search engine on *Firefox*, click on the three bars on the to right > Setting > Search > then you can change the search engine.

## 1.2. Mails

**Don't use Gmail**. There are several privacy-respecting companies offering email services. I personnaly use ProtonMail. They have a website, apps, and the possibility to encrypt email and such. You can import your gmails contacts following [this](https://proton.me/support/switch-from-gmail-to-proton) procedure. They also offer VPN and limited cloud storage, but I don't use them (see later).

If you want to use an app like outlook to check your emails from your computer, you can use the cross-platform mail client Thunderbird following [this](https://proton.me/support/protonmail-bridge-clients-windows-thunderbird) tutorial.

## 1.3. Cloud storage (simple version)

I will explain latter another solution for cloud storage, but I you want to keep it simple and prevent Google from analysing your data, you can just encrypt it before sending it to the Google Drive servers. To encrypt your data on Windows, follow [this](tutorial). On Linux, just use `zip --password MY_SECRET secure.zip file1 file2 file3` 

## 1.4. Camera on your laptop

Just put a thing on it. Switchable blockers can be bought cheaply or 3D-printed. It is also useful to use a pricacy filter (a film you put on your screen preventing your neightbors from eye-droping).

# 2. Medium steps

## 2.1. Switch to Linux

You can be surprised how easy it is to use Linux nowadays. The installation is quite easy for distributions like Ubuntu and most Windows-only softwares have good compatible Linux versions. Always make a backup before a Linux installation ! You can always keep Windows on the side for gaming and such.

## 2.2. Search for open-source alternatives to the proprietary softwares you are using

Most big-brand softwares are spiying on you to a limit. You can decide to use alternative softwares to reduce the risk. Search alternatives by taping in your Search Engine "alternative to <my_software>"

## 2.3. Use a VPN

Using a VPN encrypt your traffic, thus protecting your data. There are TONS of different VPNs, and I will not make any advice at the quality change quickly. A few advices when choosing your VPN:
- Pay for it. If it's free, you're the product
- Look for logging policy. try to find a no-log VPN
- If P2P is your thing, choose a compatible VPN. Few are.
- Be carefull with aggressive price reductions. After a year, if you let it like that, you will have to pay full price (x20 if you took it with a -95% coupon)

# 3. Harder/more expensive steps

## 3.1. Full on cloud !

NextCloud is a self-hosted cloud provider (kinda). Go see there website to have a clearer opinion. Basicly, it does from your own network everything Google is doing with Google Drive and such. The installation and maintenance can be a bit hard, but there are plenty of ressources online. Here is how I set it up:

1. Buy a Raspeberry Pi 4 (the bigger the better), a big SD card, a cheap external HDD that you can connect and power via USB, and the needed cables.
2. Set up your RPi as usual
3. Install Nextcloud by following the instructions on there doc
4. Connect the HDD and configure it to be used by nextcloud
5. Portfoward securely the Nextcloud Port with you router (router-dependant, tutorials online)
6. Install from the user interface the plugins you need/find cool
7. Keep the whole thing plugged in at all time.

## 3.2. Privacy focused hardware

I am not going to tell you what to buy, as it widely depends on your needs. There are however a few brands specialized in privacy-compliant hardware.
You can check for example puri.sm.

## 3.3. Degoogle-ify your Android phone

I will not give instructions or links for this one. This is a highly risky procedure and maybe illegal in some countries. But it remove Google from your phone.
