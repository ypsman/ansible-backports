ansible enable Backports
========================
[![Build Status](https://travis-ci.org/ypsman/ansible-backports.svg?branch=master)](https://travis-ci.org/ypsman/ansible-backports)

Setting up backports in apt sources for Debian wheezy/jessie/stretch/bullseye.<br>
Creates a file in /etc/apt/sources.list.d/ named backports.


Example Playbook
----------------

    - hosts: all
      roles:
        - role: ypsman.backports
