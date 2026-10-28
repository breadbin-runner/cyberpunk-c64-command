![Cyberpunk C64 Command](banner.png)

# Cyberpunk C64 Command

A desktop companion for **C64 Ultimate and Ultimate 64** on Windows and macOS. Manage disk images and files, explore SID music, control your C64, and adjust compatible lighting.

## Downloads

| Platform | Version | Download |
| --- | --- | --- |
| Windows 10 / 11 · 64-bit | **3.12.2** | [Download Windows installer](https://github.com/breadbin-runner/cyberpunk-c64-command/releases/download/v3.12.2/Cyberpunk-C64-Command-3.12.2-Windows-x64-Setup.exe) |
| Mac · Apple silicon | 3.12.1 | [Download](https://github.com/breadbin-runner/cyberpunk-c64-command/releases/download/v3.12.2/Cyberpunk-C64-Command-3.12.1-macOS-Apple-Silicon.zip) |
| Mac · Intel | 3.12.0 | [Download](https://github.com/breadbin-runner/cyberpunk-c64-command/releases/download/v3.12.2/Cyberpunk-C64-Command-3.12.0-macOS-Intel.zip) |

[Release notes](https://github.com/breadbin-runner/cyberpunk-c64-command/releases/tag/v3.12.2) · [German manual](docs/Anleitung-DE.pdf) · [English manual](docs/Manual-EN.pdf)

The new features in version 3.12.2 are part of the **Windows release**. The Mac downloads remain at versions 3.12.1 for Apple silicon and 3.12.0 for Intel.

## What’s new in Windows version 3.12.2

- **Multiple selection in the File Manager:** Select files and folders using checkboxes, Shift, or Ctrl+A.
- **Batch actions:** Download selected files together, add supported disk images to Disk Flip, or delete selected files and empty folders after confirmation.
- **Search across the Ultimate:** Find files and folders in all locations accessible via FTP, including SD and USB storage. Results show their full paths, and clicking a result opens its folder.
- **Search controls:** See indexing progress, refresh the index, or stop a scan.
- **Date sorting:** Sort files by modification date, with the newest files first.
- **Improved Windows installer:** File verification, backup, and recovery help protect the installation if an error occurs.
- **Update check:** The Help menu can check for future stable releases and offer the appropriate installer download.

## What you can do

- **Disk Workbench:** Open D64, D71, and D81 images, inspect their contents, and edit supported D64 working copies. Use Disk Flip to prepare multiple images for disk changes.
- **File Manager:** Browse, upload, download, and manage files on your Ultimate.
- **C64 control:** Control the machine and its drives, including reset, pause, resume, and mounting disk images.
- **Media Launcher:** Start supported programs, music, cartridges, and disk images.
- **Light Studio:** Adjust compatible case and keyboard lighting.
- **SID Collection:** Browse a separately obtained High Voltage SID Collection, add your own SID files, and play music on the Ultimate.
- **Transfer Center:** Follow uploads and downloads, cancel transfers, and retry failed jobs.
- **PCM/REU Audio Studio:** Turn WAV files into 8-bit samples, preview them, save projects, and play them on the C64 with the graphical player.

The interface is available in **English and German**. You can customize its appearance in the Design Editor and hide modules you do not use.

## Getting started

1. Download the package for your computer from the table above.
2. On Windows, run the installer. On Mac, extract the ZIP file and move the app to your Applications folder.
3. If you want to use an Ultimate, enter its IP address or hostname in the app settings and connect.
4. For the File Manager, also configure the Ultimate’s FTP access.

Local disk image work does not require an Ultimate connection. Hardware features require your computer and Ultimate to be reachable on the same network. The Ultimate’s REST service must be enabled; the File Manager also requires FTP.

All required runtime components are included. No separate FTP bridge or developer tools are needed.

## Playing your own audio on the C64

In the PCM/REU Audio Studio, load a WAV file, choose a section and sample rate, preview the 8-bit result, and save your work as a `.pcmstudio` project. “Transfer & Play” loads the sample into REU memory and starts the graphical C64 player.

This feature requires **16 MB of REU memory**, **Ultimate Audio with audible sampler output**, and the **Ultimate DMA Service**.

## Help and feedback

The app includes German and English PDF manuals. Questions, suggestions, and bug reports are welcome in [GitHub Issues](https://github.com/breadbin-runner/cyberpunk-c64-command/issues). Please include your operating system, app version, and a description of what happened.

[Support / Hilfe](SUPPORT.md) · [Network and installation counter](docs/NETWORK.md)

## About

Cyberpunk C64 Command is an independent fan project by **Breadbin Runner**. This repository contains downloads, manuals, and project information. Application source code is not published here.

The project is not affiliated with Commodore, the Ultimate projects, or the High Voltage SID Collection. Third-party notices are included with the app.

<details>
<summary>Screenshots / Bildschirmfotos</summary>

Main menu in English and German, captured without an active Ultimate connection.

![English main menu](docs/first%20pic_CYPC64COM_EN.png)
![German main menu](docs/first%20pic_CYPC64COM_DE.png)

</details>
