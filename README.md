# Looking for maintainer
These [Magento2Translations](http://magento2translations.github.io/) packages are unmaintained. This means that from time to time we will run the sync and build from Crowdin. But we probably won't add Magento/Crowdin versions. If you would like to continue the work done here please send us a message.

Have a look at all the other great community maintained packages at [e-conomix/magento-translations](https://github.com/e-conomix/magento-translations).
Or [Mageplaza maintained packages](https://github.com/mageplaza?q=language).

# Indonesian (Indonesia) Magento2 Language Pack (id_ID)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The Indonesian (Indonesia) translations used can be found [here](https://crowdin.com/project/magento-2/id).
This translation is usefull for people living in the Indonesia (Indonesia).

For our other language packs look at the [Magento2Translations](http://magento2translations.github.io/) page.

# Version & progress
This translation is generated from the branch [2.2.4](https://crowdin.com/project/magento-2/id#/2.2.4) at Crowdin and based on the Magento 2.2.4 sourcefiles.
There have been  8086 strings translated of the 10156 strings in the Magento source.

Translation progress:![Progress](http://progressed.io/bar/80)

# Installation
**Please select the git branch appropriate for your magento version from this repo.**
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_id_id:2.2.4-dev
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_id_id/archive/2.2.4.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/language_id_id`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/id_ID/id_ID.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*Indonesian (Indonesia)*'

# Contribute
To help push the '*Indonesian (Indonesia) Magento2 Language Pack (id_ID)*' forward please goto [this](https://crowdin.com/project/magento-2/id) crowdin page and translate the lines.

# Authors
The translations are done by the [official Magento2 translations project](https://crowdin.com/project/magento-2).

Code generation is sponsored by [Wijzijn.Guru](http://www.wijzijn.guru/).