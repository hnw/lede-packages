# LEDE custom packages feed

## Description

GitHub Pages repository for my own LEDE binary packages feed.

## Usage

```
$ echo 'src/gz custom-hnw https://hnw.github.io/lede-packages/17.01.2/ar71xx' >> /etc/opkg/customfeeds.conf
$ opkg update
```

## License

See [LICENSE](LICENSE) file.
