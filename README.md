# slick externs for Haxe

## Overview

This is extern for Haxe.

Original JavaScript code:
https://github.com/kenwheeler/slick/

Original API document:
https://kenwheeler.github.io/slick/


## Example

This is extern.
Load slick in HTML.

Please read the jQueryExternForHaxe documentation carefully. You need jQueryExternForHaxe to work well.

https://github.com/andyli/jQueryExternForHaxe

Haxe code:

```haxe
import js.Browser;
import js.jquery.JQuery;

class Main {

  public static function main():Void {

    Browser.window.addEventListener('DOMContentLoaded', init);

  }

  private static function init():Void {

    new JQuery('.variable-width').slick({
      dots: true,
      infinite: true,
      speed: 300,
      slidesToShow: 1,
      centerMode: true,
      variableWidth: true
    });

  }

}
```

## References

Original JavaScript code:
https://github.com/kenwheeler/slick/

Original API document:
https://kenwheeler.github.io/slick/
