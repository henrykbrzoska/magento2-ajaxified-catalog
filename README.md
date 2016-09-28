## Ajax Layered Navigation module for Magento2
This module applies AJAX on the products catalog page. The left layered navigation block links are also modified to load via AJAX.

If you have any issues using this module, you may contact us at support@czonetechnologies.com

###Why AJAX?
Catalog is the most visited section of any e-commerce site. A fast loading catalog section is intrinstic to a superior user experience.
For faster loading of the catalog section, it is necessary that we do not rebuild the entire page on each request, instead only the minimum required sections are rebuilt. This results in a faster UX.

####1 - Installation
##### Manual Installation

 * Download the extension
 * Unzip the file
 * Create a folder {Magento root}/app/code/CzoneTech
 * Extract the contents of the zipped folder inside it.


#####Using Composer

```
composer config repositories.czone-tech-ajaxified-catalog git git@github.com:czone-tech/ajaxified-catalog.git
composer require czone-tech/ajaxified-catalog
```

####2 -  Enabling the module
Using command line access to your server, run the following commands -
```
 $ php -f bin/magento module:enable --clear-static-content CzoneTech_AjaxifiedCatalog
 $ php -f bin/magento setup:upgrade
```


## Screenshot
![image](https://cloud.githubusercontent.com/assets/1729518/18911185/372d6b4c-8599-11e6-926b-bca83dc0b266.png)
