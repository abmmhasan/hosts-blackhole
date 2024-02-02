# Hosts Blackhole

If you are using any custom ad-blocking servers at home (like Pi-Hole, AdGuard etc.) or any servers that accepts ABP style or Host file style block list you can use ad list provided here. 
Just copy the link address from **Copy Link** column and add to your gravity source.
Also, it'd be great if you can set up schedular to update on daily basis.

## List of Hosts Files

Currently, 16 different variants from 4 sources are provided. All the file links, are direct file link to this Github
repo.
> Several hosts file are collected from different sources on daily basis.

### [OISD](https://oisd.nl/)

| Type  |                                                                        Blocking Type                                                                         |                                           Copy Link                                            |
|-------|:------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------:|
| Small |                                                                             Ads                                                                              |   [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/oisd/ads)    |
| Big   | Ads, Phishing, Malvertising, Malware, Spyware, Ransomware, CryptoJacking, Scam, ... Telemetry/Analytics/Tracking (Where not needed for proper functionality) | [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/oisd/security) |
| NSFW  |                                                                      Porn, Shock, adult                                                                      |   [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/oisd/nsfw)   |

### [Steven Black](https://github.com/StevenBlack/hosts)

| Type        |                  Blocking Type                  |                                                 Copy Link                                                 |
|-------------|:-----------------------------------------------:|:---------------------------------------------------------------------------------------------------------:|
| Unified     |                  Ads + Malware                  |   [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/steven-black/unified)   |
| Social      |                  Social Media                   |   [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/steven-black/social)    |
| Porn        |                   Pornography                   |    [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/steven-black/porn)     |
| Gambling    |                    Gambling                     |  [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/steven-black/gambling)   |
| Fake        |                    Fake News                    |  [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/steven-black/fake-news)  |
| Non Unified |         Social + Porn + Gambling + Fake         | [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/steven-black/non-unified) |
| Everything  | Ads + Malware + Social + Porn + Gambling + Fake |     [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/steven-black/all)     |

### [lightswitch05](https://www.github.developerdan.com/hosts/)

| Type                |                                                          Blocking Type                                                          |                                                     Copy Link                                                      |
|---------------------|:-------------------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------:|
| Ads & Tracking      |                                                         Ads + Tracking                                                          |    [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/lightswitch05/ads-tracking)     |
| Facebook            |                                            Facebook, Messenger, Instagram, WhatsApp                                             |      [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/lightswitch05/facebook)       |
| AMP                 | [Google's Accelerated Mobile Pages (AMP)](https://www.theregister.co.uk/2017/05/19/open_source_insider_google_amp_bad_bad_bad/) |     [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/lightswitch05/google-amp)      |
| Dating              |                                                         Dating Services                                                         |       [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/lightswitch05/dating)        |
| Aggressive Tracking |                                       Aggressive tracking (Not Recommended; Might break)                                        | [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/lightswitch05/aggressive-tracking) |

### [Firebog](https://firebog.net/)

| Type   |                                      Blocking Type                                       |                                          Copy Link                                           |
|--------|:----------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------:|
| Ticked | Suspicious + Ads + Tracking & Telemetry + Malicious + Other (Usually no false-positives) | [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/firebog/aio) |
