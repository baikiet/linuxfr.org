LinuxFr.org
===========

LinuxFr.org is a French-speaking website about Free software / hardware /
culture / stuff.

This git repository is the rails application that runs on LinuxFr.org.


Install
-------

See [INSTALL.md](INSTALL.md) to set up LinuxFr.org on a Debian environment.

Docker-Compose
--------------

If want to use Docker as development environment, you can run:

`$ docker-compose up --build`

When `database` and `database-test` services are ready (see logs of the
above command), you can open a second terminal and run:

`$ docker-compose run linuxfr.org bin/rails db:setup`

That will create database and seed first data.

Finally, you can access the site by opening the url: `http://localhost:3000`.

See also
--------

If you want the full stack for running LinuxFr.org, you should also look at:

* [The admin files](https://github.com/linuxfrorg/admin-linuxfr.org)
* [The migration script](https://github.com/linuxfrorg/migration-linuxfr.org)
* [The board daemon](https://github.com/linuxfrorg/board-sse-linuxfr.org)
* [The share daemon](https://github.com/linuxfrorg/share-LinuxFr.org)
* [The epub daemon](https://github.com/linuxfrorg/epub-LinuxFr.org)
* [The img daemon](https://github.com/linuxfrorg/img-LinuxFr.org)
* [SVGTeX](https://github.com/linuxfrorg/svgtex)


Copyheart
---------

The code is licensed as GNU AGPLv3. See the LICENSE file for the full license.

The [default avatar](https://linuxfr.org/images/default-avatar.svg) is a
[Tux](https://en.wikipedia.org/wiki/Tux) derived from
the [Tux Flat SVG](https://commons.wikimedia.org/wiki/File:TuxFlat.svg)
created by [gg3po](https://www.pling.com/u/gg3po/)
and [Iwan Gabovitch](http://qubodup.deviantart.com/)
under the GPL v2 or any later version.


[Feather icons](https://feathericons.com/) are licenced
[MIT](https://github.com/feathericons/feather/blob/master/LICENSE).

♡2011 by Bruno Michel. Copying is an act of love. Please copy and share.
