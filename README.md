# Paranoid Android (a fork for realme GT master edition builds) #

```bash
repo init --depth=1 -u https://github.com/aospa-lunaa/manifest -b topaz
```

```bash
repo sync -c --force-sync --optimized-fetch --no-tags --prune -j$(nproc --all)
```