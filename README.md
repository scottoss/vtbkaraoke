

```
usage: app.py [-h] [-p PORT] [-f FFMPEG_PORT] [-d DOWNLOAD_PATH] [-y YOUTUBEDL_PATH] [-v VOLUME] [-s SPLASH_DELAY] [-t SCREENSAVER_TIMEOUT]
              [-l LOG_LEVEL] [--hide-url] [--prefer-ip] [--hide-raspiwifi-instructions] [--hide-splash-screen] [--dual-screen] [--high-quality]
              [--logo-path LOGO_PATH] [-u URL] [--hide-overlay] [--admin-password ADMIN_PASSWORD]

options:
  -h, --help            show this help message and exit
  -p PORT, --port PORT  Desired http port (default: 5555)
  -f FFMPEG_PORT, --ffmpeg-port FFMPEG_PORT
                        Desired ffmpeg port. This is where video stream URLs will be pointed (default: 5556)
  -d DOWNLOAD_PATH, --download-path DOWNLOAD_PATH
                        Desired path for downloaded songs. (default: ~/pikaraoke-songs)
  -y YOUTUBEDL_PATH, --youtubedl-path YOUTUBEDL_PATH
                        Path of youtube-dl. (default: /Users/vic/coding/pikaraoke/.venv/bin/yt-dlp)
  -v VOLUME, --volume VOLUME
                        Set initial player volume. A value between 0 and 1. (default: 0.85)
  -s SPLASH_DELAY, --splash-delay SPLASH_DELAY
                        Delay during splash screen between songs (in secs). (default: 3 )
  -t SCREENSAVER_TIMEOUT, --screensaver-timeout SCREENSAVER_TIMEOUT
                        Delay before the screensaver begins (in secs). (default: 300 )
  -l LOG_LEVEL, --log-level LOG_LEVEL
                        Logging level int value (DEBUG: 10, INFO: 20, WARNING: 30, ERROR: 40, CRITICAL: 50). (default: 20 )
  --hide-url            Hide URL and QR code from the splash screen.
  --prefer-hostname     Use the local hostname instead of the IP as the connection URL. Use at your discretion: mDNS is not guaranteed to work on all
                        LAN configurations. Defaults to False
  --hide-raspiwifi-instructions
                        Hide RaspiWiFi setup instructions from the splash screen.
  --hide-splash-screen, --headless
                        Headless mode. Don't launch the splash screen/player on the pikaraoke server
  --high-quality        Download higher quality video. Note: requires ffmpeg and may cause CPU, download speed, and other performance issues
  --logo-path LOGO_PATH
                        Path to a custom logo image file for the splash screen. Recommended dimensions ~ 2048x1024px
  -u URL, --url URL     Override the displayed IP address with a supplied URL. This argument should include port, if necessary
  --hide-overlay        Hide overlay that shows on top of video with pikaraoke QR code and IP
  --admin-password ADMIN_PASSWORD
                        Administrator password, for locking down certain features of the web UI such as queue editing, player controls, song editing,
                        and system shutdown. If unspecified, everyone is an admin.
```


