<h1 align="center">nyaaflix</h1>
<p align="center">nyaaflix, a tool to search anime torrents from nyaa.si and streams it with peerflix</p>

### How does this work?

This shell script scapes nyaa.si proxy site for magnet links and uses [peerflix](https://github.com/mafintosh/peerflix) to stream anime from magnet link.

## Preview
<p align="center">
<img src="./preview.gif" alt="Video Preview" width="1280px">
</p>

## Usage
`
$ nyaaflix $SEARCH_QUERY
`

## Dependencies
* grep
* sed
* [peerflix](https://github.com/mafintosh/peerflix) - A tool to stream torrent. 
`sudo npm install peerflix -g`

## Installation

```sh
$ sudo curl -o /usr/local/bin/nyaaflix https://raw.githubusercontent.com/seadesert-git/nyaaflix/master/nyaaflix
$ sudo chmod +x /usr/local/bin/nyaaflix
```
To uninstall,
`$ sudo rm /usr/local/bin/nyaaflix`

## License

This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).

