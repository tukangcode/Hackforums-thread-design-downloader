# Hf Thread Scraper (HTS)

HTS is an image scraper and downloader designed for [hackforums.net](https://hackforums.net). It allows users to download images directly from the site, making it easier to view and analyze thread designs without needing to load threads online.

## Features

- **Image Scraping**: Extracts all images from thread posts on hackforums.net.
- **Bulk Downloading**: Downloads extracted images directly to your computer.
- **User-Friendly Interface**: Provides an intuitive UI with buttons to scrape, clear, and download images.
- **Progress Indicator**: Displays download progress and status messages.
- **Original Filenames**: Saves images using their original filenames from the URLs.

## Installation

1. **Install Tampermonkey Extension**

   - **Firefox**: [Tampermonkey for Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
   - **Chrome**: [Tampermonkey for Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)

2. **Create a New Userscript**

   - Click the Tampermonkey icon in your browser toolbar.
   - Select **Dashboard**.
   - Click the **Add a new script** button (usually a `+` icon).

3. **Paste the HTS Script**

   - Delete any default code in the editor.
   - Paste the HTS userscript code into the editor.

4. **Save the Script**

   - Click **File** > **Save** or press `Ctrl + S` (or `Cmd + S` on Mac).
  
5. Altenatively just instal script by clicking it at **release** 

## Usage

1. **Navigate to hackforums.net**

   - Open any thread or page where you want to scrape images.

2. **Open the Image Scraper UI**

   - Click the **📷 Image Scraper** button located at the top-right corner of the page.

3. **Scrape Images**

   - Click **Scrape Image Links** to extract image URLs from the current page.

4. **Download Images**

   - Review the extracted image links in the textarea.
   - Click **Download All Images** to download the images using their original filenames.

5. **Monitor Progress**

   - A progress bar will display the download progress.
   - Status messages will inform you about each image's download result.

6. **Clear Image Links**

   - Click **Clear Image Links** to reset the list of extracted images.

## Known Issues

- **Large GIF Files**

  - The script may encounter errors when downloading large GIF files due to browser limitations or network issues.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

HTS is intended for personal use to facilitate offline viewing of thread designs on hackforums.net. well hope omni don't angry about this

## Acknowledgments

- **Contributors**

  - Developed collaboratively by **[TukangCode]** and ChatGPT.

- **Inspiration**

  - Created to facilitate offline viewing and inspiration for thread designs on hackforums.net.

