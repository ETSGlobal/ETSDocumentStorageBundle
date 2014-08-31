# ETS DocumentStorage Bundle

[![Latest Stable Version](https://poser.pugx.org/ets/document-storage-bundle/v/stable.svg)](https://packagist.org/packages/ets/document-storage-bundle)
[![Total Downloads](https://poser.pugx.org/ets/document-storage-bundle/downloads.svg)](https://packagist.org/packages/ets/document-storage-bundle)
[![Latest Unstable Version](https://poser.pugx.org/ets/document-storage-bundle/v/unstable.svg)](https://packagist.org/packages/ets/document-storage-bundle)
[![License](https://poser.pugx.org/ets/document-storage-bundle/license.svg)](https://packagist.org/packages/ets/document-storage-bundle)

Symfony bundle that integrates with ets/document-storage.

## Installation

You can install the bundle using composer.
```
composer.phar require ets/document-storage-bundle
```
See the tags to know which version to use when it asks for a version.

##Enabling the bundle

Enable the bundle in the kernel:
``` php
<?php
// app/AppKernel.php

public function registerBundles()
{
    $bundles = array(
        // ...
        new ETS\DocumentStorageBundle\ETSDocumentStorageBundle()
    );
}
```

## Available services

- ets.document_storage.client.echo_sign
- ets.document_storage.client.s3.base

## Available S3 specific parameters

- ets.document_storage.s3.config.profile
- ets.document_storage.s3.config.region

Code License
============
[Resources/meta/LICENSE](https://github.com/ETSGlobal/ETSDocumentStorageBundle/blob/master/Resources/meta/LICENSE)
