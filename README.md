# Debug XML Tool — miroir de téléchargement

**Ce dépôt ne contient pas de code source.** Il ne sert qu'à une chose : garder les installeurs de
Debug XML Tool téléchargeables depuis un hébergeur tiers, indépendamment du serveur du site.

- Site officiel, documentation et achat : **<https://open-studio.tech>**
- Téléchargement officiel : **<https://open-studio.tech/fr/telecharger>**
- Les installeurs sont dans l'onglet **[Releases](../../releases)**.

## Vérifier ce que vous avez téléchargé

Chaque version publie son empreinte SHA-256, **identique à celle affichée sur le site**. Un fichier
dont l'empreinte diffère n'est pas celui qui a été publié — quelle que soit sa provenance.

```powershell
Get-FileHash '.\DebugXmlTool-1.0.1.msi' -Algorithm SHA256
```

```sh
sha256sum ./debugxmltool_1.0.1-1_amd64.deb
```

| Version | Fichier | Octets | SHA-256 |
|---|---|---:|---|
| 1.0.1 | `DebugXmlTool-1.0.1.msi` | 126 117 420 | `94071d667cd47fbca4ac38dc385bb4abad7211b84ad8ecfe2e421a3bc1fe9694` |
| 1.0.1 | `debugxmltool_1.0.1-1_amd64.deb` | 119 572 166 | `82b84549e8b9c6e31cd220ac6aa9d6a4999e3af4c01f6800b460310146d82d19` |
| 1.0.0 | `DebugXmlTool-1.0.0.msi` | 125 202 988 | `66909ed258dcc87c81ad2039195bbf00422049f052c0d04e5569266ae524d0c7` |

⚠️ **La version servie sur le site est la 1.0.1.** La 1.0.0 reste téléchargeable ici parce qu'un
fichier publié une fois ne se retire pas sans raison — mais c'est la 1.0.1 qu'il faut installer, et
elle **remplace** la 1.0.0 au lieu de s'installer à côté.

## Ce que ce miroir est, et ce qu'il n'est pas

- ✅ Il est une **seconde adresse** pour les mêmes fichiers, aux mêmes empreintes.
- ❌ Il n'est **pas** un service de support : les signalements passent par
  <https://open-studio.tech/fr/aide/signaler-un-probleme>.
- ❌ Il n'est **pas** un engagement contractuel, et il ne modifie ni la licence, ni les conditions
  générales de vente, qui sont sur le site.
- ❌ Il ne contient **aucun code source** et n'en publiera pas.

Windows et Linux, tous les deux publiés depuis la 1.0.1. Le paquet Linux est un `.deb`
Debian/Ubuntu 64 bits — `sudo apt install ./debugxmltool_1.0.1-1_amd64.deb` — et il s'installe
dans `/opt/debugxmltool`. macOS n'est pas prévu.

---

# Debug XML Tool — download mirror

**This repository contains no source code.** Its only purpose is to keep Debug XML Tool installers
downloadable from a third-party host, independently of the website's own server.

- Official site, documentation and purchase: **<https://open-studio.tech/en>**
- Official download: **<https://open-studio.tech/en/download>**
- Installers are under **[Releases](../../releases)**.

## Verify what you downloaded

Every release publishes its SHA-256 checksum, **identical to the one shown on the site**. A file
whose checksum differs is not the published file, wherever it came from.

```powershell
Get-FileHash '.\DebugXmlTool-1.0.1.msi' -Algorithm SHA256
```

```sh
sha256sum ./debugxmltool_1.0.1-1_amd64.deb
```

| Version | File | Bytes | SHA-256 |
|---|---|---:|---|
| 1.0.1 | `DebugXmlTool-1.0.1.msi` | 126 117 420 | `94071d667cd47fbca4ac38dc385bb4abad7211b84ad8ecfe2e421a3bc1fe9694` |
| 1.0.1 | `debugxmltool_1.0.1-1_amd64.deb` | 119 572 166 | `82b84549e8b9c6e31cd220ac6aa9d6a4999e3af4c01f6800b460310146d82d19` |
| 1.0.0 | `DebugXmlTool-1.0.0.msi` | 125 202 988 | `66909ed258dcc87c81ad2039195bbf00422049f052c0d04e5569266ae524d0c7` |

⚠️ **The version served on the site is 1.0.1.** 1.0.0 stays downloadable here because a file
published once is not withdrawn without a reason — but 1.0.1 is the one to install, and it
**replaces** 1.0.0 rather than installing alongside it.

## What this mirror is, and is not

- ✅ A **second address** for the same files, with the same checksums.
- ❌ **Not** a support channel: use <https://open-studio.tech/en/help/report-a-bug>.
- ❌ **Not** a contractual undertaking; it changes neither the licence nor the terms of sale, which
  live on the site.
- ❌ It contains **no source code** and will not publish any.

Windows and Linux, both published as of 1.0.1. The Linux package is a Debian/Ubuntu 64-bit
`.deb` — `sudo apt install ./debugxmltool_1.0.1-1_amd64.deb` — installing into
`/opt/debugxmltool`. macOS is not planned.
