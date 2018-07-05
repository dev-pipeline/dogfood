dev-pipeline-dogfood
====================
`dev-pipeline`_ is a tool designed to manage projects spread across
multiple repositories, but it's not self-hosting.  This repository is
an attempt to track progress toward self-hosting dev-pipeline, even
though it seems impossible at the moment.


Goals
-----
This project should serve as a way for dev-pipeline to eat its own dog
food; even if it can't self-host, this repository can be used as a
testing ground for basic functionalty (e.g., dependency management and
source control tools), plus analytics like ordering dependencies.

As a secondary goal, this project should host bootstrap scripts, so new
developers have an easy method of setting up their environment.  If a
regular user wants to avoid the normal installation methods for some
reason, they could use that option as well.


.. _dev-pipeline: https://github.com/dev-pipeline
