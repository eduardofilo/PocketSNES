## Compiling instructions

For stock firmware with stock toolchain:

```bash
cd PocketSNES
make HUGE_PAGES=0
make HUGE_PAGES=0 opk
```

For ODbeta firmware with ODbeta toolchain:

```bash
cd PocketSNES
make HUGE_PAGES=1
make HUGE_PAGES=1 opk
```

The compiled binary appears in the `dist` directory and the OPK in `opk`. The OPKs that appear are:

* `PocketSNES.opk`: For stock
* `PocketSNES_new.opk`: For ODbeta
