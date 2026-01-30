# Google Image Batch Downloader for Anki

This is a folk of the archived [batch-download-pictures-from-google-images](https://github.com/kelciour/batch-download-pictures-from-google-images) by Kelciour.

Batch download pictures from Google Images for your Anki notes.

## Features
- Multiple search queries per note (Word, Definition, Giphy, etc.).
- Custom target fields and image counts.
- Image resizing (Width/Height constraints).
- **NEW**: Language and Region filters for highly accurate results.

## Configuration Guide for Better Results

To improve the accuracy of your search results, especially for language learning, you should configure the **Region** and **Language** fields in the setup dialog.

| Filter | Description | Example (German) |
| :--- | :--- | :--- |
| **Region** | Two-letter country code (`gl` parameter) | `de` for Germany |
| **Language** | Language restriction code (`lr` parameter) | `lang_de` for Deutsch |

### Example Setup
If you are learning German and want to search for the word "Tee":

1. Open the Browser and select your notes.
2. Go to **Edit > Google Image Batch Downloader for Anki**.
3. Set **Region** to `de`.
4. Set **Language** to `lang_de`.
5. Click **Start**.

This ensures Google prioritizes results that are relevant to the German language and region, avoiding English-centric results.
