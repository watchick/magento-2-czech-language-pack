## Magento 2 Czech Language Pack

From Magento 2 Translation Project, **Magento 2 Czech Language Pack** is guided by Mageplaza in order to bring the efficient way that helps you convert Magento 2 default language into Czech Language. All words and phrases from the storefront and backend will be translated according to the data translation at Crowdin. Here, you will learn how to download and install Czech language package on your magento 2 store. Continue reading this post to get full of the instructions.

Read more [Magento 2 Czech Language Pack](https://www.mageplaza.com/magento-2-czech-language-pack.html)


## Overview

1. [Language Package Process](#process)
2. [Install Czech Language Pack](#install)
3. [How to active Czech language pack](#active)
4. [How to contribute](#contribute)
5. [Supported Magento versions](#support)

## 1. Language Package Process{#process}

This is status of Czech Language Pack, you can see how many percentage of this project has been done.

![language pack](http://progressed.io/bar/66?title=translated)

It is not fully translated? Feel free to contribute:
- [On Crowdin](https://crowdin.com/project/magento-2): It takes time to approve your contribution by Magento team.
- [On Github](https://github.com/mageplaza/magento-2-czech-language-pack/blob/master/HOW-TO-CONTRIBUTE.md): It's faster, our team will approve it after you send pull request.


Find other [language packs here](https://www.mageplaza.com/kb/magento-2-language-pack/)

## 2. How to Install Czech Language Pack{#install}

There are 3 different methods to install this language pack.

### ✓ Method #1. Composer method (Recommend)
Install the Czech language pack via composer is never easier.

**Install Czech pack**:

```
composer require mageplaza/magento-2-czech-language-pack:dev-master
php bin/magento setup:static-content:deploy cs_CZ
php bin/magento cache:flush

```


**Update  Czech pack**:

```
composer update mageplaza/magento-2-czech-language-pack:dev-master
php bin/magento setup:static-content:deploy cs_CZ
php bin/magento cache:flush

```

#### Authentication required (If any)

![Authentication required](https://cdn.mageplaza.com/media/general/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)

Or use this keys:

```
Public Key: c7af1bfc9352e9c986637eec85ed53af
Private Key: 17e1b72ea5f0b23e9dbfb1f68dc12b53
```



### ✓ Method #2. Copy & Paste method (Not recommended)

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Czech language pack
- Step 2: Unzip Czech pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Czech language pack

You can download the language pack from above link

#### Step 2: Unzip Czech pack

Unzip the Czech language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip master.zip app/i18n/Mageplaza/cs_cz
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### ✓ Method #3. Download and install manually (Not recommended)

To download and install Czech pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-czech-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-czech-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `cs_CZ.zip` into `app/i18n/mageplaza/cs_CZ/cs_CZ.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## 3. How to active Czech language pack{#active}

Now time to active the Czech language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Czech language pack}}](https://cdn.mageplaza.com/media/general/aPSUA0l.png)


## 4. How to contribute{#contribute}

Contribute to this language at :
- [On Crowdin](https://crowdin.com/project/magento-2): It takes time to approve your contribution by Magento team.
- [On Github](https://github.com/mageplaza/magento-2-czech-language-pack/blob/master/HOW-TO-CONTRIBUTE.md): It's faster, our team will approve it after you send pull request.


## 5. Supported Magento versions{#support}

It supports all Magento 2 versions include [Magento 2 open-source](https://www.mageplaza.com/download-magento/), Magento 2 Commerce.


- Magento v2.0.x
- Magento v2.1.x
- Magento v2.2.x



## 6. Notes{#important-notes}

- This project automatically updates weekly from Crowdin.
- Any question, issue please [create a new issue](https://github.com/mageplaza/magento-2-czech-language-pack/issues/new)

## 7. Language package authors{#authors}

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Magento Community
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


## 8. References:

- https://www.mageplaza.com/magento-2-czech-language-pack.html
- https://crowdin.com/project/magento-2




## Mageplaza extensions on Magento Marketplace, Github


- [Layered Navigation](https://marketplace.magento.com/mageplaza-layered-navigation-m2.html)
- [One Step Checkout](https://marketplace.magento.com/mageplaza-magento-2-one-step-checkout-extension.html)
- [SMTP](https://marketplace.magento.com/mageplaza-module-smtp.html) ; [SMTP on Github](https://github.com/mageplaza/magento-2-smtp)
- [Blog](https://github.com/mageplaza/magento-2-blog)
- [Security](https://marketplace.magento.com/mageplaza-module-security.html)
- [Social Login](https://github.com/mageplaza/magento-2-social-login)
- [SEO](https://github.com/mageplaza/magento-2-seo) ; [SEO on Marketplace](https://marketplace.magento.com/mageplaza-magento-2-seo-extension.html)
- [SMTP](https://github.com/mageplaza/magento-2-smtp)
- [Product Slider](https://github.com/mageplaza/magento-2-product-slider)
- [Banner](https://github.com/mageplaza/magento-2-banner-slider)
- [Sample Payment Method](https://github.com/mageplaza/magento-2-sample-payment-method)



