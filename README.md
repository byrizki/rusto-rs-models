# RustO! Models

Pre-converted MNN model files for [rusto-rs](https://github.com/byrizki/rusto-rs) — the Pure Rust OCR library.

## Usage

Models are automatically downloaded by `scripts/download_models.sh` in the main repository.
You can also download them manually from the [Releases](https://github.com/byrizki/rusto-rs-models/releases) page.

## Release Naming Convention

Files are named: `ppocrv6_<component>_<tier>.mnn`

| File | Description | Size |
|------|-------------|------|
| `ppocrv6_det_tiny.mnn` | PP-OCRv6 Detection (Tiny) | ~1.7 MB |
| `ppocrv6_rec_tiny.mnn` | PP-OCRv6 Recognition (Tiny) | ~4.3 MB |
| `ppocrv6_tiny_dict.txt` | PP-OCRv6 Character Dictionary (Tiny) | ~27 KB |
| `ppocrv6_det_small.mnn` | PP-OCRv6 Detection (Small) | ~9.4 MB |
| `ppocrv6_rec_small.mnn` | PP-OCRv6 Recognition (Small) | ~21 MB |
| `ppocrv6_dict.txt` | PP-OCRv6 Character Dictionary (Small/Medium) | ~75 KB |
| `ppocrv6_det_medium.mnn` | PP-OCRv6 Detection (Medium) | ~60 MB |
| `ppocrv6_rec_medium.mnn` | PP-OCRv6 Recognition (Medium) | ~74 MB |

## Model Sources

- **PP-OCRv6** — [ModelScope RapidAI/RapidOCR](https://www.modelscope.cn/models/RapidAI/RapidOCR/tree/master/mnn/PP-OCRv6)
- Original: [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)

## License

Models are derived from PaddleOCR and are subject to the [Apache 2.0 License](https://github.com/PaddlePaddle/PaddleOCR/blob/main/LICENSE).
