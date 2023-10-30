# StreamDeckAudioDownloader
Convert your Stream Deck audio files to a downloadable format.
Before you use this, you need to have the Stream Deck software installed, and have some Stream Deck Audio already downloaded/installed.

You can download the Stream Deck software [here](https://www.elgato.com/en/gaming/downloads).

You can download Stream Deck Audio [here](https://marketplace.elgato.com/audio/sounds) and [here](https://marketplace.elgato.com/audio/music).

## How to use
Head on over to https://hbidamian.github.io/StreamDeckAudioDownloader/ and follow the instructions on the pages.

## Features

| File | Description |
| --- | --- |
| `catalogscraper.html` | This page allows the user to get the `mp3` preview file from the `catalog.json` file, and allows the users to download it. |
| `sda2wav.html` | This page converts `.streamDeckAudio` files to `.wav`, and allows the user to download it. |

## How to run locally
1. Clone the repository
2. Open the `index.html` file in your browser of choice
3. Voila!

## Credits
- [RaineAllDay/SDA2Wav](https://github.com/RaineAllDay/SDA2Wav) - [License](https://github.com/RaineAllDay/SDA2Wav/blob/master/LICENSE.md): I converted the code verbaitim to JavaScript, and added a few things to make it work how I wanted it to. This is used in the `sda2wav.html` file.
