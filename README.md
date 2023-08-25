# Paranoid Android (a fork for vayu builds) #

```bash
repo init --depth=1 -u https://github.com/deedwar/aospa_vayu -b main
```

```bash
repo sync -c --force-sync --optimized-fetch --no-tags --prune -j$(nproc --all)
```