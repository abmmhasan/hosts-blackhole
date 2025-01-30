# Hosts Blackhole

If you are using any custom ad-blocking servers at home (like Pi-Hole, AdGuard etc.) or any servers that accepts ABP
style or Host file style block list you can use ad list provided here.
Just copy the link address from **Copy Link** column and add to your gravity source.
Also, it'd be great if you can set up schedular to update on daily basis.

## List of Hosts Files

Currently, 16 different variants from 4 sources are provided. All the file links, are direct file link to this Github
repo.
> Files are collected from different sources on daily basis.

### [OISD](https://oisd.nl/)

[![OISD Hosts collector](https://github.com/abmmhasan/hosts-blackhole/actions/workflows/oisd.yml/badge.svg)](https://github.com/abmmhasan/hosts-blackhole/actions/workflows/oisd.yml)

| Type  | Format |                                                                        Blocking Type                                                                         |                                           Copy Link                                            |
|:------|:-------|:------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------:|
| Small | ABP    |                                                                             Ads                                                                              |   [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/oisd/ads)    |
| Big   | ABP    | Ads, Phishing, Malvertising, Malware, Spyware, Ransomware, CryptoJacking, Scam, ... Telemetry/Analytics/Tracking (Where not needed for proper functionality) | [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/oisd/security) |
| NSFW  | ABP    |                                                                      Porn, Shock, adult                                                                      |   [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/oisd/nsfw)   |

### [Steven Black](https://github.com/StevenBlack/hosts)

[![Steven Black list collector](https://github.com/abmmhasan/hosts-blackhole/actions/workflows/steven-black.yml/badge.svg)](https://github.com/abmmhasan/hosts-blackhole/actions/workflows/steven-black.yml)

| Type        | Format |                  Blocking Type                  |                                                 Copy Link                                                 |
|:------------|:-------|:-----------------------------------------------:|:---------------------------------------------------------------------------------------------------------:|
| Unified     | Host   |                  Ads + Malware                  |   [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/steven-black/unified)   |
| Social      | Host   |                  Social Media                   |   [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/steven-black/social)    |
| Porn        | Host   |                   Pornography                   |    [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/steven-black/porn)     |
| Gambling    | Host   |                    Gambling                     |  [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/steven-black/gambling)   |
| Fake        | Host   |                    Fake News                    |  [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/steven-black/fake-news)  |
| Non Unified | Host   |         Social + Porn + Gambling + Fake         | [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/steven-black/non-unified) |
| Everything  | Host   | Ads + Malware + Social + Porn + Gambling + Fake |     [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/steven-black/all)     |

### [Lightswitch05](https://www.github.developerdan.com/hosts/)

[![Lightswitch05 list collector](https://github.com/abmmhasan/hosts-blackhole/actions/workflows/lightswitch.yml/badge.svg)](https://github.com/abmmhasan/hosts-blackhole/actions/workflows/lightswitch.yml)

| Type                | Format |                                                          Blocking Type                                                          |                                                     Copy Link                                                      |
|:--------------------|:-------|:-------------------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------:|
| Ads & Tracking      | Host   |                                                         Ads + Tracking                                                          |    [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/lightswitch05/ads-tracking)     |
| Facebook            | Host   |                                            Facebook, Messenger, Instagram, WhatsApp                                             |      [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/lightswitch05/facebook)       |
| AMP                 | Host   | [Google's Accelerated Mobile Pages (AMP)](https://www.theregister.co.uk/2017/05/19/open_source_insider_google_amp_bad_bad_bad/) |     [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/lightswitch05/google-amp)      |
| Dating              | Host   |                                                         Dating Services                                                         |       [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/lightswitch05/dating)        |
| Aggressive Tracking | Host   |                                       Aggressive tracking (Not Recommended; Might break)                                        | [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/lightswitch05/aggressive-tracking) |

### [Firebog](https://firebog.net/)

[![Firebog list collector](https://github.com/abmmhasan/hosts-blackhole/actions/workflows/firebog.yml/badge.svg)](https://github.com/abmmhasan/hosts-blackhole/actions/workflows/firebog.yml)

| Type       | Format |    Blocking Type     |                                              Copy Link                                              |
|:-----------|:-------|:--------------------:|:---------------------------------------------------------------------------------------------------:|
| Suspicious | Host   |      Suspicious      | [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/firebog/suspicious) |
| Ads        | Host   |     Advertising      |    [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/firebog/ads)     |
| malicious  | Host   |      Malicious       | [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/firebog/malicious)  |
| trackers   | Host   | Tracking & Telemetry |  [Link](https://raw.githubusercontent.com/abmmhasan/hosts-blackhole/master/hosts/firebog/trackers)  |
