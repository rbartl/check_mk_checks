# check_mk_checks
some check_mk_agent plugins/checks


## backuppc

check_backuppc calls backuppc_report and returns a critical error if backups
have errors or are too old.

non existant (never done) backups are ignored

## pve-zsync

added pve-zsync check - returns a critical error if sync is in error state
or too old (1 day)
