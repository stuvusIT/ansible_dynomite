# dynomite
This is an Ansible role which sets up a dynomite node

## Requirements

Debian or Ubuntu with a running redis server.

## Role Variables

| Name               | Required/Default   | Description             |
|:-------------------|:------------------:|:------------------------|
| `dynomite_config`  | :heavy_check_mark: | Dynomite config as yaml |
| `dynomite_version` | `v0.6.14`          | Dynomite version        |

## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).


## Author Information

 * [Fritz Otlinghaus (Scriptkiddi)](https://github.com/Scriptkiddi) _fritz.otlinghaus@stuvus.uni-stuttgart.de_
