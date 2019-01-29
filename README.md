# google_drive_sample
Sample Electron application to show what happened on Google Drive

# Run
```
npm install
npm run
```

Since 28 Jan 2019, files list on Google Drive doesn't render on Electron app.
Devtools says `net:ERR_NOT_IMPLEMENTED` happens on Google Drive.
Google Drive requires `chrome-extension://ghbmnnjooekpmoecnnnilnnbdlolhkhi/page_embed_script.js` to show files list but
Electron doesn't support this extension.

# Screen shot
![screen shot](https://github.com/KazuyaHayashi/google_drive_sample/blob/master/images/screen_shot.png)
