![]( https://icepay.com/app/themes/icepay/dist/images/logos/logo_icepay.svg)

# This repo is deprecated

New implementations should use the ICEPAY REST API and its available clients.
[PHP REST client](https://github.com/ICEPAYdev/REST-API-PHP)
[.NET REST client](https://github.com/ICEPAYdev/REST-API-NET)

# ICEPAY PHP API

[![Latest Stable Version](https://poser.pugx.org/icepay/icepay/v/stable.svg)](https://packagist.org/packages/icepay/icepay)
[![Total Downloads](https://poser.pugx.org/icepay/icepay/downloads.svg)](https://packagist.org/packages/icepay/icepay)
[![Latest Unstable Version](https://poser.pugx.org/icepay/icepay/v/unstable.svg)](https://packagist.org/packages/icepay/icepay)
[![License](https://poser.pugx.org/icepay/icepay/license.svg)](https://packagist.org/packages/icepay/icepay)

The documentation for this API can be found at [our website](https://icepay.com/downloads/tech-docs/ICEPAY_API-2.x-manual.pdf)

## Contributing ##

* Fork it
* Create your feature branch (`git checkout -b my-new-feature`)
* Commit your changes (`git commit -am 'Add some feature'`)
* Push to the branch (`git push origin my-new-feature`)
* Create new Pull Request

## Bug report ##

If you found a repeatable bug, and troubleshooting tips didn't help, then be sure to [search existing issues](https://github.com/icepay/icepay/issues) first. Include steps to consistently reproduce the problem, actual vs. expected results, screenshots, and your API module version number.

## Changelog ##

Version | Release date | Changes
------- | ------------ | ------------------------
2.5.3   | 17/08/2015   | Added BIC to getPayment() function.<br>Track a users transaction (see [#2](https://github.com/icepay/icepay/pull/2) for more information).
2.5.2   | 18/08/2015   | Added [LICENSE](https://github.com/icepay/icepay/blob/develop/LICENSE.md) to API repository.<br>Updated supported payment method parameters.
2.5.1   | 18/12/2014   | Removed Friesland Bank from iDEAL issuers.
2.5.0   | 29/08/2014   | Fix checksum calculation (autoCheckout checksum differs)
