# google_fonts_arabic

Arabic fonts by google right into your flutter application. Courtsey of fonts.google.com

## Getting Started

Until this package get listed on dartlang, add the package to your project as follows:

```ssh
google_fonts_arabic:
      git: git://github.com/emadomedher/google-fonts-arabic.git
      version: ^0.0.5
```
Import the list of fonts like this:

```ssh
import 'package:google_fonts_arabic/fonts.dart';
```

Then you can view the available fonts like this through the ArabicFonts clas:

![alt text](http://206.189.25.244/goole_arabic_fonts.png)

In your text widgets, use it like this:

```ssh
  Text(
      "كيف حالك يا أخ العرب؟",
      style: new TextStyle(
        fontFamily: ArabicFonts.Cairo,
        package: 'google_fonts_arabic',
        fontSize: 25.0,
      ),
    ),
``` 

Enjoy ^_^
