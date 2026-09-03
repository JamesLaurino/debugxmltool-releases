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
Get-FileHash '.\DebugXmlTool-1.0.0.msi' -Algorithm SHA256
```

| Version | Fichier | Octets | SHA-256 |
|---|---|---:|---|
| 1.0.0 | `DebugXmlTool-1.0.0.msi` | 125 198 888 | `948b6d082afc475e4e66b2098733a7646d6cdfa8a81e2ca763b02299ba39c28a` |

## Ce que ce miroir est, et ce qu'il n'est pas

- ✅ Il est une **seconde adresse** pour les mêmes fichiers, aux mêmes empreintes.
- ❌ Il n'est **pas** un service de support : les signalements passent par
  <https://open-studio.tech/fr/aide/signaler-un-probleme>.
- ❌ Il n'est **pas** un engagement contractuel, et il ne modifie ni la licence, ni les conditions
  générales de vente, qui sont sur le site.
- ❌ Il ne contient **aucun code source** et n'en publiera pas.

Windows. Une version Linux est en préparation.

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
Get-FileHash '.\DebugXmlTool-1.0.0.msi' -Algorithm SHA256
```

## What this mirror is, and is not

- ✅ A **second address** for the same files, with the same checksums.
- ❌ **Not** a support channel: use <https://open-studio.tech/en/help/report-a-bug>.
- ❌ **Not** a contractual undertaking; it changes neither the licence nor the terms of sale, which
  live on the site.
- ❌ It contains **no source code** and will not publish any.

Windows. A Linux version is in preparation.
