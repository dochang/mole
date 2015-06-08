MOLE
====

Let's tunnel!

Requirements
------------

Mole will install docker-py by pip.

Set up
------

Write your own `~/.config/mole/` based on `config.sample/`.

Run
---

    ansible-playbook local.yml -e 'mole_state=running'

Restart
-------

    ansible-playbook local.yml -e 'mole_state=restarted'

Stop
----

    ansible-playbook local.yml -e 'mole_state=stopped'

Stop & Remove
-------------

    ansible-playbook local.yml -e 'mole_state=absent'

