# Scoop bucket for 65816 tools and emulators

This is a bucket for the scoop command line tool installation system containing tools
that can be used in the early development of software for the Commander X16 computer
which runs a 65816 CPU. For more details on scoop, see https://scoop.sh.

To add the bucket, issue the following command:

```
scoop bucket add tools816 https://github.com/dschaefer/scoop-tools816
```

The current set of tools include:

### ACME

http://acme-crossass.sourceforge.net/

```
scoop install acme
```

ACME is a cross assembler which has support for the 65816.

### VICE

http://vice-emu.sourceforge.net/

```
scoop install vice
```

Includes ```xscpu64``` which is a Commodore 64 with the SuperCPU expansion which contains a 65816 which takes over control of the machine. It at least gets us started.
