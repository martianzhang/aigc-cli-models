# aigc-cli Models

Model files for [aigc-cli](https://github.com/martianzhang/aigc-cli).

## License Attribution

Each model retains its original license:

| File | Upstream Source | License | License File |
|---|---|---|---|
| `ch_PP-OCRv4_det_infer.onnx` | PaddleOCR / RapidOCR | Apache 2.0 | [licenses/Apache-2.0.txt](licenses/Apache-2.0.txt) |
| `ch_PP-OCRv4_rec_infer.onnx` | PaddleOCR / RapidOCR | Apache 2.0 | same |
| `rec_en_PP-OCRv3_infer.onnx` | PaddleOCR / RapidOCR | Apache 2.0 | same |
| `ch_ppocr_mobile_v2.0_cls_infer.onnx` | PaddleOCR | Apache 2.0 | same |
| `dict_zh.txt` | PaddleOCR | Apache 2.0 | same |
| `dict_en.txt` | RapidOCR-json | Apache 2.0 | same |
| `model-vit-base.onnx` | onnx-community | Apache 2.0 | same |
| `model-distilled-vit.onnx` | onnx-community | Apache 2.0 | same |
| `model-rmbg-2.0.onnx` | BRIA AI / RMBG 2.0 | CC BY-NC-SA 4.0 | [licenses/CC-BY-NC-SA-4.0.txt](licenses/CC-BY-NC-SA-4.0.txt) |
| `migan.onnx` | MI-GAN | MIT | [licenses/MIT.txt](licenses/MIT.txt) |

## Usage

Downloaded by `aigc-cli init` commands:

```bash
aigc-cli ocr init
aigc-cli detect init
aigc-cli background init
```

Base URL: `https://github.com/martianzhang/aigc-cli-models/releases/download/v1/`
