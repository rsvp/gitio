# gitio
Custom URL shortener using Github's git.io API: command line interface, written in Bash, also keeps a local log.

```
_______________|  gitio : custom URL shortener using Github's git.io API.

         Usage:  gitio [salt]  [Github URL only, defaults to clipboard]
                 gitio [-g]    [grepterm, to search log file]
                 gitio [-v, to edit log file]

      Examples:  $ gitio  foo  https://github.com/blog/category/hire
                 https://git.io/foo

                 $ gitio     #  default salt, Github URL from clipboard.
                 https://git.io/dt_2015-03-28_170702

         Notes:  A local log file is kept; set your directory below.
                 Log file can be edited; specify editor via $VISUAL.
                 Your clipboard can be used to input and output URL;
                 thus the xclip package is needed (saves typing :-).

  Dependencies:  git.io API  (No key is required.)
                 curl
                 xclip

       API ref:  https://github.com/blog/985-git-io-github-url-shortener


CHANGE LOG  ORIGIN: https://github.com/rsvp/gitio
2015-03-28  First version 1.0.0 uses googl as template.


```


