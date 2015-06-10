Tonis and related components are open source and licensed as BSD-3-Clause. Contributions are welcome in the form of issue 
reports and pull requests. All pull requests should meet the requirements outlined on the [Components & Packages](/other/components-and-packages) 
page.

Running Tests
-------------

```sh
composer install
./vendor/bin/phpunit -c test/phpunit.xml
```

Coding Standards
----------------

Tonis uses PSR-2 coding standards and checks standards using [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer).
To check coding standards:

```sh
vendor/bin/phpcs --standard=PSR2 -s -p src/ test/
```

Additonally, this is automatically checked by [Travis CI](https://travis-ci.org) and will cause a build failure if not valid.
