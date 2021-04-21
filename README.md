## YouTanion (yoo-taa-nyn)

<p align="center">
  <img width="600" src="https://user-images.githubusercontent.com/45819206/114433153-368ba380-9be1-11eb-9038-183c3aae3d90.png">
</p>

A simplified and interactive CLI based YouTube video downloader for Windows, Linux and Mac

PLEASE READ this document carefully before proceeding.

#### `Download and Installation`

Installation is pretty simple. First clone this repo using the command below in your terminal or command prompt

```sh
git clone https://github.com/iamsubingyawali/youtanion.git
```
Now navigate to the downloaded directory using **cd** command and run the command below to install dependencies. If you have multiple version of pip installed, use pip3.

```sh
pip install -r requirements.txt
```
All the requirements must be installed correctly. After the requirements are installed, run the command below to start the program. If you have multiple Python versions installed on the system, please use Python 3.

```sh
python run.py
```

#### `Single Audio/Video Download`

Downloading is very simple with the interactive prompt. The downloaded videos are stored inside **youtanion/Downloads/Videos** or on the same directory you are running the program on, while the audios are stored inside **youtanion/Downloads/Audios**. The downloaded audios are stored in m4a format. If the downloaded audios are not playable, open an issue.

#### `Playlist Audios/Videos Download`

The playlist download is exactly similar to a single video download. The downloaded videos and audios are stored in the **youtanion/Downloads/Videos** and **youtanion/Downloads/Audios** directories respectively. The playlist to be downloaded must be a public playlist on YouTube. The playlist videos are downloaded with the highest resolution by default.

This program is still in its initial experimental phase. Do not forget to open an issue if any errors occur while using it. 


This program wouldn't have been possible without:

> pytube: https://github.com/pytube/pytube

_Note: This program was solely made for educational purposes and must not be used to download content without the permission of the copyright owner. This program must not be used in any other way that violates YouTube's [terms of service](https://www.youtube.com/static?template=terms)._
