# Practicalli Spacemacs configuration

This GitHub repository contains the current configuration to support the [Practicalli Spacemacs book](https://practicalli.github.io/spacemacs).  It contains the layers recommended for use for enhanced Clojure development experience as well as numerous tweaks for general [Spacemacs](https://github.com/syl20bnr/spacemacs/) usage.  The configuration also contains a number of snippets (code and configuration templates) for specific languages.

[![Practicalli Spacemacs book cover](https://practicalli.github.io/images/practicalli-spacemacs-book-cover.png)](https://practicalli.github.io/spacemacs)


## Using this configuration directly

Visit GitHub and fork the practicalli/spacemacs.d repository.  A fork is recommended so you can add your own customisations and save them to your own repository.

In a terminal window, use git clone to copy your fork to your computer.

```git clone git@github.com:practicalli/spacemacs.d.git ~/.spacemacs.d```

If you are happy to use my Spacemacs configuration as it is, then remove your `~/.spacemacs` file and start Emacs.


## Use this configuration as an example

Clone this repository and review the configurations I have chosen, not everything may be to your preferred way of working.

The recommended approach is to use a diff tool, such as `ediff` in Emacs, `SPC D f` in Spacemacs, to compare my configuration with your own existing configuration.


## The main configuration file

The file `.spacemacs.d/init.el` is read by Spacemacs if the `.spacemacs` file does not exist.  You can used either file as your main Spacemacs configuration file (but obviously not both at the same time).  In this repository, the `.spacemacs` file is a symbolic link to `.spacemacs/init.el`.

## Getting help

Please join the [Clojurians Slack community](http://clojure.net/) and ask questions in either the `#practicalli` or `#spacemacs` channels.


Thank you

[@practical_li](https://twitter.com/practical_li)
