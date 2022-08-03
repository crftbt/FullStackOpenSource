
  
# [Full Stack](https://wikipedia.org/wiki/Solution_stack) [Open Source](https://wikipedia.org/wiki/Open_source) Hardware and Software

[![Reddit](https://www.redditstatic.com/desktop2x/img/favicon/favicon-32x32.png)](https://reddit.com/r/FullStackOpenSource/) [![Github](https://github.githubassets.com/favicons/favicon-dark.png)](https://github.com/crftbt/FullStackOpenSource/)

# Hardware

## Coreboot [Laptops](https://wikipedia.org/wiki/Laptop)

| Clearnet Website | Wikipedia | Size | Price |
| - | - | - | - |
| [Star Labs Systems](https://us.starlabs.systems/) | - | 11", 14" | $480 - $930 |
| [ThinkPenguin](https://www.thinkpenguin.com/) | - | 14" | $950 |
| [System76](https://system76.com/) | [System76](https://wikipedia.org/wiki/System76) | 14", 15", 17" | $1000 - $2200 |
| [Purism](https://puri.sm/) | [Purism_(company)](https://wikipedia.org/wiki/Purism_(company)) | 14" | $1370 |

# Software

## [Firmware Implementations](https://wikipedia.org/wiki/Firmware)

| Clearnet Website | Wikipedia | Source Code | Closed Source [Binary Blobs](https://wikipedia.org/wiki/Binary_blob) |
| - | - | - | - |
| [Coreboot](https://coreboot.org/) | [Coreboot](https://wikipedia.org/wiki/Coreboot) | <https://review.coreboot.org/plugins/gitiles/> | :x: Yes  |

## [Operating Systems](https://wikipedia.org/wiki/Operating_system)
### [Linux](https://wikipedia.org/wiki/Linux)

| Clearnet Website | Wikipedia | Source Code | Closed Source [Binary Blobs](https://wikipedia.org/wiki/Binary_blob) |
| - | - | - | - |
| [PureOS](https://pureos.net/) | [PureOS](https://wikipedia.org/wiki/PureOS) | <https://source.puri.sm/explore> | :heavy_check_mark: No |
| [Qubes OS](https://qubes-os.org/) | [Qubes_OS](https://wikipedia.org/wiki/Qubes_OS) | <https://github.com/QubesOS/> | :x: Yes |

### [Android](https://wikipedia.org/wiki/Android_(operating_system))

| Clearnet Website | Wikipedia | Source Code | Verified Boot |
| - | - | - | - |
| [CalyxOS](https://calyxos.org/) | [CalyxOS](https://wikipedia.org/wiki/CalyxOS) | <https://gitlab.com/CalyxOS> | :heavy_check_mark: Yes |
| [LineageOS](https://www.lineageos.org/) | [LineageOS](https://wikipedia.org/wiki/LineageOS) | <https://github.com/LineageOS> | :x: No

##### References:
##### - https://wikipedia.org/wiki/Security-focused_operating_system

## Applications

### Android Application Manager

| Clearnet Website | Wikipedia | Source Code |
| - | - | - |
| [F-Droid](https://f-droid.org/) | [F-Droid](https://en.wikipedia.org/wiki/F-Droid) | <https://gitlab.com/fdroid> |

### [Web Browsers](https://wikipedia.org/wiki/Web_browser)

| Clearnet Website | Wikipedia | Source Code | [Engine](https://wikipedia.org/wiki/Browser_engine) | Linux | Android | F-Droid |
| - | - | - | - | - | - | - |
| [Tor Browser](https://www.torproject.org/) | [Tor_Browser](https://wikipedia.org/wiki/Tor_(network)#Tor_Browser) | <https://gitweb.torproject.org/tor-browser.git/> | [Mozilla](https://wikipedia.org/wiki/Mozilla) [Gecko](https://wikipedia.org/wiki/Gecko_(software)) | :heavy_check_mark: Yes | :heavy_check_mark: Yes | Yes |
| [Brave](https://brave.com/) | [Brave_(web_browser)](https://wikipedia.org/wiki/Brave_(web_browser))| <https://github.com/brave/brave-browser> | Google [Blink](https://wikipedia.org/wiki/Blink_(browser_engine)) |:heavy_check_mark: Yes | :heavy_check_mark: Yes | :x: No |
| [LibreWolf](https://librewolf.net/) | - | <https://gitlab.com/librewolf-community> | [Mozilla](https://wikipedia.org/wiki/Mozilla) [Gecko](https://wikipedia.org/wiki/Gecko_(software)) |:heavy_check_mark: Yes | :x: No | :x: No |
| Focus | | | [Mozilla](https://wikipedia.org/wiki/Mozilla) [Gecko](https://wikipedia.org/wiki/Gecko_(software)) |
| Mull | | | [Mozilla](https://wikipedia.org/wiki/Mozilla) [Gecko](https://wikipedia.org/wiki/Gecko_(software)) |
| Bromite | | | Google [Blink](https://wikipedia.org/wiki/Blink_(browser_engine)) |

##### References: 
##### - https://privacytests.org/ 
##### - https://divestos.org/index.php?page=browsers

### Messaging - Decentralized and [End to End Encrypted](https://wikipedia.org/wiki/End-to-end_encryption)

| Clearnet Website | Wikipedia | Source Code | Cryptography | Protocol | Network | Linux | Android | F-Droid | Offline Cache | Last Audited |
| - | - | - | - | - | - | - | - | - | - | - |
| [Session](https://getsession.org/) | - | <https://github.com/oxen-io< | [Libsodium](https://github.com/jedisct1/libsodium) | [Session](https://getsession.org/blog/session-protocol-technical-information) DRA | [Oxen](https://oxen.io/) | :heavy_check_mark: Yes | :heavy_check_mark: Yes | [Yes](https://fdroid.getsession.org/) | | [2021.05.04](https://blog.quarkslab.com/resources/2021-05-04_audit-of-session-secure-messaging-application/20-08-Oxen-REP-v1.4.pdf) |
| [Briar](https://briarproject.org/) | [Briar_(software)](https://wikipedia.org/wiki/Briar_(software)) | <https://code.briarproject.org/briar/briar> | | P2P | Bluetooh/WiFi/Tor | :x: No | :heavy_check_mark: Yes | :heavy_check_mark: [Yes](https://f-droid.org/en/packages/org.briarproject.briar.android/) | | [2017.03.20](https://briarproject.org/news/2017-beta-released-security-audit/) |
| [Status](https://status.im/) | - | <https://github.com/status-im> | | Waku P2P | | :heavy_check_mark: Yes | :heavy_check_mark: Yes | :heavy_check_mark: [Yes](https://f-droid.org/packages/im.status.ethereum/) | 30 Days | [2019.09](https://github.com/status-im/status-security#audits)
| [Cwtch](https://cwtch.im/) | - | <https://git.openprivacy.ca/cwtch.im> | | Cwtch | [Tor](https://wikipedia.org/wiki/Tor_(network)) | :heavy_check_mark: Yes | :heavy_check_mark: Yes | :x: No |
