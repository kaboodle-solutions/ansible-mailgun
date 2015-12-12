ansible-mailgun
===============

This role configures postfix to use [Mailgun](http://mailgun.com) for outgoing
email on Linux servers.

Requirements
------------

Ansible 1.9 is strongly recommended, but Ansible 1.8 should work (unless
you're on Fedora).

Role Variables
--------------

The variables for this role are found within `defaults/main.yml` and include
the following:

* _mailgun_username_ - your Mailgun SMTP username
* _mailgun_password_ - your Mailgun SMTP password

**Please note:** This is your SMTP username/password combination, not the
credentials you use to access the Mailgun dashboard on the website. The SMTP
credentials should be different for each domain you host and they're found
here:

    https://mailgun.com/app/domains/{your-domain-name}

Dependencies
------------

This role has no dependencies.

License
-------

Apache 2.0

Author Information
------------------

[Major Hayden](http://majorhayden.com)