# BitTorrent Trackers Minimal Rules

This repository lists the **minimal ratio and seedtime (days) requirements** for various BitTorrent trackers.

It focuses on **baseline user ranks** (i.e. new or standard users), without taking into account VIP, Power User or custom classes.

---

## Format

Each tracker entry follows this simple structure:

`Name : tracker1
ratio : 1
seedtime : 1

Name : tracker2
ratio : 1
seedtime : 4

Name : tracker3
ratio : 1
seedtime : 7`

---

## Naming convention

Tracker names are **normalized** using the identifiers from the [Servarr Wiki – Supported Indexers](https://github.com/Servarr/Wiki/blob/daa08894ad4ddc67317ee9b0901418370f7a8198/prowlarr/supported-indexers.md).

For example:
- `HD-Only (API){#hdonly-api}` → becomes `hdonly`
- `SceneTime (Scraping){#scenetime-scraping}` → becomes `scenetime`

Remove suffixes like `-api` or `-scraping`.

---

## Contributions

Pull Requests are **open and welcome** to improve or expand this repository.  
Please keep entries simple and standardized — one tracker per block, with lowercase normalized names.

---

## Disclaimer

This repository is **for informational purposes only.**  
Tracker rules may evolve — always check each tracker’s own documentation or forum for the latest requirements.
