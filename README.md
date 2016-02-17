MOLE
====

[![Issue Stats](http://issuestats.com/github/dochang/mole/badge/pr)](http://www.issuestats.com/github/dochang/mole)
[![Issue Stats](http://issuestats.com/github/dochang/mole/badge/issue)](http://www.issuestats.com/github/dochang/mole)

Let's tunnel!

Requirements
------------

Mole will install docker-py by pip.

Set up
------

Write your own `~/.config/mole/` based on `config.sample/`.

Run
---

    ansible-playbook -i localhost, mole.yml -e 'mole_state=started'

Restart
-------

    ansible-playbook -i localhost, mole.yml -e 'mole_state=restarted'

Stop
----

    ansible-playbook -i localhost, mole.yml -e 'mole_state=stopped'

Stop & Remove
-------------

    ansible-playbook -i localhost, mole.yml -e 'mole_state=absent'

License
-------

[MIT](http://dochang.mit-license.org/)

