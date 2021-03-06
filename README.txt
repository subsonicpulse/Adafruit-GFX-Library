Current additions:

- XBitMap support (*.xbm)
  Use exported xbm files from GIMP with bitmap data directly in your sources.
  (fits perfectly with SSD1306 library from Adafruit)
  New function: Adafruit_GFX::drawXBitmap()
  Usage: Export bitmap with GIMP as *.xbm file,
         Rename the *.xbm to *.c,
         Open file in editor,
         Use C array directly in your sources.

----------------------------------

This is the core graphics library for all our displays, providing a common set of graphics primitives (points, lines, circles, etc.).  It needs to be paired with a hardware-specific library for each display device we carry (to handle the lower-level functions).

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Written by Limor Fried/Ladyada for Adafruit Industries.
BSD license, check license.txt for more information.
All text above must be included in any redistribution.

To download, click the DOWNLOAD ZIP button, uncompress and rename the uncompressed folder Adafruit_GFX. Confirm that the Adafruit_GFX folder contains Adafruit_GFX.cpp and Adafruit_GFX.h

Place the Adafruit_GFX library folder your <arduinosketchfolder>/Libraries/ folder. You may need to create the Libraries subfolder if its your first library. Restart the IDE.
