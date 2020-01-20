# How I made this:
1. `wget --no-clobber --convert-links --random-wait -r -p -H -E -e robots=off -U mozilla http://chickenandegg.ca/ -Dlive.staticflickr.com,www.chickenandegg.ca,chickenandegg.ca -l9`
2. `mv chickenandegg.ca/* <git-repo>`
3. `mv live.staticflickr.com/* <git-repo>/flickr`
