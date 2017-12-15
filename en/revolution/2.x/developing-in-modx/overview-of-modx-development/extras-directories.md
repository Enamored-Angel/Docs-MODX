---
title: "Extras Directories"
_old_id: "110"
_old_uri: "2.x/developing-in-modx/overview-of-modx-development/extras-directories"
---

Extras are most commonly stored in 2 directories when they are installed:

- **core/components/** - This is the location for all the PHP and non-web-accessible files for the Extra.
- **assets/components/** - This is the location for the web-accessible files for the Extra, such as CSS, JS and images.

Why the separation? Well, since MODx users can move the core outside the webroot, separating out the non-accessible files into core/components allows MODx developers to add an extra level of security to their Extras.

See Also
--------

1. [Developer Introduction](/revolution/2.x/developing-in-modx/overview-of-modx-development/developer-introduction)
  1. [Getting Started Developing](/revolution/2.x/developing-in-modx/overview-of-modx-development/developer-introduction/getting-started-developing)
2. [Extras Directories](/revolution/2.x/developing-in-modx/overview-of-modx-development/extras-directories)
3. [Setting up a Development Environment](/revolution/2.x/developing-in-modx/overview-of-modx-development/setting-up-a-development-environment)