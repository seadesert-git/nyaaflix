<h1 align="center">NYAAFLIX</h1>
<p align="center">Use nyaaflix, a tool to search magnet links from nyaa.si and stream it with peerflix</p>

##
<p align="center">
<img src="./preview.gif" alt="Video Preview" width="500px">
</p>

### How does this work?

This shell script scapes nyaa.si proxy site for magnet links and uses [peerflix](https://github.com/mafintosh/peerflix) to stream the video from magnet link.


## Usage
$ nyaaflix $SEARCH_QUERY

## Dependencies
* grep
* sed
* [peerflix](https://github.com/mafintosh/peerflix) - A tool to stream torrent. `sudo npm install peerflix -g`

## Installation

```sh
$ sudo curl -o /usr/local/bin/nyaaflix https://raw.githubusercontent.com/seadesert-git/nyaaflix/master/nyaaflix
$ sudo chmod +x /usr/local/bin/nyaaflix
```
- To uninstall,
$ sudo rm /usr/local/bin/nyaaflix

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).

