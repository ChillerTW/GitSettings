# gfx

manual backups of my gfx configs
ideally at some point they should be auto loaded

but before that happens i rather refactor the whole config approach
a cleaner approach would disallow the teeworlds clients to ever write a config to disk
and it should only ever load a config that looks like this


```
# ~/.teeworlds/autoexec.cfg
cl_save_settings 0
exec GitSettings/base.cfg
exec GitSettings/gfx/laptop.cfg
```

