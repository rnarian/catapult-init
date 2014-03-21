# catapult-init

Init script for [catapult](https://github.com/rnarian/catapult). 

It pulls the latest version from github, removes the `.git` directory and adjusts `package.json`, `bower.json`, `index.html` and `style.scss` based on some user inputs.

## Installation

Clone this repo and move the script somewhere in your path, e.g. `/usr/local/bin`:

    $ git clone https://github.com/rnarian/catapult-init.git
    $ mv catapult-init/catapult /usr/local/bin/
    $ chmod +x /usr/local/bin/catapult

And restart your shell afterwards.

## Usage

### Initialize new project:

    $ catapult init

### Retrieve current version:

    $ catapult version

### Update project version:

    $ catapult versionbump
