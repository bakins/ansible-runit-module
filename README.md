Simple runit module for ansible. Works like the [monit module](http://docs.ansible.com/monit_module.html) crossed with the [service module](http://docs.ansible.com/service_module.html)

Supports "started", "stopped" and "restarted" states.

Example:

    - runit: name=myrunitservice state=started


