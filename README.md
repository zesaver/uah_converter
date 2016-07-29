UAH Currency Converter Using PrivatBank API
===========================================

About
-----

These small scripts can be used to convert Ukraine Hrivnas to US Dollars or Euro and vice versa using actual rates. Usage:

``` console
$ eur 50 eur
1237.50  UAH
$ eur 70 EUR
1732.50  UAH
$ usd 1000 uah
40.40  USD
$ usd 20 usd
495.00  UAH
```

Development
-----------

Scripts are written under Python 2.7.12 and use following python modules:

- requests
- argparse
- os
- json
- datetime

Internet connection is required (to use PrivatBank API). Exchange rates are caching for 10 minutes to improve the speed.

Any contributions, forks and advices are welcome!

ToDo
----

- Interactive mode
