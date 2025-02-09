# magictube

## Not maintained. Use [https://songpal.tsf.int.eu.org](https://songpal.tsf.int.eu.org/) instead.

a **minimal** tool that **automatically** searches, downloads, saves and plays songs.

![magictube-demo-v2 1](https://user-images.githubusercontent.com/26126049/128795673-bade22ab-bab1-415e-acdc-1140bb654532.gif)

## how does it work?

all you gotta do is type the song you want to listen to. hit enter. done.

magictube finds the most relevant video, downloads & saves its audio, and then plays it.

## why choose magictube?

save memory, bandwidth, time, energy. think smart. it's the youtube experience, reimagined.

## who is this good for?

### **building playlists**
when you want to build a music collection with your favourite songs, this is the easiest way i've ever thought of.
if you want to make a music folder for yourself or a friend, or you want to play songs without having to research them.

### saving bandwidth / memory
if you are on metered internet connection, you don't want to spend MB on page loadings and unnesesary video data.
if you are on low memory, you don't want a browser playing videos to hear precious music (good for gamers!)

## how to run?

type `./magictube` and let the magic begin!

*or* put the file in `/usr/local/bin` then you can start it by typing `magictube` from any dir

## requirements

you must have [`curl`](https://google.com/search?&q=install+curl+linux) and one of the following:

[`yt-dlp`](https://github.com/yt-dlp/yt-dlp) (recommended), or [`youtube-dl`](https://youtube-dl.org), or [`youtube-dlc`](https://github.com/blackjack4494/yt-dlc).

tested on ubuntu 21.04. should work pretty much everywhere.

## configuration

in the script's first section (Config) there are two options:

1. working dir. this is the download folder. change this if you want
2. downloader. this is the youtube-dl variant. first it checks for yt-dlp. you can change the order
