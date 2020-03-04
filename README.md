----
# ansible-role-app-clamav
Set up [Clam Anti Virus](https://www.clamav.net/) on Linux

## Default Variables
| Name | Type | Value | Purpose |
| ---- | ---- | ----- | ------- |
| clamav_freshclam_name   | string  | clamav-freshclam.service | name of the service |
| clamav_freshclam_onboot | string  | enabled | choice(enabled, disabled) |
| clamav_freshclam_state  | string  | started | arg to systemctl |
| clamav_pkgs             | list    | see `default/main.yml` | packages to install |
| clamav_state            | string  | present | choice(absent, present) |
| clamav_update_cache     | Boolean | true | whether to update package cache first |

## Role Dependencies
None

## Supported Distros
Ubuntu 16+ with `systemd`

## To Do
Add support for RedHat based distros
****
