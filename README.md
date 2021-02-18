# PayU module for OpenCart version 3.x
`` The module is released under the GPL license. ''

** If you have any questions or want to report a bug, please contact our [technical support] [ext7]. **

* If you are using OpenCart version 2.3.x please use [plugin version 3.2.x] [ext1]
* If you are using OpenCart version 2.0.x, 2.1.x or 2.2.x please use [plugin version 3.1.x] [ext2]


## Table of Contents

* [Features and Compatibility] (# Features-and-Compatibility)
* [Requirements] (# requirements)
* [Installation] (#installation)
* [Update] (# update)
* [Configuration] (# configuration)

## Features and Compatibility
The PayU payment module adds the PayU payment option to OpenCart and allows you to:

* Creation of payments (along with discounts)
* Automatic receipt of notifications and change of order statuses

## Requirements

** Important: ** This module works only with a `REST API` (Checkout) payment point, if you do not have an account in the PayU system yet - [** Register **] [ext6]

The following PHP extensions are required for the proper functioning of the module: [cURL] [ext3] and [hash] [ext4].

## Installation

1. Download the module from [GitHub] [ext5] as a zip file.
1. Unpack the downloaded file.
1. Connect to the ftp server and copy the contents of the `upload` directory from the unpacked file to the root of your OpenCart store.
1. Go to the admin page of your OpenCart store [http: // store-address / admin].
1. Navigate to `Extensions`» `Extensions`.
1. Set the filter to `Payments`.
1. Find `PayU` on the list and click the` Install` icon.

## Configuration

1. Go to the admin page of your OpenCart store [http: // store-address / admin].
1. Navigate to `Extensions`» `Extensions`.
1. Set the filter to `Payments`.
1. Find `PayU` on the list and click the` Edit` icon.

#### Configuration parameters


| Parameter | Description |
| --------- | ----------- |
| Status | Determines whether the PayU payment method will be available in the store on the payment list. |
| Order | Specifies on which position the PayU payment method available in the shop on the payment list is to be displayed. |
| Order sum | The minimum order value from which the PayU payment method is available in the store on the payment list. |
| Geo zone | Geo zone, for which the PayU payment method is available in the store on the payment list. |
| Point of payment id | POS ID from the PayU system |
| Second key (MD5) | Second MD5 key from PayU system |
| OAuth protocol - client_id | client_id for OAuth protocol from PayU system |
| OAuth protocol - client_secret | client_secret for OAuth from PayU system |

#### Status parameters
Defines the relationship between order statuses in PayU and order statuses in OpenCart.

<! - LINKS ->

<! - external links: ->
[ext0]: README.EN.md
[ext1]: https://github.com/PayU/plugin_opencart_2
[ext2]: https://github.com/PayU/plugin_opencart_2/tree/opencart_2_2
[ext3]: http://php.net/manual/en/book.curl.php
[ext4]: http://php.net/manual/en/book.hash.php
[ext5]: https://github.com/PayU/plugin_opencart_3
[ext6]: https://www.payu.pl/oferta-handlowa
[ext7]: https://www.payu.pl/pomoc

<! - images: -> 
