# yt-dlp-installation

yt-dlp installation process on Linux server

- download appropriate executable from [github release page](https://github.com/yt-dlp/yt-dlp/releases) or build it from source using [project instructions](https://github.com/yt-dlp/yt-dlp?tab=readme-ov-file#compile)
- install ffmpeg on system to download best quality of videos (for more information see [this post](https://www.reddit.com/r/youtubedl/comments/uba0yh/does_ytdlp_automatically_download_the_highest/))
- download browser cookies using [firefox](https://addons.mozilla.org/en-US/firefox/addon/get-cookies-txt-locally/) or [chrome](https://chromewebstore.google.com/detail/get-cookiestxt-locally/cclelndahbckbenkjhflpdbgdldlbecc) extension and copy it on the server
- use --cookies flag to pass cookies file to the yt-dl
```bash
./yt-dlp --cookies cookies.txt <video_link>
```
