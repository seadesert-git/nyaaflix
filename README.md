<h1 align="center">NYAAFLIX</h1>
<p align="center">Use nyaaflix, a tool to search magnet links from nyaa.si and stream it with peerflix</p>

##
<p align="center">
<img src="./preview.gif" alt="Video Preview" width="500px">
</p>

### How does this work?

This shell script scapes nyaa.si proxy site for magnet links.
After this it use [peerflix](https://github.com/mafintosh/peerflix) to stream the video from magnet link.
For scraping script use simple gnu utils like sed, awk, paste, cut.

## Requirements

* [peerflix](https://github.com/mafintosh/peerflix) - A tool to stream torrent. `sudo npm install peerflix -g`

## Installation

### cURL
cURL **notflix** to your **$PATH** and give execute permissions.

```sh
$ cd /usr/local/bin/
$ git clone https://github.com/seadesert-git/nyaaflix/
$ sudo chmod +x /usr/local/bin/nyaaflix/nyaaflix
```
- To uninstall, simply remove `nyaaflix` from your **$PATH**, for example `sudo rm -r /usr/local/bin/nyaaflix.

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).

