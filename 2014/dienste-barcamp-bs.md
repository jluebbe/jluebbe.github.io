---
author: Jan Lübbe
title: Netzdienste selbst hosten
---

# Netzdienste selbst hosten
## Nicht nur Webseiten!

---

# Warum?

# Was?

# Wie?

---

# Warum?

![text](free.png)

---
= data-z='-1000'

# Warum?
- Unabhängigkeit
  - Daten (und Metadaten!) unter eigener Kontrolle
  - Dezentralisierung
- Neues lernen
- Communities unterstützen

---

# Was?

- GitHub
- Mail
- DNS & DynDNS
- XMPP (Jabber)
- Video-/Audiokonferenz
- VPN
- "Cloud"
- Virtualisierung

---
= data-z='-1000'

## GitHub

- [GitLab](https://about.gitlab.com/) statt GitHub
  - Repo-Verwaltung
  - Wiki
  - Issue-Tracking

---
= data-z='-1000'

## Mail

- Postfix, Dovecot, Roundcube, Mailman, Amavis
- Viel Aufwand! → am besten für viele Nutzer
  - Spam
  - Fehlkonfigurationen führen zu Mailverlust!
- Oder fertig vorbereitet: z.B. [Kolab](http://kolab.org/) oder [SOGo](http://www.sogo.nu/)

---
= data-z='-1000'

## DNS & DynDNS

- Bind 9
  - DNSSEC, DANE
- DynDNS: [nsupdate.info](https://nsupdate.info/) / [stratum0.net](https://stratum0.net/)
- Mit jemand anderem "secondaries tauschen"

---
= data-z='-1000'

## XMPP (Jabber)

- (Gruppen-)Chat
- Federated
- Android-Client: [Conversations](https://github.com/siacs/Conversations)
  (OTR und GPG mit OpenKeychain) oder [ChatSecure](https://chatsecure.org/)
- Server: [prosody](https://prosody.im/) oder [ejabberd](https://www.ejabberd.im/)

---
= data-z='-1000'

## Video-/Audio-Konferenz

- Multi-User-Voice-Chat: [Mumble](http://wiki.mumble.info/wiki/Main_Page)
- Video-Konferenz im Browser: [palava.tv](https://palava.tv/)
- VoIP: [ostel.co](https://ostel.co/) (oder z.B. [asterisk](http://www.asterisk.org/))

---
= data-z='-1000'

## VPN

- Sicherer Netzzugang von überall
- [OpenVPN](https://openvpn.net/) über TCP oder UDP
- [iodine](http://code.kryo.se/iodine/) als DNS-Tunnel

---
= data-z='-1000'

## "Cloud"

- [OwnCloud](http://owncloud.org/): DropBox, Kalender, Adressen, ...
- [Etherpad](http://etherpad.org/): Multiuser-Texteditor
- [ZeroBin](http://sebsauvage.net/wiki/doku.php?id=php:zerobin): Verschlüsselter Textsnipsel-Austausch
- Social: [Friencia](http://friendica.com/), [Diaspora](https://joindiaspora.com/), [pump.io](http://pump.io/)

---
= data-z='-1000'

## Virtualisierung

- Als Basis für die anderen Dienste
- Physikalischen Server gemeinsam nutzen
- libvirt (KVM oder Xen)
  - [virt-manager](http://virt-manager.org/) als GUI per SSH
  - [kimchi](https://github.com/kimchi-project/kimchi) als Web-Interface

---

# Wie?

- Jeder betreibt 1+ Dienste
- Gemeinsames (virtualisiertes) Hosting
- Es gibt viele gut Anleitungen
- Oder: Im nächsten Hackerspace mitmachen

---

## Danke!
# Diskussion?

---

## Links aus der Diskussion

- https://git-annex.branchable.com/
- http://seafile.com/en/home/
- https://posteo.de/de
- https://mailbox.org/
- https://workaround.org/ispmail

