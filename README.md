# DiamantTh — Freie Software, Selfhosting & technische Experimente

Deutsch | [English](README.en.md)

Viele meiner Projekte beginnen mit eigenem Bedarf oder einer Frage, die mich nicht loslässt: Warum ist etwas unnötig geschlossen, eingeschränkt oder an einen einzelnen Anbieter gebunden? Ich probiere gern selbst aus, wie eine offenere und besser kontrollierbare Lösung aussehen könnte.

## Woran ich gerade praktisch arbeite

Die folgenden Repositories sind keine Hochglanz-Produktpalette. Sie sind Beispiele dafür, was ich selbst ausprobieren, verstehen und offen weiterentwickeln möchte – vom Prototyp bis zu Projekten, die sich noch bewegen dürfen.

| Projekt | Technik | Lizenz | Warum es existiert |
| --- | --- | --- | --- |
| [ArborPress](https://github.com/DiamantTh/ArborPress) | Python, Quart/ASGI, SQLAlchemy, SvelteKit | AGPL-3.0 | Ein sicherheitsorientiertes Blog-/Mini-CMS-Experiment: WebAuthn/FIDO2-first, getrennte öffentliche und administrative Identitäten, kleiner Core und möglichst wenige externe Laufzeitabhängigkeiten. |
| [HomeClaim](https://github.com/DiamantTh/HomeClaim) | Kotlin/JVM, Gradle, Paper/Folia, SvelteKit | AGPL-3.0 | Ein offenes, modulares Plot- und Regionen-Framework für Minecraft – mit Regionen, Rollen, Policies, Flags und Erweiterungen statt dauerhafter Abhängigkeit von geschlossenen oder kostenpflichtigen Plugins. |
| [LexNova](https://github.com/DiamantTh/LexNova) | PHP, Mezzio, Doctrine DBAL, Svelte 5 | AGPL-3.0-or-later | Ein Experiment für das zentrale Verwalten, Versionieren und Veröffentlichen von Impressums- und Datenschutztexten – mit klarer Kontrolle über Daten und Infrastruktur. |
| [NovariusIRC](https://github.com/DiamantTh/NovariusIRC) | Python 3.12+, Tornado, SQLAlchemy, Alembic, Typer | AGPL-3.0-or-later | Ein modularer, mehrsprachiger IRC-Bot/Daemon zum Selbstbetrieb: moderne, erweiterbare Architektur für mehrere Instanzen und isolierte Container-Deployments, mit RSS, Moderation und Rollen-/Rechtekonzept statt eines historisch gewachsenen Monolithen. |
| [TowerDNS](https://github.com/DiamantTh/TowerDNS) | PHP, Mezzio, Doctrine, Svelte 5, TypeScript | AGPL-3.0-or-later | Selfhostbare DNS-Verwaltung mit gemeinsamem Kern und Provider-Adaptern, statt DNS unnötig an einen einzelnen Anbieter zu ketten. |
| [Visotaris OPMod](https://github.com/DiamantTh/visotaris-opmod) | Kotlin/JVM, Fabric, Gradle, Svelte | AGPL-3.0-or-later | Eine freie Client-Mod für OPSUCHT. Sie ist eine selbst kontrollierbare, quelloffene Alternative zu einer proprietären Mod und Raum für eigene Komfort- und Auswertungsfunktionen. |

Daneben interessieren mich Selfhosting, Linux, IRC, offene Webtechnologien, eigene Server und kleine technische Ideen, die nicht erst einen Business-Plan brauchen, um ausprobiert werden zu dürfen. KI-gestützte Entwicklung und „Vibecoding“ nutze ich dabei als Werkzeug: um Ideen schneller anzutesten, neue Stacks zu verstehen und Dinge umzusetzen, die sonst vielleicht bloß Notizen geblieben wären. Das ersetzt weder Nachdenken noch Prüfen – es macht den Weg zum ersten funktionierenden Versuch oft kürzer.

## Freiheit ist mehr als ein öffentliches Repository

Ich bin **Copyleft-first, nicht OSI-first**. Dass Quellcode irgendwo öffentlich liegt, ist für mich nur der Anfang. Entscheidend ist, ob Freiheit langfristig bei Nutzer:innen und Gemeinschaft bleibt: Nachnutzbarkeit, Transparenz, Auditierbarkeit, Kontrolle über die eigene Technik – und ein echter Rückfluss von Verbesserungen.

MIT- oder BSD-Lizenzen sind aus meiner Sicht gerade deshalb schwächer: Sie lassen die Übernahme und proprietäre Weiterentwicklung freier Arbeit weitgehend zu, ohne einen vergleichbaren Rückfluss zu verlangen. LGPL kann je nach Anwendungsfall ebenfalls zu weich sein. GPL und besonders AGPL entsprechen meiner Vorstellung stärker.

Die AGPL ist für mich eine sehr gute und praktisch nutzbare Copyleft-Lizenz. Viele meiner aktuellen Projekte verwenden deshalb AGPL oder AGPL-3.0-or-later. Sie macht es bei Web-, Server- und Netzwerksoftware schwieriger, Offenlegungspflichten allein dadurch zu umgehen, dass ein Programm als Dienst angeboten wird. Trotzdem halte ich AGPL nicht zwingend für das maximal sinnvolle Copyleft: Fragen bleiben etwa bei interner Nutzung, SaaS- und Netzwerkbetrieb, API- oder Proxy-Schichten, künstlich aufgeteilten, funktional zusammengehörigen Komponenten und proprietären Umgehungskonstruktionen.

Ein Beispiel dafür, wie ich stärkeres Copyleft weiterdenke, ist die [Novara Software Freedom License (NSFL)](https://gist.github.com/DiamantTh/ef7ef2da5c60278574e2402a1c41b7db). „Novara“ stammt aus meinen Überlegungen zu einem eigenen Staat oder einem alternativen politischen und gesellschaftlichen Ordnungsmodell, in dem Regeln und Strukturen bewusst anders und nachvollziehbar begründet gestaltet werden. Die NSFL überträgt einen Teil dieser Gedanken – Transparenz, nachvollziehbare Regeln, Begrenzung von Macht und Abhängigkeiten, Rückfluss und stärkere Nutzerrechte – auf Software und ihre Nutzung.

Kurz: **Copyleft, Rückfluss und Gemeingut vor maximaler kommerzieller Wiederverwendungsfreiheit.**

## Authentifizierung: Passkeys sind kein Luxus

Wo es sinnvoll möglich ist, bevorzuge ich **WebAuthn, FIDO2, Passkeys und Hardware-Sicherheitsschlüssel**. Passwort plus sechsstelliger TOTP-Code ist für mich ein Fallback oder eine Übergangslösung, nicht das Zielbild.

Bei Admin-Oberflächen, Hosting-Panels, Cloud- und Entwicklerdiensten, DNS, Domains und anderer Infrastruktur mit weitreichenden Berechtigungen sollten phishing-resistente Verfahren zum normalen Fundament gehören. Wenn eine technisch anspruchsvolle Plattform im Jahr 2026 ausschließlich Passwort und TOTP anbietet, frage ich mich schon gelegentlich, ob man das Auth-System nicht einmal komplett neu bauen lassen sollte. Das ist technische Frustration, keine persönliche Abrechnung: Die Standards existieren seit Jahren, und die Schutzwirkung ist kein dekoratives Extra.

## Offen, langlebig und zugänglich

Mich beschäftigen digitale Nutzerrechte, offene Standards, Interoperabilität und digitale Selbstbestimmung. Dazu gehören für mich auch Reparierbarkeit, langfristige Nutzbarkeit von Hard- und Software, Kritik an unnötigem DRM und Vendor-Lock-in sowie der Erhalt von Spielen und Software nach Abschaltungen. Offene oder community-getragene Serverstrukturen und Drittanbieter-Server sind dabei keine Randthemen, sondern oft Voraussetzung dafür, dass Technik nicht einfach verschwindet.

Das berührt auch Fragen der gesellschaftlichen Teilhabe. Inklusion, Barrierefreiheit, inklusive Bildung, Teilhabe am Arbeitsleben, faire Arbeitnehmerrechte, Selbstbestimmung und die Rechte von Menschen mit Behinderungen – einschließlich der **UN-Behindertenrechtskonvention (UN-BRK)** – sind Themen, mit denen ich mich beschäftige. Freie Software, offene Schnittstellen und zugängliche Gestaltung lösen nicht alles. Sie können aber unnötige Zugangshürden und Abhängigkeiten verringern und damit digitale Teilhabe realistischer machen.

## Gaming gehört dazu

Gaming ist für mich nicht nur Spielen. Ich mag Mods, Community-Projekte, eigene Server, technische Anpassungen und die Frage, wie Spiele auch außerhalb eines einzelnen Plattformbetreibers weiterleben können. Minecraft und Pokémon gehören dazu, ebenso Linux-Gaming, Modding und die Bewahrung älterer Spiele.

## Links

- 💻 [GitHub](https://github.com/DiamantTh) · [Git / diath.systems](https://git.diath.systems) · [Keybase](https://keybase.io/diamantthomy)
- 🗨️ [X](https://x.com/DiamantThomy) · [Reddit](https://www.reddit.com/user/diamantth/) · [Facebook](https://www.facebook.com/DiamantThomy)
- ▶️ [YouTube](https://www.youtube.com/@DiamantTh) · 🎮 [Twitch](https://www.twitch.tv/diamantth) · 🎵 [Suno](https://suno.com/profile/@diamantth)
- 🕹️ [Steam](https://steamcommunity.com/id/DiamantThomy) · [GOG](https://www.gog.com/u/DiamantTh)

---

Ich mag Software, die man verstehen, verändern, reparieren, weitergeben und selbst betreiben kann – und die Menschen nicht unnötig aus der digitalen Welt ausschließt.
