# Allstar

This repo contains config for the Open Source Security Foundation ([OpenSSF](https://openssf.org/)) [Allstar](https://github.com/ossf/allstar) security best practices checker.

For a list of public repos (exclusing forks and archived repos):

```
gh repo list --public --no-archived --source -L 100 atsign-foundation | awk '{print $1}' | sed s#atsign-foundation/##
```