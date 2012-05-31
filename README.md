Welcome to my Mutt config
=========================

This is my setup for the currently best mail user agent we have on
earth: [Mutt](http://mutt.org).

First steps
-----------

In order to use this setup, I suggest you to fork this repo, cause I
also have my accounts configured here. This way, you'll really need to
change some things before start using it.

### Getting the conf

You just need to clone your repo, like this:

    $ git clone git@github.com:clarete/muttrc.git ~/.mutt

### Conf structure

This conf is split into small files to make it easy to maintain
things. This setup also support multiple accounts and the basic setup
can be found in the `inc` directory and the account setup can be found
in the `inc/accounts` directory. Each account must have an entry point
file, so you can `mutt -F <file>` to load one or another account, or
just create shell aliases for each account, if you want.
