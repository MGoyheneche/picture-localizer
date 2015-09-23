# Picture Localizer

Picture localizer helps you to get google maps data from a picture.

## Usage

``` javascript
var pctrLclzr = require('picture-localizer');

pctrLclzr.gmapApiKey = 'your_api_key';

pctrLclzr.localize('image.jpg', function(data){
  console.log(data);
});

```


## Dependencies

Picture Localizer uses ImageMagick (you have to install Image Magick cli). Please refer to : https://github.com/yourdeveloper/node-imagemagick

#### Thanks :)
