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

    ansible-playbook mole.yml -e 'mole_state=started'

Restart
-------

    ansible-playbook mole.yml -e 'mole_state=restarted'

Stop
----

    ansible-playbook mole.yml -e 'mole_state=stopped'

Stop & Remove
-------------

    ansible-playbook mole.yml -e 'mole_state=absent'

