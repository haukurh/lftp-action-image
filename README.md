## haukurh/lftp-action-image

This is a simple Docker image based `alpine:latest` with [LFTP](https://lftp.yar.ru) setup to synchronize files 
over a network. 

## Packages

- `lftp` v4.9.2
- `openssh` v9.3p1
- `openssl` v3.0.8

## Entrypoint

This image is specially setup for [haukurh/lftp-action](https://github.com/haukurh/lftp-action) which is GitHub Action to use LFTP.
The entrypoint is a script that's specifically setup to trigger LFTP by using environment variables.

This image could though be used anywhere either by overwriting the entrypoint or  

## LFTP

> LFTP is a sophisticated file transfer program supporting a number of network protocols (ftp, http, sftp, fish, torrent).

- LFTP website: [lftp.yar.ru](https://lftp.yar.ru)
- LFTP man page: [lftp.yar.ru/lftp-man](https://lftp.yar.ru/lftp-man.html)
- LFTP GitHub repo: [github.com/lavv17/lftp](https://github.com/lavv17/lftp)

## Issues

If you find any problems with this Docker image, please [open an issue](https://github.com/haukurh/lftp-action-image/issues).

## License

The MIT License, check the `LICENSE` file.
