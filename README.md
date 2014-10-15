# ansible-cmake

A role for installing cmake.

[![Build Status](https://api.travis-ci.org/AlbanAndrieu/ansible-cmake.png?branch=master)](https://travis-ci.org/AlbanAndrieu/ansible-cmake)

## Actions

- Ensures that cmake is installed (using `apt`)

Usage example
------------

    - name: Install cmake
      hosts: cmake
      remote_user: root
    
      roles:
        - cmake      

Requirements
------------

none

Dependencies
------------

none

License
-------

MIT

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/AlbanAndrieu/ansible-cmake/issues)!
