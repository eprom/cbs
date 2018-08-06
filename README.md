# CBS Website

[![Build Status](https://travis-ci.org/eprom/cbs.svg?branch=gh-pages)](https://travis-ci.org/eprom/cbs)


## Developing locally
1. [Install Ruby](https://www.ruby-lang.org/en/documentation/installation/). 
1. `gem install bundler`
1. `bundle install`
1. `bundle exec jekyll serve`

The local site will update as changes are made.

## Contributing

One quick way to contribute is to review the [website](https://cbsrc.org) and [file issues](https://github.com/ifrcgo/cbs/website/issues) documenting the problems you see. If you would like to help fix those issues, see [the contribution guide](CONTRIBUTING.md).

## Troubleshooting

Nokogiri (鋸) is a Rubygem providing HTML, XML, SAX, and Reader parsers with XPath and CSS selector support.
Command `bundle install` tries to install `nokogiri`

If you face following error:
	`Gem::Ext::BuildError: ERROR: Failed to build gem native extension.`

You can fix it as follows:

For Ubuntu/Debian OS:
Run the command `sudo apt-get install build-essential patch ruby-dev zlib1g-dev liblzma-dev` and try again.

If you are using any other OS, you can follow the instructions mentioned here:
http://www.nokogiri.org/tutorials/installing_nokogiri.html
