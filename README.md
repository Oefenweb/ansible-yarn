## yarn

[![CI](https://github.com/Oefenweb/ansible-yarn/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-yarn/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-yarn-blue.svg)](https://galaxy.ansible.com/Oefenweb/yarn/)

Set up (the latest version of) [Yarn](https://yarnpkg.com/) in Debian-like systems.

#### Requirements

* `software-properties-common` (will be installed)
* `dirmngr` (will be installed)
* `apt-transport-https` (will be installed)
* `wget` (will be installed)

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
    - oefenweb.yarn
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-yarn/issues)!
