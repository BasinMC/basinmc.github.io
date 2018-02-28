[![License](https://img.shields.io/github/license/BasinMC/basinmc.github.io.svg?style=flat-square)](https://www.apache.org/licenses/LICENSE-2.0.txt)

Basin Documentation
===================

A landing page and documentation for the Basin project's modules.

# Table of Contents

* [Building](#building)
* [Contact](#contact)
* [Issues](#issues)
* [Contributing](#contributing)
* [License](#license)

Building
--------

1. Clone this repository via ```git clone https://github.com/BasinMC/basinmc.github.io.git``` or download a [zip](https://github.com/BasinMC/basinmc.github.io/archive/master.zip)
2. Install the project dependencies by running ```bundler install```
3. Build the site by running ```PAGES_REPO_NWO=BasinMC/basinmc.github.io bundler exec jekyll build```
4. The resulting site can be found inside of the ```_site``` directory

In order to permit Jekyll to consistently fetch organization information (such
as members, projects, etc), you may also need to populate the
`JEKYLL_GITHUB_TOKEN` environment variable with a
[personal access token](https://github.com/settings/tokens/new).

Developers may also wish to invoke
`PAGES_REPO_NWO=BasinMC/basinmc.github.io bundler exec jekyll serve` instead of
the build command in order to automatically recompile any resources when their
backing files change.

Contact
-------

* [IRC #Basin on EsperNet](http://webchat.esper.net/?channels=Basin)
* [Twitter](https://twitter.com/BasinMC)
* [GitHub](https://github.com/BasinMC/basinmc.github.io)

Issues
------

You encountered problems with the library or have a suggestion? Create an issue!

1. Make sure your issue has not been fixed in a newer version (check the list of [closed issues](https://github.com/BasinMC/basinmc.github.io/issues?q=is%3Aissue+is%3Aclosed)
1. Create [a new issue](https://github.com/BasinMC/basinmc.github.io/issues/new) from the [issues page](https://github.com/BasinMC/basinmc.github.io/issues)
1. Enter your issue's title (something that summarizes your issue) and create a detailed description containing:
   - What is the expected result?
   - What problem occurs?
   - How to reproduce the problem?
   - Crash Log (Please use a [Pastebin](https://gist.github.com) service)
1. Click "Submit" and wait for further instructions

Contributing
------------

Before you add any major changes to the site you may want to discuss them with us (see
[Contact](#contact)) as we may choose to reject your changes for various reasons. All contributions
are applied via [Pull-Requests](https://help.github.com/articles/creating-a-pull-request). Patches
will not be accepted. Also be aware that all of your contributions are made available under the
terms of the [Creative Commons BY-SA](http://creativecommons.org/licenses/by-sa/4.0/), Version 4.0 License.
Please read the [Contribution Guidelines](CONTRIBUTING.md) for more information.

License
-------

This project is released under the terms of the
[Creative Commons BY-SA](http://creativecommons.org/licenses/by-sa/4.0/), Version 4.0 License.

**Note:** The Basin logo is excluded from this license declaration and remains
property of the Basin Team (see [LICENSE](assets/README.md)).
