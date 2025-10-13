---
title: "Digitale Souveränität"
meta_title: ""
description: ""
draft: false
---

In einer Zeit, in der technologische Abhängigkeiten wachsen und proprietäre Plattformen immer mehr Kontrolle ausüben, wird digitale Souveränität zur zentralen Frage:
Wie können wir Systeme gestalten, die nicht nur effizient, sondern auch frei, nachvollziehbar und nachhaltig sind? Wie wird Datenschutz gewährleistet?
Ich glaube, offene Standards, verantwortungsbewusste Softwareentwicklung und dezentrale (föderierte) Architekturen entscheidende Bausteine dafür sind.

<!-- {{< toc >}} -->

## Allgemeines

Als Privatperson versuche ich digital unabhängig von den großen (amerikanischen) Konzernen zu sein. Dies versuche ich durch folgende Strategien umzusetzen:"
* Self-Hosting: ich installiere und nutze bevorzugt Webanwendungen auf der von mir kontrollierten Infrastruktur (z. B. meinem Homeserver oder NAS zu Hause)
* Software (Programme und Apps): Ich nutze dort, wo es möglich ist, Open Source Software.
* Cloud-Dienste: Ich bevorzuge europäische Alternativen zu den großen amerikanischen Diensten. Sollte noch keine europäische Alternative existieren, so greife ich möglichst auf Dienste zurück, die durch gemeinnützige Stiftungen oder ähnliches finanziert werden.

Bei manchen Dingen ist es leicht, eine Alternative zu nutzen (eine andere Suchmaschine, Self-Hosted-Anwendungen, statt Cloud-Apps). Bei Social Media und Messengern ist dies schon deutlich schwerer, da die Akzeptanz davon abhängt, ob schon eine kritische Masse an Mitmachenden erreicht wurde. Doch wenn niemand damit beginnt, wie soll dann die kritische Masse erreicht werden? Außerdem wurde das auch schon bei den alten Diensten, wie ICQ, Skype, etc. befürchtet - und wo sind diese Dienste heute? Ich habe damit begonnen, eine Alternative zu nutzen und versuche, meinen Kommunikationskreis davon zu überzeugen. Man muss ja nicht Facebook, WhatsApp und co. sofort aufhören zu nutzen!

In unserem Haushalt sind die verschiedenen Ökosysteme zu Hause: Windows, Linux, Android und iOS. Aus diesem Grund ist bei der meisten Software wichtig, dass sie auf allen Systemen lauffähig sind, entweder als (Progressive-)Web-Anwendung/PWA (bevorzugt) oder mit einer gut funktionierenden und performanten App.

## E-Mail

