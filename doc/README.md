# ShoebillOS repository

## Installation

> 📄 `/etc/portage/repos.conf/shoebill.conf`
>
> ```ini
> [shoebill]
> location = /var/db/repos/shoebill
> sync-type = git
> sync-uri = https://github.com/cjwijtmans/shoebill-repo.git
> auto-sync = yes
> priority = -100
> ```

```bash
emerge --sync
```
