----
# ansible-role-app-clamav
Set up [Clam Anti Virus](https://www.clamav.net/) on Linux

## Default Variables
| Name | Type | Purpose |
| ---- | ---- | ------- |
| clamav_pkgs | List | ... of packages to install |
| clamav_state | string | absent or present |
| clamav_update_cache | Boolean | whether to update package cache first |

## Role Dependencies
None

## To Do
Add support for RedHat based distros

## Supported Distros
Ubuntu 16+
****
