# monitors
Save and restore your monitors settings with a CLI (gnome desktop)

If you use your laptop at different locations, with different screens,
you can use this CLI to easily save and restore your display configurations.

## Usage

```
$ ./monitors help
usage: ./monitors [cmd] [args...]

Use the following cmd:
    save <name>       save current monitors settings
    restore <name>    restore monitors settings you saved
    list              list available settings
    help              print this help
```

```
$ ./monitors list
home
client
```

```
$ ./monitors save workstation
$ ./monitors restore home
```
