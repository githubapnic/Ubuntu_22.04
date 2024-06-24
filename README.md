# Ubuntu_22.04
Repo of Ubuntu 22.04 scripts

# Work in progress
This is used for converting the Ubuntu 18.04 scripts used for lab creation. Not all scripts have been converted and is a work in progress

## Installation
Download the repo and change the permissions on all the shell scripts to allow it to be run. eg:
``` bash
find Ubuntu_22.04/ -type f -iname "*.sh" -exec chmod u+x {} \;
find Ubuntu_22.04/ -type f -iname "run-dynamips" -exec chmod u+x {} \;
```
## Troubleshooting
If an error about "/bin/bash^M: bad interpeter" replace suspicious characters using the following command:
```bash
sed -i -e 's/\r$//' <filename>
```

