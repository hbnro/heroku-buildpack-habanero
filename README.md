Habanero build pack
===================

This is a build pack for Heroku for Habanero apps.

This is based on the [heroku-buildpack-silex](https://github.com/klaussilveira/heroku-buildpack-silex/).


Compiling binaries
------------------

In order to create the packages used by the build pack, you must compile Apache, PHP and their extensions with the following steps.

The default packages were built on Ubuntu 10.04 64 bits in order to be compatible with Heroku dynos.

Get the installation script at "[Apache & PHP / Heroku pre-compile script](https://gist.github.com/3152679)".


Hacking
-------

To change this buildpack, fork it on Github. Push up changes to your fork, then create a test app with --buildpack <your-github-url> and push to it.


Meta
----

Original build pack created by Pedro Belo. Composer support by Henri Bergius. Silex build pack by Klaus Silveira.
