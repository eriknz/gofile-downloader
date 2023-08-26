# gofile-downloader
Download files from https://gofile.io
modified to accept a .txt file of urls.


# Requirements
```
pip install -r requirements.txt
```

# Usage
```
python gofile-downloader.py urls.txt
```

If it has password (I haven't checked if this works with file import):
```
python gofile-downloader.py urls.txt password
```

Use the environment variable **`GF_DOWNLOADDIR`** to specify where to download to (the
path must exist already):
```
GF_DOWNLOADDIR="/path/to/the/directory" python gofile-downloader.py https://gofile.io/d/contentid

```
