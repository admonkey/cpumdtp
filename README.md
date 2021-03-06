This is a base template for a project using [PHPUnit][4] and [MySQL dev/test/prod][5] packages.

# Requirements

* PHP >= 5.5.9

The install script uses [wget][3] to download the dependency package manager [Composer v1.1.2][2].
If you do not have [wget][3], then you will need to [manually download Composer][2]
and place `composer.phar` in the project root directory.

# Installation

If you're installing this for production use, then you can get all the dependencies with the script.

    ./install --prod

----------

# Development

You can run the install script with the `--dev` flag to grab the developer tools like [PHPUnit][4].

    ./install --dev

## Testing

To run the test suite, use the `test` script.

    ./test

The verbose flag will show more detailed output.

    ./test -v

----------

[1]:http://php.net/manual/en/book.pdo.php
[2]:https://getcomposer.org/download/
[3]:https://www.gnu.org/software/wget/
[4]:https://phpunit.de/
[5]:https://github.com/jeff-puckett/mysql-dtp

> Written with [StackEdit](https://stackedit.io/).
