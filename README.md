## Magento 2 Finnish Language Pack

**Magento 2 Finnish Language Pack** is the perfect guide so that you can enable Finnish on your magento 2 store. This translation is really necessary for everyone who are living in the Finland. Here is a step-by-step guide to install Finnish package and use it as the default language.

Read more [Magento 2 Finnish Language Pack](https://www.mageplaza.com/magento-2-finnish-language-pack.html)


## Overview

- Download & Contribute
- Install Finnish Language Pack
- How to Install Finnish Language Pack

## Download & Contribute to Finnish Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Finnish Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-finnish-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-finnish-language-pack/tarball/master)
- [Copy & paste package](https://crowdin.com/project/magento-2/fi.zip)


Find other [language packs here]({https://www.mageplaza.com/kb/magento-2-language-pack/)

## How to Install Finnish Language Pack

There are 3 different methods to install this language pack.

### #1. Composer method
Install the Finnish language pack via composer is never easier.

**Install Finnish pack**:

```
composer require mageplaza/magento-2-finnish-language-pack:*
php bin/magento cache:clean
php bin/magento setup:static-content:deploy fi-fi

```


**Update  Finnish pack**:

```
composer update mageplaza/magento-2-finnish-language-pack:*
php bin/magento cache:clean
php bin/magento setup:static-content:deploy fi-fi

```

### #2. Copy & Paste method

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Finnish language pack
- Step 2: Unzip Finnish pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Finnish language pack

You can download the language pack from above link

#### Step 2: Unzip Finnish pack

Unzip the Finnish language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip /var/www/html/
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### #3. Download and install manually

To download and install Finnish pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-finnish-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-finnish-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `fi_FI.zip` into `app/i18n/mageplaza/fi_FI/fi_FI.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## How to active language pack

Now time to active the language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Finnish language pack}}](https://i.imgur.com/aPSUA0l.png)


## Translation process of Finnish Language Pack
![process](http://progressed.io/bar/80)

Contribute to this language at https://crowdin.com/project/magento-2/fi

## Supported Magento versions

- Magento v2.0.0
- Magento v2.0.1
- Magento v2.0.2
- Magento v2.0.3
- Magento v2.0.4
- Magento v2.0.5
- Magento v2.0.6
- Magento v2.0.7
- Magento v2.0.8
- Magento v2.1.0
- Magento v2.1.1
- Magento v2.1.2



## Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


References:
- https://www.mageplaza.com/magento-2-finnish-language-pack.html
- https://www.mageplaza.com/kb/magento-2-language-pack/