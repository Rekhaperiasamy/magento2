# About
This is a Magento 2 - Hello World module created as a composer submodule.

# Requirements

- Magento Composer Installer: To copy the module contents under app/code/ folder.
In order to install it run the below command on the root directory:

        composer require magento/magento-composer-installer

- Add the VCS repository: So that composer can find the module. Add the following lines in your composer.json

        "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/Rekhaperiasamy/magento2.git"
        }],


# Installation

- Add the module to composer:

        composer require rekha-software/magento2-module

- Add the new entry in `app/etc/config.php`, under the 'modules' section:

        'Adobe_HelloWorld' => 1,

- Clear cache

# Usage

        http://yourstore/helloworld/index/


Feel free to contribute, and contact me for any issues.


# Version

Updated to version 1.0.1 to achieve a stable version and demonstrate the handling of module updates via composer and tags
Updated to version 1.0.2 to test module update via composer and tags
