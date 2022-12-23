# 4chan Bulk Downloader
This is a small Shell script to download several images and/or videos from 4chan threads in parallel

# Installation

Just download and copy the `4chan` file into your **$PATH** (*/usr/bin/*, *home/.local/bin*, etc) and give execute permissions (`sudo chmod +x $PATH/4chan`)

# Usage

To download all media files in a thread run `4chan <link>`

To download just images run `4chan <link> -img` (or `4chan <link> --image`)

To download just videos run `4chan <link> -vid` (or `4chan <link> --video`)

To set the number of parallel downloads run `4chan <link> -j <n>` 
