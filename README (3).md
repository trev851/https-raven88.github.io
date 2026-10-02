# Ravenbooks

A Kodi addon that turns written stories into audiobooks. Pick a story from the library, tap it, and it reads aloud using online text-to-speech.

- **Addon ID:** `plugin.audio.ravenbooks`
- **Version:** 0.1.0
- **Tested on:** Kodi 21 (Omega)
- **Repo:** https://github.com/trev851/https-raven88.github.io

## Download

Addon zip: **[ADD YOUR ZIP LINK HERE]**

(Example format: `https://github.com/trev851/https-raven88.github.io/raw/main/plugin.audio.ravenbooks-0.1.0.zip`)

## Install in Kodi

1. Open Kodi and go to **Settings > System > Add-ons**.
2. Turn on **Unknown sources** and accept the warning.
3. Go back to **Add-ons > Install from zip file**.
4. Browse to the downloaded `plugin.audio.ravenbooks` zip and select it.
5. Wait for the "Add-on installed" notification.
6. Open it from **Add-ons > Music add-ons > Ravenbooks**.

## How it works

1. The addon shows a library of stories.
2. Tap a story and the text is split into chunks.
3. Each chunk is sent to an online TTS service and saved as audio.
4. The audio chunks play in order as a playlist.

An internet connection is needed the first time a story is played.

## Updating

Download the newer zip and install it the same way. Kodi replaces the old version.

## Troubleshooting

- **Nothing plays:** check your internet connection and try the story again.
- **Install fails:** make sure Unknown sources is turned on and the file is the full `.zip`.
- **Still stuck:** open Kodi's log and look for lines mentioning `ravenbooks`.
