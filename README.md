# YH Apple RAW 8K — browser assets

Derivative preview assets for browsing the [YH CUHKSZ Apple RAW 8K Dataset](https://huggingface.co/datasets/YarnYang/YH_CUHKSZ_Apple_RAW_8K_Dataset) (YarnYang).

Licence of source dataset: **CC BY-NC-SA 4.0** (plus no military / surveillance use). These previews inherit that licence.

- `thumbs/` — ~480px WebP grid thumbnails
- `med/` — ~2000px JPEG previews (phone JPEG, RAW neutral, RAW exposure-matched)
- `full/` — 8064×6048 JPEG (recompressed) and RAW renders (added separately)

RAW renders: rawpy, camera white balance, `no_auto_bright`, linear → 99.5th-percentile scale → γ≈2.2. Exposure-matched applies a global gain so mean brightness matches the phone JPEG (labeled separately in the viewer).
