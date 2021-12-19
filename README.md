 <!-- Space: AnsibleRoleChrony -->
<!-- Title: Project -->

<!--


  ** DO NOT EDIT THIS FILE
  **
  ** 1) Make all changes to `provision/generator/README.yaml`
  ** 2) Run`task readme` to rebuild this file.
  **
  ** (We maintain HUNDREDS of open source projects. This is how we maintain our sanity.)
  **


  -->

[![Latest Release](https://img.shields.io/github/release/hadenlabs/ansible-role-chrony)](https://github.com/hadenlabs/ansible-role-chrony/releases) [![Lint](https://img.shields.io/github/workflow/status/hadenlabs/ansible-role-chrony/lint-code)](https://github.com/hadenlabs/ansible-role-chrony/actions?workflow=lint-code) [![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit) [![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow)](https://conventionalcommits.org)

# ansible-role-chrony

ansible-role-chrony for hadenlabs.

## Requirements

This is a list of requirements that need to be installed previously to enjoy all the goodies of this configuration:

- [gomplate](https://github.com/hairyhenderson/gomplate)
- [python](https://www.python.org)
- [taskfile](https://github.com/go-task/task)

## Usage

```bash
ansible-galaxy install hadenlabs.chrony
```

Full working examples can be found in [examples](./examples) folder.

## Examples

<!-- Space: AnsibleRoleChrony -->
<!-- Parent: Project -->
<!-- Title: Project Examples -->

<!-- Label: Examples -->
<!-- Include: docs/disclaimer.md -->
<!-- Include: ac:toc -->

### basic

To run this playbook with default settings, create a basic playbook like this:

```{.yaml}
- hosts: servers
  roles:
    - hadenlabs.chrony
```

## Requirements

## Role Variables

The default role variables in `defaults/main.yml` are:

```{.yaml}
# defaults file for ansible-role-chrony
```

## Help

**Got a question?**

File a GitHub [issue](https://github.com/hadenlabs/ansible-role-chrony/issues).

## Contributing

See [Contributing](./docs/contributing.md).

## Module Versioning

This Module follows the principles of [Semantic Versioning (SemVer)](https://semver.org/).

Using the given version number of `MAJOR.MINOR.PATCH`, we apply the following constructs:

1. Use the `MAJOR` version for incompatible changes.
1. Use the `MINOR` version when adding functionality in a backwards compatible manner.
1. Use the `PATCH` version when introducing backwards compatible bug fixes.

### Backwards compatibility in `0.0.z` and `0.y.z` version

- In the context of initial development, backwards compatibility in versions `0.0.z` is **not guaranteed** when `z` is increased. (Initial development)
- In the context of pre-release, backwards compatibility in versions `0.y.z` is **not guaranteed** when `y` is increased. (Pre-release)

## Copyright

Copyright © 2018-2021 [Hadenlabs](https://hadenlabs.com)

## Trademarks

All other trademarks referenced herein are the property of their respective owners.

## License

The code and styles are licensed under the LGPL-3.0 license [See project license.](LICENSE).

## Don't forget to 🌟 Star 🌟 the repo if you like ansible-role-chrony

[Your feedback is appreciated](https://github.com/hadenlabs/ansible-role-chrony/issues)
