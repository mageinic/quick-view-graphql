# Quick View GraphQL

**Quick View GraphQL is a part of MageINIC Quick View extension that adds GraphQL features.** This extension extends Quick View definitions.

## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageinic/quickviewgraphql

php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

**Note:**
Magento 2 Quick View GraphQL requires installing [MageINIC Quick View](https://github.com/mageinic/Quick-View) in your Magento installation.

**Or Install via composer [Recommend]**
```
composer require mageinic/quickview
```

## 2. How to use

- To view the queries that the **MageINIC Quick View GraphQL** extension supports, you can check `Quick View GraphQl User Guide.pdf` Or run `QuickViewGraphQl.postman_collection.json` in Postman.

## 3. Get Support

- Feel free to [contact us](https://www.mageinic.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star**
