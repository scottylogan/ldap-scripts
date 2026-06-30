# LDAP Scripts

## `mkpwdldif` _cn_ _[password]_

Generate the LDIF to change the AD password for the user identified by _cn_. If _password_ isn't sepcificied one is prompted for.

## `su-ldap`

Wrapper around an LDAP search for Stanford University.
Copy / symlink `su-ldap` to make shortcuts for specific trees:

* `accounts` - search the Stanford Accounts tree
* `ldapgroups` - search the Stanford Groups tree
* `people` - search the Stanford People tree

Usage: `script` _searchfilter_ _[attrs]_

