# Image converter and manup
This is the image converter with using Imagick .

## Development Stack
PHP
Imagick library

###sample
// open an image file
$img = Image::make('public/foo.jpg');

// resize image instance
$img->resize(320, 240);

// insert a watermark
$img->insert('public/watermark.png');

// save image in desired format
$img->save('public/bar.jpg');