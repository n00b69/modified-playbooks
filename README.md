# modified-playbooks
Repo for modified AME playbooks for WOA Helper

The only difference is that the charging requirement has been removed.

## Why does this repo exist?
Because charging in WoA is problematic. Some devices don't support it at all, while others are very picky when it comes to the cables and chargers it actually accepts.

## Why does it say the playbook is malicious?
Because the file integrity is changed when anything is edited in the password protected playbooks, and [Ameliorated does not let you verify playbooks without donating](https://docs.ameliorated.io/developers/verification.html#verification)

If you don't trust these playbooks, you can manually download them at [AtlasosOS](https://atlasos.net/) or [ReviOS](https://revi.cc), open them (the password is `malte`), and remove the `PluggedInRequirement` line in the playbook.conf file.


























