Voice Guidelines
=============

<p>Designing a voice interface? Here's a useful list of lists: as many guiding principles as we could find, all in one place. List compiled and edited by Ben Sauer (<a href="https://twitter.com/bensauer">@bensauer</a>).</p>

[![Deploy with Elf](https://img.shields.io/badge/deploy-elf-green.svg?style=flat-square)](http://elf.clearleft.com)

Main voiceguidelines.clearleft.com site repository. Built in plain 'ol html.


## Running locally
The easiest way to get a local version of the site up and running is to use [Elf](http://elf.clearleft.com). Assuming you have Elf installed (and have the local Devbox server up and running) then you can follow these steps to install the site locally:

1. Clone this repository to your sites/projects directory.
2. Open terminal and `cd` into the cloned site's root directory.
3. Run `elf refresh` to inform Elf about the new site you want to add
5. Open up a browser and navigate to [http://voiceguidelines.clearleft.elf](http://voiceguidelines.clearleft.elf) to check that the site is all working correctly.

## Editing
The site is built with html and css only, and requires no build tools or processes. Changes you make to `/public/index.html` and `/public/assets/css/styles.css`, along with anything in the `/public` directory, will be reflected directly in the page, which you can see by refreshing it if you've followed the above instructions and have a local version up and running.

## Deploying
You can deploy any template or styling changes to the site by running the `elf deploy` command from the project root directory.
