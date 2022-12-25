# 4chan Bulk Downloader
This is a small Shell script to download several images and/or videos from 4chan threads in parallel


# Dependencies
`curl`  
`wget`  
`parallel`    

# Installation

Just download and copy the `4chan-bd` file into your **$PATH** (*/usr/bin/*, *$HOME/.local/bin*, etc) and give execute permissions (`sudo chmod +x $PATH/4chan-bd`)

# Usage

To download all media files in a thread run 
```
4chan-bd <link>
```

To download just images run 
```
4chan-bd <link> -img
```
or 
```
4chan-bd <link> --image
```

To download just videos run 
```
4chan-bd <link> -vid
```
or
```
4chan-bd <link> --video
```

To set the number of parallel downloads run
```
4chan-bd <link> -j <n>
``` 
