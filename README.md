# Flysystem2 Adapter for BunnyCDN Storage with S3

Please see new combined repository:
[bunnycdn-s3-flysystem-adapter:^2.0.0](https://github.com/tinect/bunnycdn-s3-flysystem-adapter/tree/v2)

This adapter supports Flysystem with version 2 for BunnyCDN.  
## Installation

```bash
composer require tinect/bunnycdn-s3-flysystem-adapter
```

## Usage

```php
use League\Flysystem\Filesystem;
use Tinect\Flysystem\BunnyCDN\BunnyCDNAdapter;

$client = new BunnyCDNAdapter('storageName', 'api-key-or-ftp-passwort', 'storage.bunnycdn.com', 'optionalSubfolder');
$filesystem = new Filesystem($client);
```
