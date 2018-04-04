## yarn

[![Build Status](https://travis-ci.org/Oefenweb/ansible-yarn.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-yarn) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-yarn-blue.svg)](https://galaxy.ansible.com/Oefenweb/yarn/)

Set up (the latest version of) [Yarn](https://yarnpkg.com/) in Debian-like systems.

#### Requirements

* `apt-transport-https` (will be installed)

#### Variables

None

## Dependencies

None

## Recommended

* `ansible-nodejs` ([see](https://github.com/Oefenweb/ansible-nodejs))

#### Example

```yaml
---
- hosts: all
  roles:
    - Oefenweb.yarn
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-yarn/issues)!
