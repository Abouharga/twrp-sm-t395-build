# TWRP build for SM-T395 (gtactive2lte)

This repo only holds a GitHub Actions workflow. It builds TWRP 9.0 from
[qcom-toolbox/TWRP_GTA2LTE](https://github.com/qcom-toolbox/TWRP_GTA2LTE/tree/android17-layout)
on the `android17-layout` branch, applying that tree's `patches/`.

Run it from the Actions tab (or push to `main`). The `twrp-gtactive2lte`
artifact holds `recovery.img` (with the `SEANDROIDENFORCE` trailer appended),
its SHA-256, and the device-tree commit it was built from.
