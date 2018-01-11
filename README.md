# alpine-pkg-php5-xdebug

[![CircleCI](https://circleci.com/gh/sgerrand/alpine-pkg-php5-xdebug/tree/master.svg?style=svg)](https://circleci.com/gh/sgerrand/alpine-pkg-php5-xdebug/tree/master)

This is the [PHP5 extension for Xdebug][php-xdebug] as an Alpine Linux package.

The package provided by Alpine Linux was removed from their repositories in the
3.6 release. A package for PHP7 is still available there.

## Releases

See the [releases page](https://github.com/sgerrand/alpine-pkg-php5-xdebug/releases) for the latest
download links.

## Installing

The current installation method for these packages is to pull them in using
`wget` or `curl` and install the local file with `apk`:

    apk --no-cache add ca-certificates wget
    wget --quiet --output-document=/etc/apk/keys/sgerrand.rsa.pub https://alpine-pkgs.sgerrand.com/sgerrand.rsa.pub
    wget https://github.com/sgerrand/alpine-pkg-php5-xdebug/releases/download/2.5.5-r0/php5-xdebug-2.5.5-r0.apk
    apk add --no-cache php5-xdebug-2.5.5-r0.apk

[php-xdebug]: https://pecl.php.net/xdebug
