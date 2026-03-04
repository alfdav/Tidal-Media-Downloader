<br>
    <a href="https://github.com/yaronzz/Tidal-Media-Downloader-PRO">[GUI-REPOSITORY (upstream PRO version)]</a>
<br>

![Tidal-Media-Downloader](https://socialify.git.ci/alfdav/Tidal-Media-Downloader/image?description=1&font=Rokkitt&forks=1&issues=1&language=1&name=1&owner=1&pattern=Circuit%20Board&stargazers=1&theme=Dark)


<div align="center">
  <h1>Tidal-Media-Downloader</h1>
  <a href="https://github.com/alfdav/Tidal-Media-Downloader/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/alfdav/Tidal-Media-Downloader.svg?style=flat-square" alt="">
  </a>
  <a href="https://github.com/alfdav/Tidal-Media-Downloader/releases">
    <img src="https://img.shields.io/github/v/release/alfdav/Tidal-Media-Downloader.svg?style=flat-square" alt="">
  </a>
  <a href="https://www.python.org/">
    <img src="https://img.shields.io/github/issues/alfdav/Tidal-Media-Downloader.svg?style=flat-square" alt="">
  </a>
  <a href="https://github.com/alfdav/Tidal-Media-Downloader">
    <img src="https://img.shields.io/github/downloads/alfdav/Tidal-Media-Downloader/total?label=tidal-gui%20download" alt="">
  </a>
  <a href="https://pypi.org/project/tidal-dl/">
    <img src="https://img.shields.io/pypi/dm/tidal-dl?label=tidal-dl%20download" alt="">
  </a>
  <a href="https://github.com/alfdav/Tidal-Media-Downloader/actions/workflows/build.yml">
    <img src="https://github.com/alfdav/Tidal-Media-Downloader/actions/workflows/build.yml/badge.svg" alt="">
  </a>
</div>
<p align="center">
  «Tidal-Media-Downloader» is an application that lets you download videos and tracks from Tidal. It supports two version: tidal-dl and tidal-gui. (This repository only contains tidal-dl, and the release isn't the newest gui version.)
    <br>
        <a href="https://github.com/yaronzz/Tidal-Media-Downloader-PRO/releases">Download</a> |
        <a href="https://doc.yaronzz.com/post/tidal_dl_installation/">Documentation</a> |
        <a href="https://doc.yaronzz.com/post/tidal_dl_installation_chn/">中文文档</a> |
    <br>
</p>

> **Note:** This is a fork of <a href="https://github.com/yaronzz/Tidal-Media-Downloader">yaronzz/Tidal-Media-Downloader</a>.

## 📺 Installation 

```shell
pip3 install tidal-dl --upgrade
```

| USE                                                   | FUNCTION                   |
| ----------------------------------------------------- | -------------------------- |
| tidal-dl                                              | Show interactive interface |
| tidal-dl -h                                           | Show help-message          |
| tidal-dl -l "https://tidal.com/browse/track/70973230" | Download link              |
| tidal-dl -g                                           | Show simple-gui            |

If you are using windows system, you can use [tidal-pro](https://github.com/yaronzz/Tidal-Media-Downloader-PRO)

### Nightly Builds

|Download nightly builds from continuous integration: 	| [![Build Status][Build]][Actions] 
|-------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|

[Actions]: https://github.com/alfdav/Tidal-Media-Downloader/actions
[Build]: https://github.com/alfdav/Tidal-Media-Downloader/workflows/Tidal%20Media%20Downloader/badge.svg

## 🤖 Features
- Download album \ track \ video \ playlist \ artist-albums

- Add metadata to songs

- Selectable video resolution and track quality

## 💽 User Interface

## Settings - Possible Tags

### Album

| Tag               | Example value                        |
| ----------------- | ------------------------------------ |
| {ArtistName}      | The Beatles                          |
| {AlbumArtistName} | The Beatles                          |
| {Flag}            | M/A/E  (Master/Dolby Atmos/Explicit) |
| {AlbumID}         | 55163243                             |
| {AlbumYear}       | 1963                                 |
| {AlbumTitle}      | Please Please Me (Remastered)        |
| {AudioQuality}    | LOSSLESS                             |
| {DurationSeconds} | 1919                                 |
| {Duration}        | 31:59                                |
| {NumberOfTracks}  | 14                                   |
| {NumberOfVideos}  | 0                                    |
| {NumberOfVolumes} | 1                                    |
| {ReleaseDate}     | 1963-03-22                           |
| {RecordType}      | ALBUM                                |
| {None}            |                                      |

### Track

| Tag               | Example Value                              |
| ----------------- | ------------------------------------------ |
| {TrackNumber}     | 01                                         |
| {ArtistName}      | The Beatles                                |
| {ArtistsName}     | The Beatles                                |
| {TrackTitle}      | I Saw Her Standing There (Remastered 2009) |
| {ExplicitFlag}    | (*Explicit*)                               |
| {AlbumYear}       | 1963                                       |
| {AlbumTitle}      | Please Please Me (Remastered)              |
| {AudioQuality}    | LOSSLESS                                   |
| {DurationSeconds} | 173                                        |
| {Duration}        | 02:53                                      |
| {TrackID}         | 55163244                                   |

### Video

| Tag               | Example Value                              |
| ----------------- | ------------------------------------------ |
| {VideoNumber}     | 00                                         |
| {ArtistName}      | DMX                                        |
| {ArtistsName}     | DMX, Westside Gunn                         |
| {VideoTitle}      | Hood Blues                                 |
| {ExplicitFlag}    | (*Explicit*)                               |
| {VideoYear}       | 2021                                       |
| {TrackID}         | 188932980                                  |

## 🎨 Libraries and reference

- [aigpy](https://github.com/yaronzz/AIGPY)
- [python-tidal](https://github.com/tamland/python-tidal)
- [redsea](https://github.com/redsudo/RedSea)
- [tidal-wiki](https://github.com/Fokka-Engineering/TIDAL/wiki)

## 📜 Disclaimer
- Private use only.
- Need a Tidal-HIFI subscription. 
- You should not use this method to distribute or pirate music.
- It may be illegal to use this in your country, so be informed.

## Developing

```shell
pip3 uninstall tidal-dl
pip3 install -r requirements.txt --user
python3 setup.py install
```
