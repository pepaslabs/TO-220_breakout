TO-220_breakout
===============

A breakout board for mounting TO-220 parts to a heatsink.

Top side of board:

![alt text](https://raw.github.com/pepaslabs/TO-220_breakout/master/revisions/v1/top.png "Top side of board")

Bottom side of board:

![alt text](https://raw.github.com/pepaslabs/TO-220_breakout/master/revisions/v1/bottom.png "Bottom side of board")

## Two TO-220 footprints

A second TO-220 footprint has been included for mounting to the back side of the heatsink.  This is useful for, e.g.:
* mounting a second TO-220 device which shares the thermal load.
* mounting a temperature sensor to the heatsink.

## Mounting holes

The three mounting holes are sized for M3 male brass hex standoffs:

![alt text](https://raw.github.com/pepaslabs/TO-220_breakout/master/github%20media/m3_hex_standoffs.jpg "M3 hex standoffs")

I recommend buying these in quantity on ebay.  Search for ["m3 male brass hex standoff"](http://www.ebay.com/sch/i.html?_nkw=m3+brass+male+hex+standoff).

The forward two mounting holes are spaced 1.5" center-to-center.  The rear mounting hole center is placed 1.25" above the centerline of the forward two mounting holes.

## Heatsink

![alt text](https://raw.github.com/pepaslabs/TO-220_breakout/master/github%20media/530002B02500.jpg "Aavid 530002B02500G heat sink")

This board was designed for the following [Aavid Thermalloy](http://www.aavid.com/) heatsinks based on the [63130 extrusion](http://www.aavid.com/products/extrusion-heatsinks/63130):
* [529702B02500G](http://www.aavid.com/products/standard/529702b02500g) (1.0" height, 5.5&deg;C/W) ([digikey](http://www.digikey.com/product-detail/en/529702B02500G/HS404-ND/1625478))
* [529802B02500G](http://www.aavid.com/products/standard/529802b02500g) (1.5" height, 4.5&deg;C/W) ([digikey](http://www.digikey.com/product-detail/en/529802B02500G/HS350-ND/1216357), [jameco](https://www.jameco.com/webapp/wcs/stores/servlet/Product_10001_10001_2039793_-1))
* [529902B02500G](http://www.aavid.com/products/standard/529902b02500g) (2.0" height, 3.7&deg;C/W) ([digikey](http://www.digikey.com/product-detail/en/529902B02500G/HS374-ND/1216379))
* [530002B02500G](http://www.aavid.com/products/standard/530002b02500g) (2.5" height, 2.6&deg;C/W) ([digikey](http://www.digikey.com/product-detail/en/530002B02500G/HS380-ND/1216384), [jameco](https://www.jameco.com/webapp/wcs/stores/servlet/Product_10001_10001_696626_-1))

See also [page 56 of the Aavid catalog](http://www.aavid.com/sites/default/files/literature/Aavid-Board-Level-Heatsinks-Catalog.pdf#page=56).

Here is a performance chart for largest of those heatsinks (530002B02500G), generated by the tool on the [63130 extrusion](http://www.aavid.com/products/extrusion-heatsinks/63130) page:

![alt text](https://raw.github.com/pepaslabs/TO-220_breakout/master/github%20media/530002B02500_performance.png "530002B02500G performance")

Typically, pin 2 of a TO-220 part will be shorted to the backing plate which mounts to the heatsink.  Thus, if pin 2 is not ground, the TO-220 will need to be electrically insulated from the heatsink, for which you will need a thermally conductive, electrically insulating pad.  These are typically made of silicone ("sil-pads") or mica, which is more thermally conductive than silicone.  I use [these mica pads from jameco](https://www.jameco.com/webapp/wcs/stores/servlet/Product_10001_10001_34121_-1) which include mounting hardware.

## OSHPark URL:

Have this board manufactured by OSHPark: http://oshpark.com/shared_projects/35mMKncx

## License

This board design is [Open-Source Hardware](http://www.oshwa.org/definition/).  It is licensed under the [MIT License](http://opensource.org/licenses/MIT).  It was designed by Jason Pepas and (will be) sold by Pepas Labs, LLC on tindie.com.
