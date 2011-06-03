# EAN-13 barcode maker

## Usage

    ean = EAN13.new('4960999212722')

    # get image blob
    ean.to_png

    # save to 4960999212722.png
    ean.save

    # save to foo.png, 300x100 pixels
    ean.save(to: 'foo.png', width: 300, height: 100)

## Example

![EAN-13 barcode picture](http://boxbot.org/4960999212722.png)
