Ansible Role: io500
===================

NOT READY FOR CONSUMPTION YET

This role will automatically set up io500

Planned support is for:

* Debian 9, Debian 10, Debian Testing

* Ubuntu 18.04, Ubuntu 20.04

Goals:

* Sane defaults but tunable knobs for all the things you may reasonably want to tune

Major planned features:

* Support for amd64, arm32, arm64 architectures (I run a mix of all 3 in my personal MooseFS cluster). Special added stuff for ODROID HC2 and Helios64.

* GitHub Actions CI testing of tags to make sure they're good to go before release - for every supported platform

* Changelogs that let you track exactly what changed with each new tagged release

Development of this role is driven primarily by my own needs for testing my storage systems.

New release versions of this role will be released when ready, using Semantic Versioning to keep things predictable.

I will not be changing or deleting release tags once published, so you can pin and rely on them safely.

If a critical fix is needed a new tag will be created :)

You should not rely solely on this stuff especially in production until I start publishing the 1.x.x series at least.

However, I will keep it as stable and production ready as possible.

Requirements
------------

Nothing yet.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

    NOT DOCUMENTED/IMPLEMENTED YET

Dependencies
------------

None.

Example Playbook
----------------

NOT DOCUMENTED/IMPLEMENTED YET

License
-------

MIT

Author Information
------------------

This role was created in 2020 by Benjamin Arntzen.

This role uses examples and code from [geerlingguy.awx](https://github.com/geerlingguy/ansible-role-awx) which was written by Jeff Geerling and is available under the MIT license.
