# ly

## Dependencies

- ly

## Usage

```
# cp -r ly /etc/runit/sv
```

```
# ln -s /etc/runit/sv/ly /etc/runit/runsvdir/default
```

```
# touch /run/runit/service/agetty-tty2/down
```

```
# sv up ly
```
