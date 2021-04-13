# The packaging information for asynqp in Wazo

This repository contains the packaging information for
[asynqp](https://github.com/benjamin-hodgson/asynqp).

## Reason

* Not packaged by Debian
* Needed by wazo-websocketd

## Upgrading

To get a new version of asynqp in the Wazo repository, set the desired version
in the `VERSION` file and increment the changelog.

[Jenkins](http://jenkins.xivo.io) will then retrieve and build the new version.

