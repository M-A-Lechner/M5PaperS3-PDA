# PaperS3 PDA

This project aims to add apps and functionality to the M5 Paper S3 for it to work as a low-power, modern PDA-like device.

Following functionalities are planned:
- [ ] Notebook App: Accepts drawn and typed input.
- [ ] Calendar App: For logging and tracking daily events.
- [ ] Project Management App: Will work as a type of journal, in which you can log projects, etc. and record updates, deadlines and so on. All changes will be logged in a project history. This app will integrate with the calendar (Integration with Notebook is in consideration). 
- [ ] News App: set APIs to receive news, and read them on the device, like an e-book reader.
- [ ] Syncing Tool: This function aims to sync calendar and notebook data to a specified server/service. Currently a seperate app/simple ftp folder is planned. However NextCloud integration will be considered. This tool will not be automatic, and will only sync when the user explicitly starts it.
- [ ] Calculator App: Simple calculator, like any phone app.
- [ ] Lexicon App: Words lookup based on installed dictionaries on the SD-card.
- [ ] Wallpaper App: Pick and choose any wallpaper to be displayed from the SD-card.
- [ ] Comprehensive Settings: Set things like startup sound, sleep timer, WiFi-setup, etc.
- [ ] Further Features: Other apps/tools are being planned, and will be added to this list.

User demo source code of [PaperS3](https://docs.m5stack.com/en/core/PaperS3).

## Build

### Fetch Dependencies

```bash
python ./fetch_repos.py
```

### Tool Chains

[ESP-IDF v5.3.3](https://docs.espressif.com/projects/esp-idf/en/v5.3.3/esp32s3/index.html)

### Build

```bash
idf.py build
```

### Flash

```bash
idf.py flash
```

## Acknowledgments

This project is a fork of the following repository:

- https://github.com/m5stack/M5PaperS3-UserDemo

This project references the following open-source libraries and resources:

- https://github.com/m5stack/M5GFX.git
- https://github.com/m5stack/M5Unified.git
- https://github.com/Forairaaaaa/mooncake
- https://github.com/Forairaaaaa/mooncake_log

