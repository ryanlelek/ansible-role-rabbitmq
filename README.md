RabbitMQ
========

Installs and configures RabbitMQ

Requirements
------------

None

Role Variables
--------------

- **rabbitmq_vhost**:    main
- **rabbitmq_username**: bunny
- **rabbitmq_password**: amqp

Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      become: yes
      roles:
        - role: ryanlelek.rabbitmq
          rabbitmq_vhost: myproject
          rabbitmq_username: myuser
          rabbitmq_password: itsasecret

License
-------

MIT

Author Information
------------------

Created by [Ryan Lelek](https://www.ryanlelek.com)  
Part of [AnsibleTutorials.com](http://www.ansibletutorials.com)
