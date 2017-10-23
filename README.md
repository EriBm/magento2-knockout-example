## Knockout example module

The sample module of using Knockout in Magento 2.

### Feature:

- Simple example of using Knockout with MVVM pattern in Magento 2 display on product page.

### Install:

```bash
mkdir app/code/Unet
git clone git@github.com:dhduc/magento2-knockout-example.git app/code/Unet/Knockout
php bin/magento module:enable Unet_Knockout
php bin/magento setup:upgrade
php bin/magento cache:flush
php bin/magento setup:static-content:deploy
```

### Reference:

- [http://inchoo.net/magento-2/knockout-js-in-magento-2/](http://inchoo.net/magento-2/knockout-js-in-magento-2/)

- [https://inviqa.com/blog/using-knockout-js-magento-2](https://inviqa.com/blog/using-knockout-js-magento-2)
