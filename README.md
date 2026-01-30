# Google Image Batch Downloader for Anki

To install this add-on for Anki, use the code `511921711`. See also: [https://ankiweb.net/shared/info/511921711](https://ankiweb.net/shared/info/511921711)

Batch download pictures from Google Images for your Anki notes.

Credits:

This is a folk of the archived [batch-download-pictures-from-google-images](https://github.com/kelciour/batch-download-pictures-from-google-images) by Kelciour.


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

# Dev notes

How to publish a new version:

- Modify the code
- Log in Anki
- Visit https://ankiweb.net/shared/upload?id=511921711
- Upload the addon `.ankiaddon` file

```bash

# cd to this project directory
zip -r ../google-image-batch-downloader-for-anki.ankiaddon *

```
