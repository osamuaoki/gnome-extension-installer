# local-gnome-shell-tool

**Simple GNOME shell extension installer wrapper**

## Usage examples

Install based on `2_Vitals.conf`:

```sh
$ ./local-gnome-shell-tool 2_Vitals.conf
```

Install based on all `[1234]_*.conf`:
```sh
$ ./local-gnome-shell-tool -a
```

Install based on essential, basic, and optional `[123]_*.conf` (recommended):
```sh
$ ./local-gnome-shell-tool -3
```
or
```sh
$ ./local-gnome-shell-tool
```

Install based on essential and basic `[12]_*.conf`:
```sh
$ ./local-gnome-shell-tool -2
```

Install based on essential only `1_*.conf`:
```sh
$ ./local-gnome-shell-tool -1
```
## Note on some avoided extensions

File name `Z_*.conf` are for extensions with issues.
See their comment in these files.


