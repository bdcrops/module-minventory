

# BDC_Minventory

This module is used as a resupply for stock BDCrops Magento 2 extensions.
Magento 2 Stock / Inventory Management, demonstrating UI grid.




## How to install & upgrade BDC_Minventory


### 1.1 Copy and paste

If you don't want to install via composer, you can use this way.

- Download [the latest version here](https://github.com/bdcrops/module-minventory/archive/master.zip)
- Extract `master.zip` file to `app/code/BDC/Core` ; You should create a folder path `app/code/BDC/Core` if not exist.
- Go to Magento root folder and run upgrade command line to install `BDC_Minventory`:





### 1.2 Install via composer

We recommend you to install BDC_Minventory module via composer. It is easy to install, update and maintaince.Run the following command in Magento 2 root folder.

```
composer config repositories.module-minventory git
https://github.com/bdcrops/module-minventory.git

composer require bdc/module-minventory:~1.0.0
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

#### 1.2 Upgrade    

```
composer update bdcrops/module-minventory
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

Run compile if your store in Product mode:

```
php bin/magento setup:di:compile

```
## Tutorial

![](docs/menuDash.png)
![](docs/minventoryList.png)
![](docs/resupplyStock.png)
![](docs/resupplyaddAfter.png)


### ref
