# ArchipelagoMW-checksums

MD5 checksums to verify ROM file integrity for use with [Archipelago](https://github.com/ArchipelagoMW/Archipelago).

Verify with the hashing program of your choice, e.g.:

```sh
$ md5sum -c checksums.md5
ADVNTURE.bin: OK
[...]
```

Only the ROM files you intend to use need to come up with `OK`.

List the latest hashes from Archipelago with something like:

```sh
git clone 'https://github.com/ArchipelagoMW/Archipelago'
egrep -Ri '[a-f0-9]{32}' 'ArchipelagoMW/Archipelago/inno_setup.iss'
```

## Apps

Windows users who prefer a GUI can use something like [ExactFile](https://www.exactfile.com/downloads/).

Other useful Windows GUI apps include:

- [OpenHashTab](https://github.com/namazso/OpenHashTab)
- [HashCheck](https://github.com/gurnec/HashCheck)
- [GtkHash](https://github.com/gtkhash/gtkhash)
- [HashTab](https://implbits.com/hashtab) (bottom of list because it's discontinued and closed-source)
