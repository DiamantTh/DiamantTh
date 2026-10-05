# DiamantTh / DiamantThomy / DT

Ich baue, hoste und zerlege gerne Dinge selbst: freie Software, kleine und größere Web-Anwendungen, Minecraft-Mods, Server-Dienste und technische Experimente. Nicht alles davon soll ein fertiges Produkt werden. Vieles beginnt mit einer Frage wie: *Warum ist das an einen Anbieter gebunden – und wie würde eine offene Variante aussehen?*

<p>
  <a href="https://github.com/DiamantTh"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-DiamantTh-181717?style=for-the-badge&logo=github" /></a>
  <a href="https://git.diath.systems"><img alt="Eigener Git-Dienst" src="https://img.shields.io/badge/Git-diath.systems-F05032?style=for-the-badge&logo=git" /></a>
  <a href="https://keybase.io/diamantthomy"><img alt="Keybase" src="https://img.shields.io/badge/Keybase-diamantthomy-33A0FF?style=for-the-badge&logo=keybase" /></a>
  <a href="https://x.com/DiamantThomy"><img alt="X" src="https://img.shields.io/badge/X-%40DiamantThomy-000000?style=for-the-badge&logo=x" /></a>
  <a href="https://www.reddit.com/user/diamantth/"><img alt="Reddit" src="https://img.shields.io/badge/Reddit-u%2Fdiamantth-FF4500?style=for-the-badge&logo=reddit" /></a>
  <a href="https://www.youtube.com/@DiamantTh"><img alt="YouTube" src="https://img.shields.io/badge/YouTube-%40DiamantTh-FF0000?style=for-the-badge&logo=youtube" /></a>
  <a href="https://www.twitch.tv/diamantth"><img alt="Twitch" src="https://img.shields.io/badge/Twitch-diamantth-9146FF?style=for-the-badge&logo=twitch" /></a>
  <a href="https://www.facebook.com/DiamantThomy"><img alt="Facebook" src="https://img.shields.io/badge/Facebook-DiamantThomy-1877F2?style=for-the-badge&logo=facebook" /></a>
  <a href="https://suno.com/profile/@diamantth"><img alt="Suno" src="https://img.shields.io/badge/Suno-%40diamantth-171717?style=for-the-badge&logo=suno" /></a>
</p>

## Woran ich gerade praktisch arbeite

Die folgenden Repositories sind keine Hochglanz-Produktpalette. Sie sind Beispiele dafür, was ich selbst ausprobieren, verstehen und offen weiterentwickeln möchte – vom Prototyp bis zu Projekten, die sich noch bewegen dürfen.

