# DiamantTh — Free Software, Self-Hosting & Technical Experiments

[Deutsch](README.md) | English

Many of my projects start with a need of my own or a question I can't quite let go: Why is something unnecessarily closed, restricted, or tied to a single provider? I like trying out what a more open solution, with more control, could look like.

## What I'm working on

The repositories below are not a polished product lineup. They are examples of things I want to try, understand, and develop openly—from prototypes to projects that are still evolving.

| Project | Technology | License | Why it exists |
| --- | --- | --- | --- |
| [ArborPress](https://github.com/DiamantTh/ArborPress) | Python, Quart/ASGI, SQLAlchemy, SvelteKit | AGPL-3.0 | A security-focused blogging and mini-CMS experiment: WebAuthn/FIDO2 first, separate public and administrative identities, a small core, and as few external runtime dependencies as possible. |
| [HomeClaim](https://github.com/DiamantTh/HomeClaim) | Kotlin/JVM, Gradle, Paper/Folia, SvelteKit | AGPL-3.0 | An open, modular plot and region framework for Minecraft, with regions, roles, policies, flags, and extensions instead of a lasting dependency on closed or paid plugins. |
| [LexNova](https://github.com/DiamantTh/LexNova) | PHP, Mezzio, Doctrine DBAL, Svelte 5 | AGPL-3.0-or-later | An experiment in centrally managing, versioning, and publishing legal notice and privacy texts, with clear control over data and infrastructure. |
| [NovariusIRC](https://github.com/DiamantTh/NovariusIRC) | Python 3.12+, Tornado, SQLAlchemy, Alembic, Typer | AGPL-3.0-or-later | A modular, multilingual IRC bot/daemon for self-hosting: a modern, extensible architecture for multiple instances and isolated container deployments, with RSS, moderation, and role-based permissions instead of a historically grown monolith. |
| [TowerDNS](https://github.com/DiamantTh/TowerDNS) | PHP, Mezzio, Doctrine, Svelte 5, TypeScript | AGPL-3.0-or-later | A self-hostable DNS manager with a shared core and provider adapters, so DNS management doesn't have to be tied unnecessarily to a single provider. |
| [Visotaris OPMod](https://github.com/DiamantTh/visotaris-opmod) | Kotlin/JVM, Fabric, Gradle, Svelte | AGPL-3.0-or-later | A free client mod for OPSUCHT. It offers a self-controlled, open-source alternative to a proprietary mod and room for my own convenience and analysis features. |

I'm also interested in self-hosting, Linux, IRC, open web technologies, running my own servers, and small technical ideas that don't need a business plan before they can be tried. I use AI-assisted development and “vibecoding” as tools: to test ideas sooner, learn new stacks, and build things that might otherwise have stayed as notes. They don't replace thinking or review; they often make it quicker to get to a first working attempt.

## Freedom means more than a public repository

I'm **copyleft-first, not OSI-first**. Having source code publicly available is only the beginning. What matters to me is whether freedom stays with users and the community over time: the ability to reuse, transparency, auditability, control over one's own technology, and a real return of improvements.

From my perspective, MIT and BSD licenses are weaker precisely because they largely allow others to take free work and develop it into proprietary software without requiring a comparable contribution back. Depending on the use case, LGPL can also be too soft. GPL, and especially AGPL, are closer to what I have in mind.

AGPL is a very good and practical copyleft license to me. That's why many of my current projects use AGPL or AGPL-3.0-or-later. For web, server, and network software, it makes it harder to sidestep disclosure obligations simply by offering a program as a service. Still, I don't necessarily consider AGPL the strongest useful form of copyleft. Questions remain around internal use, SaaS and network operation, API or proxy layers, artificially split but functionally connected components, and proprietary workarounds.

The [Novara Software Freedom License (NSFL)](https://gist.github.com/DiamantTh/ef7ef2da5c60278574e2402a1c41b7db) is one example of how I think about taking copyleft further. “Novara” comes from my ideas for a state of my own, or an alternative political and social order, where rules and structures would be deliberately designed differently and their reasoning made clear. The NSFL carries some of those ideas—transparency, rules people can understand, limits on power and dependency, contribution back, and stronger user rights—over to software and how it is used.

In short: **copyleft, contribution back, and the commons before maximum commercial reuse freedom.**

## Authentication: passkeys are not a luxury

Wherever it makes sense, I prefer **WebAuthn, FIDO2, passkeys, and hardware security keys**. A password plus a six-digit TOTP code is a fallback or a transition measure to me, not the end goal.

Phishing-resistant methods should be a standard foundation for admin panels, hosting control panels, cloud and developer services, DNS, domains, and other infrastructure accounts with broad permissions. When a technically sophisticated platform still offers only passwords and TOTP in 2026, I sometimes wonder whether its authentication system should just be rebuilt from scratch. That's technical frustration, not a personal attack: these standards have been around for years, and their protection isn't a decorative extra.

## Open, durable, and accessible

I'm interested in digital user rights, open standards, interoperability, and digital self-determination. For me, that also includes repairability, the long-term usability of hardware and software, concerns about unnecessary DRM and vendor lock-in, and preserving games and software after services shut down. Open or community-run server structures and third-party servers aren't side issues; they're often what lets technology continue to exist.

These interests also connect to social participation. Inclusion, accessibility, inclusive education, participation in working life, fair workers' rights, self-determination, and the rights of people with disabilities—including the **UN Convention on the Rights of Persons with Disabilities (UN CRPD)**—are among the topics I follow. Free software, open interfaces, and accessible design don't solve everything. They can, however, reduce unnecessary barriers and dependencies, making digital participation more achievable.

## Gaming is part of it

Gaming means more to me than just playing. I like mods, community projects, running my own servers, technical tweaks, and the question of how games can live on beyond a single platform operator. Minecraft and Pokémon are part of that, as are Linux gaming, modding, and preserving older games.

## Links

- 💻 [GitHub](https://github.com/DiamantTh) · [Git / diath.systems](https://git.diath.systems) · [Keybase](https://keybase.io/diamantthomy)
- 🗨️ [X](https://x.com/DiamantThomy) · [Reddit](https://www.reddit.com/user/diamantth/) · [Facebook](https://www.facebook.com/DiamantThomy)
- ▶️ [YouTube](https://www.youtube.com/@DiamantTh) · 🎮 [Twitch](https://www.twitch.tv/diamantth) · 🎵 [Suno](https://suno.com/profile/@diamantth)
- 🕹️ [Steam](https://steamcommunity.com/id/DiamantThomy) · [GOG](https://www.gog.com/u/DiamantTh)

---

I like software you can understand, change, repair, share, and run yourself—and that doesn't needlessly exclude people from the digital world.
