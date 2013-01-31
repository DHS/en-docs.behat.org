= Behat documentation (English)

This repository contains the latest version of the documentation 
found at http://docs.behat.org.

To generate documentation on your local machine, you will need
to install the Sphinx documentation system.

On Debian GNU/Linux and similar systems such as Ubuntu or 
Linux Mint, Sphinx is usually included in the default repositories
and you can install it with:

    # apt-get install python-sphinx

Then, to generate the documentation itself, use the provided
Makefile. For example, to generate everything in one single
HTML file, use:

    $ make singlehtml

The result will be found in build/singlehtml.

To build multiple HTML pages in directories, use:

    $ make dirhtml

There are other build targets as well. If you want to see a list
of available targets, just run make without any arguments:

    $ make


