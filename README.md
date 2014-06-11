ETSDocumentStorageBundle
========================

Symfony bundle that integrates with ets/document-storage.

Installation
============
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

Available services
==================
- ets.document_storage.client.echo_sign
- ets.document_storage.client.s3

Code License
============
[Resources/meta/LICENSE](https://github.com/ETSGlobal/ETSDocumentStorageBundle/blob/master/Resources/meta/LICENSE)
