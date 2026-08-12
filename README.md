# RustO! Models

Pre-converted MNN model files for [rusto-rs](https://github.com/byrizki/rusto-rs) — the Pure Rust OCR library.

## Usage

Models are automatically downloaded by `scripts/download_models.sh` in the main repository.
You can also download them manually from the [Releases](https://github.com/byrizki/rusto-rs-models/releases) page.

## Available Models

### PP-OCRv6 (Default & Recommended)

MetaFormer-based PPLCNetV4 architecture with unified 50-language dictionary.

| File | Size | Description |
|------|------|-------------|
| `ppocrv6_det_tiny.mnn` | ~1.7 MB | Detection — Tiny ⭐ prebundled default |
| `ppocrv6_rec_tiny.mnn` | ~4.3 MB | Recognition — Tiny ⭐ prebundled default |
| `ppocrv6_tiny_dict.txt` | ~27 KB | Dictionary for Tiny models |
| `ppocrv6_det_small.mnn` | ~9.4 MB | Detection — Small |
| `ppocrv6_rec_small.mnn` | ~21 MB | Recognition — Small |
| `ppocrv6_dict.txt` | ~75 KB | Dictionary for Small/Medium models |
| `ppocrv6_det_medium.mnn` | ~60 MB | Detection — Medium |
| `ppocrv6_rec_medium.mnn` | ~74 MB | Recognition — Medium |

### PP-OCRv5

SVTR-LCNet-based recognition. Mobile (4–16 MB) models for Chinese and English.

| File | Size | Description |
|------|------|-------------|
| `ppocrv5_det_mobile.mnn` | ~4.6 MB | Detection — Mobile (Chinese) |
| `ppocrv5_rec_ch_mobile.mnn` | ~16 MB | Recognition — Mobile (Chinese+English) |
| `ppocrv5_rec_en_mobile.mnn` | ~7.5 MB | Recognition — Mobile (English only) |
| `ppocrv5_ch_dict.txt` | ~73 KB | Dictionary for Chinese recognition |
| `ppocrv5_en_dict.txt` | ~1.4 KB | Dictionary for English recognition |

### PP-OCRv4

Lightweight mobile OCR. Includes text orientation classifier.

| File | Size | Description |
|------|------|-------------|
| `ppocrv4_det_mobile.mnn` | ~4.6 MB | Detection — Mobile (Chinese) |
| `ppocrv4_rec_ch_mobile.mnn` | ~10.5 MB | Recognition — Mobile (Chinese+English) |
| `ppocrv4_rec_en_mobile.mnn` | ~7.3 MB | Recognition — Mobile (English only) |
| `ppocrv4_cls_mobile.mnn` | ~519 KB | Text orientation classifier |
| `ppocrv4_ch_dict.txt` | ~26 KB | Dictionary for Chinese recognition |
| `ppocrv4_en_dict.txt` | ~190 B | Dictionary for English recognition |

## Quick Download (default PP-OCRv6 tiny)

```bash
bash <(curl -sSL https://raw.githubusercontent.com/byrizki/rusto-rs/main/scripts/download_models.sh)
```

## Model Sources

- [ModelScope RapidAI/RapidOCR](https://www.modelscope.cn/models/RapidAI/RapidOCR)
- [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) (Apache 2.0)
