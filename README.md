cexio-reinvest
==============

A minor personal project to calculate and visualize some thoughts about a good mining/re-invest strategy at cex.io.  Mostly it's just a simple HTML/JavaScript/Highchart page calculating possible earnings, if all bitcoin mining return will be re-invested at cex.io.

## How to use

You can use this tool at [my site](http://www.ltcinstawallet.com/cexio-reinvest).

### Selfhosted

On your web server do:

```
git clone git@github.com:johndoe75/cexio-reinvest.git
```

and point your browser to `http://{yourdomain}/cexio-reinvest/index.html`.

## TODO

* Add possibility to specify after which time a specific amount of GH/s will be added beside the cex.io re-investment.  E.g. double GH/s every 3 months or add 100 GH/s every 6 months or so.

* Get the current difficulty e.g. from [blockchain.info](https://blockchain.info/de/q/getdifficulty).

* Get the current price per GH/s from cex.io API.

* Add a table with results -- incl. earnings in USD and EUR.  Get the exchange rate from MtGox.

* Take in account, that the hashpower will greatly increase beginning next year (when new Avalon or Butterfly Labs miners will arrive on market).

* …

## Credits & License

Alexander Zschach <alex@zschach.net>

### Donate

If you like this tool, find it useful or if you just find it useful, that people out there writing free software for everybody to use or contribute, please donate some coins:

Bitcoins `1MzFr1eKzLEC1tuoZ7URMB7WWBMgHKimKe`
Litecoins `LSRfZJf75MtwzrbAUfQgqzdK4hHpY4oMW3`
Terracoins `1MsuC6knLeZKHCyQ39Xcw1qcgScS1ZK5R`
Feathercoins `6tfEE48qk8Kgs9ancC82Y2iQBSX3VGYXfL`

### License

The MIT License (MIT)

Copyright (c) 2013 Alexander Zschach alex@zschach.net

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
