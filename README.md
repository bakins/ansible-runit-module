**This repository is deprecated**

See https://github.com/bakins/ansible-runit


Simple runit module for ansible. Works like the [monit module](http://docs.ansible.com/monit_module.html) crossed with the [service module](http://docs.ansible.com/service_module.html)

Supports "started", "stopped" and "restarted" states.

Example:

    - runit: name=myrunitservice state=started

So, get into ansible - probably via a role - and use.

Status
=======
I tested it a few times and it worked for me.  This was a way to get me more into ansible and also to practice my rusty python.


