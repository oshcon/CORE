# CORE

[![Build Status](http://ci.nodemc.space/buildStatus/icon?job=NodeMC)](http://nodemc.space:8080/job/NodeMC/) [![Gitter](https://img.shields.io/badge/slack-community-brightgreen.svg)](https://nodemc.space/slack/)

- [Node.js](https://nodejs.org/en/) >= 5.7.0

- [npm](https://www.npmjs.com/) >= 3.6.0

- [Java JRE](https://www.java.com/en/) >= 1.7.0

### (Optional) Building Requirements

- [nexe](https://jaredallard.me/nexe/) >= 1.1.0
    - Linux / Mac / BSD / Windows
    - Python 2.6 or 2.7 (use --python if not in PATH)
    - Windows: Visual Studio 2010+

## Running

Running NodeMC is easy.

```
git clone https://github.com/NodeMC/CORE.git NodeMC/

cd NodeMC/

npm install

node server.js
```

Then navigate to http://localhost:3000 and go through the setup processs.
npm >= 3.6.0

Java JRE >= 1.7.0

(Optional) Building Requirementsnpm >= 3.6.0

Java JRE >= 1.7.0

(Optional) Building Requirements
## Contributing

### Wall of Fame

[Mathew Da Costa](https://github.com/md678685) for his incredible work on the plugin system
and for his continued support of NodeMC. :thumbsup:

[Jared Allard](https://github.com/jaredallard) for his immense contributions of rewriting NodeMC
using ES6 sepcifications. :heart:

I welcome contributions from other developers, however there are a few
things you should keep in mind when making a pull request.

First things first, pull requests will never be accepted to the master branch
unless there is an important security or performance patch. Otherwise, they will be
merged to whichever is the newest upcoming version of NodeMC (v7).

Second, if you are considering a major rewrite of a particular component of NodeMC,
be sure to run it by me in the Gitter (@gmemstr) so I can be aware of your proposed changes.

Third, please make sure you follow the `.eslintrc` so that your code style is the same. Pull requests that do *not* pass
the test to check this will *NOT* be accepted.

Lastly, please try to use a node.js org commit style; `component: changes`. i.e `readme: update with new rules`.

## Building

TL;DR - If you modify NodeMC, you need to mark your code and/or binary as such.

> For the developers' and authors' protection, the GPL clearly explains
that there is no warranty for this free software.  For both users' and
authors' sake, the GPL requires that modified versions be marked as
changed, so that their problems will not be attributed erroneously to
authors of previous versions.

I use [nexe](https://github.com/jaredallard/nexe) for the builds of NodeMC. I recommend it - version 2.0.0
should be available around the time of this branch being merged upstream.

## Credits

Various OSS modules are used in this project, please check `package.json` for the extended list of them.

## License

GNU GPL3