Als E-Mail-Anbieter nutze ich den deutschen Anbieter [mailbox](mailbox.org) mit meiner eigenen Domäne. Der Dienst ist **nicht** kostenfrei, aber für einen fairen Monatsbetrag erhält man eine komplette Workgroup-Suite (E-Mail, Kalender, Adressbuch, Aufgaben, OpenTalk-Meetings, und noch mehr). Dabei können mehrere Konten zu einer Familien-Gruppe zusammengefasst werden, die sich die Ressourcen (insbesondere Gruppenkalender) teilen können. mailbox ist durch das Bundesamt für Sicherheit in der Informationstechnik (BSI) [ausgezeichnet](https://mailbox.org/de/news/bsi-verleiht-mailbox-den-goldstatus/) worden. Wer sich beruflich mit Microsoft Exchange auskennt, der wird sich sofort zurechtfinden, da die Software-Basis [Open-Xchange (OX)](https://www.open-xchange.com/) ist. Es werden im wesentlichen offene Standards/Protokolle (IMAP, SMTP, CalDAV, CardDAV, Webcal, WebDAV) eingesetzt und mit Open Source Software betrieben.

## Messenger

* WhatsApp: [Signal](https://signal.org/), [Threema](https://threema.com)

## Social Media

Wie wäre es, wenn jede Plattform mit jeder interagieren könnte? z. B. einen Instagram-Beitrag in Facebook kommentieren; sehen, wenn mein Facebook-Post auf X geteilt wird. Wie wäre es, wenn mir nicht ein Algorithmus für mich entscheidet, was ich sehen möchte? Wie wäre es, wenn es keine Werbung gäbe und kein großer amerikanischer Konzern dahinterstehen würde, für den **ich** das Produkt bin? 

All dies ist mit dem föderierten Fediverse möglich! Ein tolles [Erklärvideo von Elena Rossini](https://videos.elenarossini.com/w/64VuNCccZNrP4u9MfgbhkN) helfen Dir, einen ersten Überblick über das Fediverse zu erhalten. Bei [jointhefediverse.net](https://jointhefediverse.net/) findest Du Deinen eigenen Einstieg. Lass Dich am Anfang nicht von der Wahl der Anwendung oder des Servers/der Instanz abschrecken: wähle aus dem Bauch heraus, was Du glaubst, was am besten zu Dir passt. 

Alternativen zu den bekannten Anwendungen:
* Twitter/X: [Mastodon](https://joinmastodon.org/)
* Facebook: [Friendica](https://friendi.ca/)
* Instagram: [PixelFed](https://pixelfed.org/)
* YouTube: [PeerTube](https://joinpeertube.org/)
* TikTok: [Loops](https://loops.video/)

Ich nutze beispielsweise Mastodon auf der Instanz [mastodon.social](https://mastodon.social); meinen bisherigen Twitter/X-Account habe ich ohnehin kaum benutzt, weshalb ich ihn problemlos stilllegen konnte. Da ich selbst erst neu im Fediverse bin, habe ich die anderen Alterantiven noch nicht getestet; ich möchte gleichzeitig aber auch ein Social-Media-Detoxing betreiben - also das "Entgiften" und damit weglassen von der immerwährenden Social-Media-Berieselung mit dem endlosen Durchscrollen.

## Sonstige Open-Source-Software, die ich einsetze

* [Bitwarden](https://bitwarden.com): Passwortmanager für alle Plattformen mit der Möglichkeit auch das Backend/den Server selbst zu hosten (per [Vaultwarden](https://github.com/dani-garcia/vaultwarden))
* [Paperless-ngx](https://docs.paperless-ngx.com/): Dokumenten-Management-System
* [Actual Budget](https://actualbudget.org/): Haushaltsbuch/persönlicher Finanzstatus
* [Joplin](https://joplinapp.org/): persönliche Wissensdatenbank und Notizen, synchronisiert z. B. mit WebDAV auf meiner NAS
* [Stratum](https://stratumauth.com/): Zweifaktor-Authentifizierungs-App (2FA) mit Backup-Möglichkeit
* [Thunderbird](https://www.thunderbird.net/): E-Mail-Client, sowohl mobil auf ANdroid, als auch auf dem Desktop (Windows und Linux)
* [DAVx<sup>5</sup>](https://www.davx5.com/): zur bidirektionalen Unterstützung von CalDAV (offener Standard für Kalender), CardDAV (offener Standard für Kontakte) unter Android; Funfact: das iPhone hat native Unterstützung für diese offenen Protokolle, obwohl Apple sonst eher proprietär ist.
* [ICSx<sup>5</sup>](https://icsx5.bitfire.at/): zur Unterstützung von lesenden (Web-)Kalendern auf Basis von Webcal oder iCal (arbeitet zusammen mit DAVx<sup>5</sup>)

## Web-Anwendungen, die ich gerne nutze

* Suchmaschine (Google-Ersatz): [Qwant](https://www.qwant.com/) aus Frankreich, [Ecosia](https://www.ecosia.org/) aus Berlin - beide investieren in einen eigenen gemeinsamen [europäischen Suchindex](https://de.blog.ecosia.org/eusp/), insbesondere Unabhängig von Google und Microsoft Bing
* Online-Übersetzer mit KI: [DeepL](https://www.deepl.com/) aus Köln

## Self-Hosting

Aktuell nutze ich zum Self-Hosting eine mittlerweile betagtere NAS vom Typ Synology DS216+II. Entweder nutze ich die bereitgestellten Anwendungen von Synology oder installiere Software als Docker-Container.

Synology-Software, die ich nutze:
* Synology Photos
* Synology Drive
* Hyper Backup zum Offsite-Backup in den Synology C2 Cloud-Speicher
* Cloud-Sync zum Synchronisieren von Dateien mit Microsoft OneDrive
* SSO-Server zur Anmeldung von anderen Anwendungen mit meinen Synology-Usern

Anwendungen, die ich als Docker-Container betreibe:
* [AdGuard Home](https://adguard.com/de/adguard-home/overview.html): ein DNS-Filterserver, um Werbung schädliche Websites von allen Heimgeräten fernzuhalten
* [Paperless-ngx](https://docs.paperless-ngx.com/): mein Dokumentenarchiv, das sich leicht selbst befüllt. Alles was ich an Belegen per E-Mail erhalte, wird automatisch archiviert; Papierdokumente per Post werden sofort nach dem Empfang mit einem Epson WorkForce ES-580W Dokumentenscanner eingelesen und automatisch archiviert.
* [Actual Budget](https://actualbudget.org/): unser digitales Haushaltsbuch und Budgetplaner
* [Speedtest Tracker](https://docs.speedtest-tracker.dev/): zur kontinuierlichen Messung und Aufzeichnung meiner Internetgeschwindigkeiten alle 4 Stunden/6 mal am Tag
* [Uptime Kuma](https://uptime.kuma.pet/): Software zur Überwachung meiner selbsgehosteten Anwendungen und Dienste
* [Homepage](https://gethomepage.dev/): um alle meine Netzwerkgeräte und Dienste auf einer zentralen Übersichtsseite zu haben
* [Portainer](https://www.portainer.io/): zur Verwaltung der Docker-Container selbst

Als Router ins Internet verwende ich eine ganz normale FritzBox 7590 an einem Vodafone DSL-Anschluss - der Glasfaserausbau zieht sich leider hin.

Für meinen Webspace, die Domänen und den DNS verwende ich die Dienste von [hosting.de](https://www.hosting.de).

## Anwendungen, für dich ich noch keine Alternative nutze

* Paypal: das europäische Wero ist meiner Meinung nach noch weit davon entfernt, eine PayPal-Alternative zu sein. (kostenfreie) SEPA-Echtzeitüberweisungen sind aktuell am naheliegendsten, schnell jemandem Geld per IBAN zu senden (z. B. bei Kleinanzeigenkäufen vor Ort)
* GitHub: bisher war ich zu Faul, eine Alternative zu nutzen. GitHub gehört mittlerweile zu Microsoft, die Alternative GitLab (ursprünglich aus der Ukraine, anschließend eine niederländische B. V.) ist zwischenzeitlich auch eine amerikanische Firma (Inc.) mit Sitz in geworden - wenigstens könnte es selbst gehostet werden, da die Basissoftware Open Source ist. Ansonsten bleibt noch Gitea übrig.
* Amazon: Shopping, Alexa, Prime Video, Kindle (Unlimited), Music (Unlimited), etc. => ich bin komplett im Vendor-Lockin verloren :-/
* Microsoft Office/Microsoft 365 Family: egal ob iPhone, Android oder Windows - Office ist bekannt, integriert (mit OneDrive) und funktioniert unter Linux und Chromebook im Browser. LibreOffice wäre als Desktop-Alternative (unter Windows und Linux) in Verbindung mit Nextcloud gut verwendbar, der Android-Client ist jedoch noch zu rudimentär und unter iOS schlichtweg nicht vorhanden.
* diverse Smart Home Produkte: IKEA Trasfri, TP-Link KASA, Netatmo, Bosch Smart Home, iRobit Roomba, Gardena Gartenbewässerung, AP-Systems Balkonkraftwerk-Wechselrichter - für all das existieren keine guten Bindings für Home Assistant oder die Einrichtung ist mir zu aufwändig.
* ChatGPT: Pest oder Cholera? - der KI-Markt wird dominiert von den amerikanischen Big Playern OpenAI (ChatGPT), Anthropic (Claude), Meta (MetaAI in Facebook, Instagram, WhatsApp und co.), Microsoft (Copilot), und Google (Gemini) - und aus China (DeepSeek). Das Macht einer KI liegt in den Modellen, da helfen selbst Open Source Bibliotheken (wie [Ollama](https://ollama.com/)), die alle Modelle integrieren können nur bedingt. Auch wenn Meta sich stark im Bereich der Open Source Modelle betätigt, so geht es auch hier höchstwahrscheinlich um die Sicherung der Vormachtstellung und damit dem "Steuern des Wissens".
* Bring!: eine clevere Einkaufsleisten-App, die wir im Haushalt teilen können. Hier befinden sich auch die wöchentlichen Prospekte der lokalen Händler in digitaler Form an einem Ort. Mit [KitchenOwl](https://docs.kitchenowl.org/) existiert ein Open Source Self-hosted Klon, aber ohne die Werbeprospekte.
