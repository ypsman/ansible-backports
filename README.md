ansible enable Backports
========================
[![Build Status](https://travis-ci.org/ypsman/ansible-backports.svg?branch=master)](https://travis-ci.org/ypsman/ansible-backports)

Setting up backports in apt sources for Debian wheezy/jessie.


Example Playbook
----------------

    - hosts: all
      roles:
        - role: ypsman.backports
