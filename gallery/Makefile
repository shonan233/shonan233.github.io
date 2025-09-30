
all : embroidery-small.jpeg

embroidery-small.jpeg : embroidery.jpeg Makefile
	 magick convert '$<' -thumbnail 400x400 -quality 80 '$@'
