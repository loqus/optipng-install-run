# optipng-install-run
Install and run optipng for files

sudo apt-get install optipng

go to the directory

find . -name '*.png' | xargs optipng -strip all
