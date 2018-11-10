# websites
[![CircleCI status](https://img.shields.io/circleci/project/github/uubk/websites/master.svg?style=shield)](https://circleci.com/gh/uubk/websites/tree/master)
![License](https://img.shields.io/github/license/uubk/websites.svg?style=popout)

Deploys static websites on the target machine. This e.g. allows for simple info pages to be shown when using the [nginx](https://github.com/SOSETH/nginx) role.

## Configuration
| Name | Default value | Description |
| ---- | ------------- | ----------- |
| `websites` | `[]` | Websites to create. See `defaults/main.yml` for how this list should be formatted. |
| `websites_owner` | `www-data` | Default owner of files and directories |
| `websites_group` | `www-data` | Default group for files and directories |
| `websites_default_mode` | `0750` | Default mode for new files |
| `websites_default_file_mode` | `0640` | Default mode for new directories |

## License
GPLv3