| Projekt | Technik | Lizenz | Warum es existiert |
| --- | --- | --- | --- |
| [TowerDNS](https://github.com/DiamantTh/TowerDNS) | PHP, Mezzio, Doctrine, Svelte 5, TypeScript | AGPL-3.0-or-later | Selfhostbare DNS-Verwaltung mit gemeinsamem Kern und Provider-Adaptern, statt DNS unnötig an einen einzelnen Anbieter zu ketten. |
| [ArborPress](https://github.com/DiamantTh/ArborPress) | Python, Quart/ASGI, SQLAlchemy, SvelteKit | AGPL-3.0 | Ein sicherheitsorientiertes Blog-/Mini-CMS-Experiment: WebAuthn/FIDO2-first, getrennte öffentliche und administrative Identitäten, kleiner Core und möglichst wenige externe Laufzeitabhängigkeiten. |
| [HomeClaim](https://github.com/DiamantTh/HomeClaim) | Kotlin/JVM, Gradle, Paper/Folia, SvelteKit | AGPL-3.0 | Ein offenes, modulares Plot- und Regionen-Framework für Minecraft – mit Regionen, Rollen, Policies, Flags und Erweiterungen statt dauerhafter Abhängigkeit von geschlossenen oder kostenpflichtigen Plugins. |
| [Visotaris OPMod](https://github.com/DiamantTh/visotaris-opmod) | Kotlin/JVM, Fabric, Gradle, Svelte | AGPL-3.0-or-later | Eine freie Client-Mod für OPSUCHT. Sie ist eine selbst kontrollierbare, quelloffene Alternative zu einer proprietären Mod und Raum für eigene Komfort- und Auswertungsfunktionen. |
| [LexNova](https://github.com/DiamantTh/LexNova) | PHP, Mezzio, Doctrine DBAL, Svelte 5 | AGPL-3.0-or-later | Ein Experiment für das zentrale Verwalten, Versionieren und Veröffentlichen von Impressums- und Datenschutztexten – mit klarer Kontrolle über Daten und Infrastruktur. |

Daneben interessieren mich Selfhosting, Linux, IRC, offene Webtechnologien, eigene Server und kleine technische Ideen, die nicht erst einen Business-Plan brauchen, um ausprobiert werden zu dürfen. KI-gestützte Entwicklung und „Vibecoding“ nutze ich dabei als Werkzeug: um Ideen schneller anzutesten, neue Stacks zu verstehen und Dinge umzusetzen, die sonst vielleicht bloß Notizen geblieben wären. Das ersetzt weder Nachdenken noch Prüfen – es macht den Weg zum ersten funktionierenden Versuch oft kürzer.

## Freiheit ist mehr als ein öffentliches Repository

Ich bin **Copyleft-first, nicht OSI-first**. Dass Quellcode irgendwo öffentlich liegt, ist für mich nur der Anfang. Entscheidend ist, ob Freiheit langfristig bei Nutzer:innen und Gemeinschaft bleibt: Nachnutzbarkeit, Transparenz, Auditierbarkeit, Kontrolle über die eigene Technik – und ein echter Rückfluss von Verbesserungen.

Deshalb überzeugen mich MIT, BSD, ISC oder Apache-2.0 nicht automatisch, nur weil sie sehr weitgehende Wiederverwendung erlauben. Aus meiner Sicht ist es ein realer Mangel, wenn freie Arbeit problemlos als Fundament eines geschlossenen Produkts dienen kann und relevante Verbesserungen nie zurückkommen. LGPL kann je nach Fall ebenfalls zu wenig sein. GPL und besonders AGPL liegen meiner Vorstellung wesentlich näher.

AGPL ist für mich ein sinnvoller Mindeststandard für viele Web-, Server- und Netzwerkprojekte, weil Dienstbetrieb nicht einfach eine Ausrede sein sollte, Änderungen zu verstecken. Aber auch dort endet die Frage nicht: Was ist mit rein internem oder konzerninternem Betrieb, API- und Proxy-Schichten, künstlich zerlegten Komponenten oder der Betriebssoftware, ohne die ein Dienst praktisch nicht existiert?

Meine Idee einer **Novara-Lizenz** geht in diese Richtung: eine bewusst strengere Copyleft-/Gemeingut-Lizenz, die nicht darauf optimiert ist, möglichst wenige Pflichten zu erzeugen. Sie soll eher prüfen, wie relevante Änderungen, Dienstbetrieb, funktional zusammengehörige Teile, Transparenz und wirtschaftliche Verwertung so geregelt werden können, dass die Gemeinschaft nicht bloß kostenlos vorarbeitet. Ob jede solche Regel noch in eine klassische OSI-Schablone passt, ist für mich nicht der Maßstab. Gerade bei öffentlich finanzierter oder gesellschaftlich wichtiger Software und Infrastruktur halte ich starke Offenlegungs- und Rückflussregeln für sinnvoll.

Kurz: **Copyleft, Rückfluss und Gemeingut vor maximaler kommerzieller Wiederverwendungsfreiheit.**

## Authentifizierung: Passkeys sind kein Luxus

Wo es sinnvoll möglich ist, bevorzuge ich **WebAuthn, FIDO2, Passkeys und Hardware-Sicherheitsschlüssel**. Passwort plus sechsstelliger TOTP-Code ist für mich ein Fallback oder eine Übergangslösung, nicht das Zielbild.

Bei Admin-Oberflächen, Hosting-Panels, Cloud- und Entwicklerdiensten, DNS, Domains und anderer Infrastruktur mit weitreichenden Berechtigungen sollten phishing-resistente Verfahren zum normalen Fundament gehören. Wenn eine technisch anspruchsvolle Plattform im Jahr 2026 ausschließlich Passwort und TOTP anbietet, frage ich mich schon gelegentlich, ob man das Auth-System nicht einmal komplett neu bauen lassen sollte. Das ist technische Frustration, keine persönliche Abrechnung: Die Standards existieren seit Jahren, und die Schutzwirkung ist kein dekoratives Extra.

## Offen, langlebig und zugänglich

Mich beschäftigen digitale Nutzerrechte, offene Standards, Interoperabilität und digitale Selbstbestimmung. Dazu gehören für mich auch Reparierbarkeit, langfristige Nutzbarkeit von Hard- und Software, Kritik an unnötigem DRM und Vendor-Lock-in sowie der Erhalt von Spielen und Software nach Abschaltungen. Offene oder community-getragene Serverstrukturen und Drittanbieter-Server sind dabei keine Randthemen, sondern oft Voraussetzung dafür, dass Technik nicht einfach verschwindet.

Das berührt auch Fragen der gesellschaftlichen Teilhabe. Inklusion, Barrierefreiheit, inklusive Bildung, Teilhabe am Arbeitsleben, faire Arbeitnehmerrechte, Selbstbestimmung und die Rechte von Menschen mit Behinderungen – einschließlich der **UN-Behindertenrechtskonvention (UN-BRK)** – sind Themen, mit denen ich mich beschäftige. Freie Software, offene Schnittstellen und zugängliche Gestaltung lösen nicht alles. Sie können aber unnötige Zugangshürden und Abhängigkeiten verringern und damit digitale Teilhabe realistischer machen.

## Gaming gehört dazu

Gaming ist für mich nicht nur Spielen. Ich mag Mods, Community-Projekte, eigene Server, technische Anpassungen und die Frage, wie Spiele auch außerhalb eines einzelnen Plattformbetreibers weiterleben können. Minecraft und Pokémon gehören dazu, ebenso Linux-Gaming, Modding und die Bewahrung älterer Spiele.

<p>
  <a href="https://steamcommunity.com/id/DiamantThomy"><img alt="Steam" src="https://img.shields.io/badge/Steam-DiamantThomy-171A21?style=for-the-badge&logo=steam" /></a>
  <a href="https://www.gog.com/u/DiamantTh"><img alt="GOG" src="https://img.shields.io/badge/GOG-DiamantTh-86328A?style=for-the-badge&logo=gog.com" /></a>
</p>

---

Ich mag Software, die man verstehen, verändern, reparieren, weitergeben und selbst betreiben kann – und die Menschen nicht unnötig aus der digitalen Welt ausschließt.
