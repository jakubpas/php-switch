# php-switch

* The script allows to change php version from command line on fly. Changes version both for command line and under apache
* It was tested under Ubuntu 14.04 and 16.04

## How to install

* add multiple php version into your system. You can do it by installing Ondřej Surý ppa:

'''sudo add-apt-repository ppa:ondrej/php
'''sudo apt-get update
''' sudo apt-get install php...

* edit line: version=(["php53"]="PHP 5.3.29" ["php5"]="PHP 5.59" ["php7"]="PHP 7.0.14") and add versions supported under your system
* copy file to /usr/local/bin
* run script as root.

