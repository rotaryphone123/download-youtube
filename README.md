# download-youtube

- <https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe?utm_source=docker&utm_medium=webreferral&utm_campaign=docs-driven-download-win-amd64>
- <https://github.com/git-for-windows/git/releases/download/v2.47.0.windows.1/Git-2.47.0-64-bit.exe>
- <https://code.visualstudio.com/docs/?dv=win64user>

```sh
git clone https://github.com/rotaryphone123/download-youtube
cd download-youtube
```

```sh
yt-dlp zmAn2SVrJwo -S vcodec:h264,res,acodec:m4a --write-info-json --write-thumbnail --convert-thumbnails png --download-sections "*02:05:08-02:07:32" -o "$(date +"%Y-%m-%d_%H-%M-%S")/%(title)s.% (ext)s"
```
