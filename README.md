# Hifz — Web App

A web-first 16-line Indo-Pak Mushaf memorization app. Android/Gradle build files have been removed.

## Run locally

Serve this directory with any static HTTP server (for example `python -m http.server 8000`) and open `http://localhost:8000`. Using a server is recommended because the app loads local JSON files.

## Deploy

Upload the contents of this folder to your GitHub repository and enable GitHub Pages for the appropriate branch/folder.

## Tafsir

The Tools menu includes an initial Ayah-by-Ayah Tafsir lookup for selected Urdu and English editions. It requests public JSON records from the spa5k/tafsir_api repository at runtime. It does not bundle the complete Tafsir corpora locally; internet access is required. Edition identifiers and returned JSON formats may change, so verify each edition before relying on it. Missing records are reported rather than replaced with invented commentary.

## Data and attribution

Existing Quran/Mushaf, font, meanings, mutashabihat, rub and ruku data are retained from the supplied project. Review each source's license and attribution requirements before public distribution. The Darussalam screenshot is a visual reference; the current page text/layout data has not been converted into a verified facsimile of that specific printed edition.
