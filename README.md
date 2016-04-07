# Ansible Role Cloudflare

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/hadenlabs/ansible-role-cloudflare.svg)](https://travis-ci.org/hadenlabs/ansible-role-cloudflare)
[![Stories in Ready](https://badge.waffle.io/hadenlabs/ansible-role-cloudflare.svg?label=ready&title=Ready)](http://waffle.io/hadenlabs/ansible-role-cloudflare)
[![GitHub issues](https://img.shields.io/github/issues/hadenlabs/ansible-role-cloudflare.svg)](https://github.com/hadenlabs/ansible-role-cloudflare/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


Installs and configures [cloudflare][link-cloudflare] on a host.

## Requirements

 - Linux
   - none
 - OSX
   - none


## Role Variables

The default role variables in `defaults/main.yml` are:

    ---
    # defaults file for cloudflare


## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

    - hosts: servers
      roles:
         - cloudflare

To install a specific version:

    - hosts: servers
      roles:
         - { role: hadenlabs.cloudflare }


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [Luis Mayta][link-luis]
- [All Contributors][link-contributors]


<!-- Other -->

[link-cloudflare]: https://www.cloudflare.com
[link-luis]: https://github.com/luismayta
[link-contributors]: contributors
