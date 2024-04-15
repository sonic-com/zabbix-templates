# zabbix-templates
Zabbix templates that might be worth sharing, especially modifications to upstream templates

Many of these are originally from [core zabbix](https://git.zabbix.com/projects/ZBX/repos/zabbix/browse/templates) or from the [Zabbix Community Templates](https://github.com/zabbix/community-templates) repository, but have local changes.

## SOC* Templates
These are system operations department templates. Many of them inherit other templates and change defaults, add triggers, add items, etc...

## VMWare* Templates
Added triggers for things so that these actually alert us about problems

## Website_certificate templates
Mostly just added some triggers so that they alert at different ages of TLS certificate.

## ZFS_on_Linux template
I forget details, but we did some local tweaks to this to make it more useful for us.
