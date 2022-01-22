**Convert FLAC to MP3 in sub-folders, keeping folder structure and metadata**

`find . -name "*.flac" -exec ffmpeg -i {} -ab 192k -map_metadata 0 -id3v2_version 3 {}.mp3 \;`

Source : https://stackoverflow.com/questions/26109837/convert-flac-to-mp3-with-ffmpeg-keeping-all-metadata

**Delete all .flac files in the current directory and subdirectories**

`find . -name "*.flac" -type f -delete`

Source : https://askubuntu.com/a/377442


