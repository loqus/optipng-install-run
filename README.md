# optipng-install-run
Install and run optipng for files all or newer than 30 days

sudo apt-get install optipng

go to the directory

find . -name '*.png' | xargs optipng -strip all
find . -name '*.png' -mtime -30 | xargs optipng -strip all
