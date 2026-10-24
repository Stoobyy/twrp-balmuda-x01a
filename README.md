# TWRP device tree: BALMUDA Phone X01A (KYOCERA, lito)

Device tree for building TWRP (twrp-12.1) for the Balmuda Phone X01A, generated with twrpdtgen
from the stock X01A 1.280MI.0648.a recovery image and then corrected by hand.

- Snapdragon 765 (lito), Android 12, A/B + Virtual A/B, dynamic partitions
- Boot header v2, dedicated recovery_a / recovery_b partitions
- Prebuilt kernel / dtb / dtbo from the stock recovery image
- Decryption is disabled in this first build

Build: run the "Build TWRP recovery (X01A)" workflow from the Actions tab.
Test only with `fastboot boot recovery.img` (do not flash).
