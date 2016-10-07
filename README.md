wrboyce.flux
============

[![Build Status](https://travis-ci.org/wrboyce/ansible-flux.svg)](https://travis-ci.org/wrboyce/ansible-flux)

Install and Configure Flux.app

Requirements
------------

* [Homebrew](http://brew.sh)

Role Variables
--------------

| variable | description |
|---|---|
| flux_night_colour | screen temperature at night |
| flux_late_colour | screen temperature when late |
| flux_wake_time | time you wake up expressed as minutes after midnight |

Example Playbook
----------------

    - hosts: macos-workstations
      roles:
         - wrboyce.flux

License
-------

Apache 2.0
