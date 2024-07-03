# Description for "NFC Audio Player Project (kmx-nfc-notYourMaster)"

This project enables automatic audio playback through NFC-triggered web pages. By scanning an NFC tag, users are redirected via an intermediate HTML page to the main page where the audio file `kmx_not_your_master.mp3` is played. This approach successfully circumvents browser restrictions on autoplay triggered by NFC. The project demonstrates effective use of NFC technology in web development, providing a seamless and interactive user experience.

**Created by Shaw-core( Thanks to all Shadow_Ship_Studio members ).**

## Features

- **Automatic audio playback**: Plays `kmx_not_your_master.mp3` when NFC tag is scanned.
- **Intermediate redirection**: Uses an intermediate page to bypass browser autoplay restrictions.
- **Seamless user experience**: Ensures smooth and interactive experience using NFC technology.

## How It Works

1. **NFC Tag Scan**: When the NFC tag is scanned, it opens an intermediate HTML page.
2. **Redirection**: The intermediate page redirects to the main page after a short delay.
3. **Audio Playback**: The main page attempts to autoplay the audio file. If autoplay fails, a button is provided for manual playback.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/shaw-core/kmx-nfc-notYourMaster.git
2. Intermediate URL(Write this URL into the NFC tag):
   ```sh
   https://shaw-core.github.io/kmx-nfc-notYourMaster/intermediate.html

