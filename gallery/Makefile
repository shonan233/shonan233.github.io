
all : embroidery-small.jpeg \
	yosegaki-small.jpeg \
	counterpoint-small.jpeg \

%-small.jpeg : %.jpeg Makefile
	 magick convert '$<' -thumbnail 400x400 -quality 80 '$@'
