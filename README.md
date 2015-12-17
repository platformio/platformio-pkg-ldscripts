# platformio-pkg-ldscripts
PlatformIO LD scripts package

##How to use specific LD script?

The specific LD script can be overridden via [build_flags](http://docs.platformio.org/en/latest/projectconf.html#build-flags) option
```ini
[env:specific_ld_script]
build_flags = -Wl,-Tname_of_script.ld
```
