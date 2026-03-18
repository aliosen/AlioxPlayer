# Privacy Policy - Aliox Player

**Last Updated: March 17, 2026**

**Aliox Player** ("we", "our") is committed to protecting your privacy. This Privacy Policy explains how we handle information when you use our application, particularly regarding its integration with Google Drive.

## 1. Information We Access and Collect

To function as a cloud music player, the application requests access to your Google Drive via the `drive.readonly` scope. 

*   **File Metadata**: We access file names, IDs, sizes, and media types (audio) to index your music library.
*   **Audio Content**: The application reads audio files for playback and extraction of music metadata (ID3 tags such as Artist, Album, and Cover Art).
*   **Local Storage**: The indexed information (song names, artists, and album art) is stored **locally** on your device using technologies like IndexedDB (in the browser/app) to enable rapid access to your library.

## 2. How We Use Information

The collected information is used exclusively to:
*   Display your music library within the app.
*   Allow the playback of your audio files via direct streaming from your Google Drive.
*   Organize your music by artist and album.

## 3. Data Sharing

**We do not share, sell, or transfer your data to third parties.** 
All metadata remains on your device, and access credentials (tokens) are managed securely and sent only to official Google servers for authentication.

## 4. Data Retention and Deletion

*   The application does not have its own server; therefore, your data is not stored on our servers.
*   You can remove all data collected by the application at any time:
    1.  By **Logging out** in the application settings.
    2.  By clearing the application's cache/data on your device.
    3.  By revoking "Aliox Player" access through your Google Account security settings.

## 5. Google Limited Use Requirements

Aliox Player's use of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the **Limited Use** requirements.

## 6. Contact

If you have any questions about this policy, please feel free to open an issue on the project's official GitHub repository.
