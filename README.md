# Awesome-File-Sharing

## Top File Sharing Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Local Network Transfers, Cloud Link Sharing & Self-Hosted Alternatives*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **File Sharing**. These tools enable users to send files between devices—locally over Wi-Fi, through cloud links, or peer-to-peer—without relying on email attachments or USB drives.



**Examples** include AirDrop, Pushbullet, WeTransfer, Send Anywhere, SHAREit, Xender, Dropbox Transfer, Smash, Box, and Filemail (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local-first transfers, and transparent file sharing—ideal for privacy-conscious users, teams without cloud dependency, and developers building custom transfer workflows. The open-source landscape is anchored by **LocalSend** (the most popular AirDrop alternative with 70k+ GitHub stars) , alongside browser-based tools like **PairDrop** and **SnapDrop**, and CLI utilities like **croc** for terminal-native transfers.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AirDrop](https://support.apple.com/en-us/102376)**  

  Apple's native peer-to-peer file sharing across iPhone, iPad, and Mac. Uses Bluetooth for discovery and Wi-Fi for transfer with end-to-end encryption. No setup required within the Apple ecosystem, but limited to Apple devices.



- **[Pushbullet](https://www.pushbullet.com/)**  

  Cross-device notification and file sharing tool for Android, iOS, Windows, and web. Free tier has monthly push limits; Pro ($4.99/month) removes restrictions . Best for users who want notification mirroring alongside file transfer.



- **[WeTransfer](https://wetransfer.com/)**  

  Cloud-based large file transfer service. Free tier now offers 3 GB total per month with a maximum of 10 transfers, each expiring after 3 days . Paid plans increase limits. Best for occasional one-off transfers without account creation.



- **[Send Anywhere](https://send-anywhere.com/)**  

  Cross-platform file transfer with a 6-digit key system for direct device-to-device sending. Free tier supports up to 50 GB real-time transfers or 10 GB share links . Paid tiers extend limits. Best for users who want key-based transfers without cloud storage.



- **[SHAREit](https://www.ushareit.com/)**  

  Free cross-platform file transfer app using local Wi-Fi hotspot for direct device-to-device sending. Advertises speeds up to 20 MB/s with no file size limits . Ad-supported; users frequently report intrusive ads . Best for quick local transfers when ads are tolerable.



- **[Xender](https://www.xender.com/)**  

  Free file transfer app for iOS, Android, and PC. Works offline via local Wi-Fi, supports cross-platform transfers between iOS and Android, and includes a built-in music player . Ad-supported.



- **[Dropbox Transfer](https://www.dropbox.com/features/share/file-transfer)**  

  File transfer feature available to all Dropbox users. Free Basic plan allows up to 2 GB per transfer; Plus allows 50 GB; Advanced allows 100 GB . Best for users already within the Dropbox ecosystem.



- **[Smash](https://fromsmash.com/)**  

  File transfer service with a free tier allowing 2 GB per transfer (larger files are queued with lower priority). Paid plans extend to 250 GB (Pro) or 1 TB (Team) . Best for occasional large transfers with a generous free tier.



- **[Box](https://www.box.com/)**  

  Enterprise content management and file sharing platform. Free personal plan offers 10 GB storage but only 250 MB per file; Personal Pro ($14/month) offers 100 GB with 5 GB file limit . Best for document-focused workflows rather than large media transfers.



- **[Filemail](https://www.filemail.com/)**  

  File transfer service with a free tier allowing 5 GB per transfer, up to 2 transfers per 24 hours, with 7-day file retention . Paid plans extend limits. Best for sending files larger than email allows without an account.



## Open-Source GitHub Projects



- **[LocalSend](https://github.com/localsend/localsend)**  

  The leading open-source AirDrop alternative. Cross-platform (Windows, macOS, Linux, Android, iOS) with end-to-end HTTPS encryption, no internet required, no accounts, no ads, and no tracking. 70k+ GitHub stars and 5M+ downloads . Zero configuration—install, select files, tap the nearby device. Best for users who want a private, ad-free local transfer experience across all platforms.



- **[PairDrop](https://github.com/schlagmichdoch/PairDrop)**  

  Browser-based local file sharing inspired by AirDrop, forked from SnapDrop. Works on any device with a modern web browser. Features persistent device pairing via 6-digit code or QR code, temporary public rooms for internet transfers through NAT, and multi-file ZIP downloads . Best for users who want AirDrop-like functionality without installing an app.



- **[SnapDrop](https://github.com/RobinLinus/snapdrop)**  

  The original browser-based local file sharing PWA inspired by AirDrop. Devices on the same network discover each other automatically; files transfer peer-to-peer via WebRTC. No installation or account required . Best for quick, ephemeral transfers where installing software isn't practical.



- **[croc](https://github.com/schollz/croc)**  

  CLI-based file transfer tool that works across any two computers. Generates a memorable code phrase for the recipient. Uses PAKE encryption and supports relay-based transfers through NAT, with self-hosted relay options for privacy . Best for developers and terminal users who want secure, scriptable file transfers.



- **[KDE Connect](https://github.com/KDE/kdeconnect-kde)**  

  Multi-platform device integration tool for Linux, Android, Windows, and macOS. Enables file and URL sharing, shared clipboard, notification sync, and remote input over local Wi-Fi with TLS encryption . Best for Linux users who want deep phone-desktop integration beyond just file transfer.



- **[Warpinator](https://github.com/linuxmint/warpinator)**  

  Linux Mint's local network file transfer tool. Uses mDNS for discovery and TLS for secure transfers on the same subnet. Simple GTK interface . Best for Linux users on the same network who want a native-feeling, no-frills transfer tool.



- **[FilePizza](https://github.com/kern/filepizza)**  

  Browser-based peer-to-peer file transfer using WebRTC. Files never touch a server—they stream directly from uploader to downloader. Supports multiple simultaneous downloaders, password protection, and streaming downloads . Best for sharing files with others without cloud storage or software installation.



- **[OnionShare](https://github.com/onionshare/onionshare)**  

  Anonymous file sharing over the Tor network. Hosts files from your computer as a temporary onion service; recipients download via Tor Browser. Supports receive mode, public mode, and website mode . Best for anonymity-critical transfers where hiding IP addresses matters.



### Additional Strong Open-Source Options



- **File.pizza** — Minimal web-based P2P transfer. Drag a file, share the link, done. Files transfer directly between browsers with no server storage . Best for one-off transfers when both parties are online.

- **Warpinator forks** — Community implementations like Sovereign Warpinator Engine in Rust offer higher throughput and modern protocol support .

- **Frameworks for building custom systems**: Combine **LocalSend** for GUI-based local transfers with **croc** for CLI automation, **PairDrop** for browser-based ad-hoc sharing, and **OnionShare** when anonymity is required. For self-hosted relay infrastructure, **croc** supports custom relay servers.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Free tiers of SaaS file sharing services have significant limits (file size, transfer frequency, retention period); verify current terms before relying on them for important transfers.

- Self-hosted solutions require proper network configuration (firewall, port forwarding for internet transfers) and security review.

- Ad-supported apps like SHAREit may include trackers or intrusive advertising; review privacy policies before installation .



---



**Made for privacy-conscious users, developers, IT administrators, and anyone who needs to move files without the cloud.**  

Let's make file sharing more open, local-first, and accessible.
