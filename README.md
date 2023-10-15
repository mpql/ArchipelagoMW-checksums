# ArchipelagoMW-checksums

MD5 checksums to verify ROM file integrity for use with [Archipelago](https://github.com/ArchipelagoMW/Archipelago).

Verify with the hashing program of your choice. Windows users who prefer a GUI can use something like [ExactFile](https://www.exactfile.com/downloads/).

List the latest hashes with something like:

```sh
git clone 'https://github.com/ArchipelagoMW/Archipelago'
egrep -Ri '[a-f0-9]{32}' 'ArchipelagoMW/Archipelago/inno_setup.iss'
```
