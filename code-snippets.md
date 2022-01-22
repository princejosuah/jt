**Convert FLAC to MP3 in sub-folders**
`find . -name "*.flac" -exec ffmpeg -i {} -ab 192k -map_metadata 0 -id3v2_version 3 {}.mp3 \;`

**Delete all .flac files in the current directory and subdirectories**
`find . -name "*.flac" -type f -delete`
