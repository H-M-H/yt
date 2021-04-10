# yt
Search and play YouTube videos via command line.

## Installation
yt is just a simple bash script and relies on `youtube-dl`, `jq`, `fzf` and `mpv` for the heavy
lifting, so make sure these programs are installed.

## Usage
```
USAGE yt [OPTIONS] "SEARCH STRING"

Search and play YouTube videos.

  -h, --help         Show this help.
  -n, --num-results  Number of search results to fetch, defaults to 50.
  -c, --consumer     Command to be called with URLs of selected videos,
                     default is mpv.
  -v, --version      Print version.
  --                 Stops interpreting the following arguments as options.
```
