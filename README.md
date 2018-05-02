# SkynetAPI installer

SkynetAPI create project

```bash
skynetapi new Project
```

## Installation

Require using composer:

```bash
composer global require skynetapi/skynetapi-installer
```

Make sure to place the `$HOME/.composer/vendor/bin` directory (or the equivalent directory for your OS) in your `$PATH` so the asgardcms` executable can be located by your system.

Once installed, the `skynetapi new` command will create a fresh SkynetAPI installation in the directory you specify. For instance, `asgardcms new blog` will create a directory named `blog` containing a fresh AsgardCMS installation with all of AsgardCMS's dependencies already installed:

```bash
skynetapi new Blog
```
