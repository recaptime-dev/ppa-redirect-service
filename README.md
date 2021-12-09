# Recap Time's Personal Package Archives - Redirect Service at CF Pages

[![Powered by CF Pages](https://img.shields.io/badge/Powered%20by-Cloudflare%20Pages-orange?style=for-the-badge&logo=cloudflare)](https://pages.cloudflare.com//?rref=shieldsio-custom-badge&source=github:RecapTime/ppa-redirect-service)
[![Packages hosted @ GitLab.com](https://img.shields.io/badge/Packages%20hosted%20on-GitLab%20SaaS%20as%20Git%20LFS%20blobs-380D75?style=for-the-badge&logo=gitlab)](https://gitlab.com/RecapTime/infra/packages-store)
[![Mirrors on SourceForge](https://img.shields.io/badge/Mirrors%20available%20on-SourceForge-orange?logo=sourceforge&style=for-the-badge)](https://sourceforge.net/p/recaptime-package-store)

This repository only stores the necessary files for our own package repository to work for apt-based clients, including `Packages.gz` and some GPG stuff.

## Where are the deb/apk files?

All of them are in [GitLab SaaS](https://gitlab.com/RecapTime/infra/packages-store), stored as either Git LFS blobs or in GitLab Package Registry, with mirrors available at [SourceForge](https://sourceforge.net/p/recaptime-package-store). They are being automagically redirected through some `_redirects` magic.

## Submitting copyright takedown requests

Please redirect your takedown requests to our squad lead below instead of GitLab/GitHub/CloudFlare Support:

```txt
Andrei Jiroh E. Halili
Package Repository Maintainer / Squad Lead, Recap Time
Email: andreijiroh@recaptime.tk
Report-Form: https://reportabuse.rtapp.tk
Telegram: https://t.me/ajhalili2006
```
