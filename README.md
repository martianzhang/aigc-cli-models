# aigc-cli Models

Model files for [aigc-cli](https://github.com/martianzhang/aigc-cli).

## License Attribution

Each model retains its original license:

| File | Upstream Source | Source URL | License | License File |
|---|---|---|---|---|
| `ch_PP-OCRv4_det_infer.onnx` | PaddleOCR / RapidOCR | https://github.com/PaddlePaddle/PaddleOCR | Apache 2.0 | [licenses/Apache-2.0.txt](licenses/Apache-2.0.txt) |
| `ch_PP-OCRv4_rec_infer.onnx` | PaddleOCR / RapidOCR | same | Apache 2.0 | same |
| `rec_en_PP-OCRv3_infer.onnx` | PaddleOCR / RapidOCR | same | Apache 2.0 | same |
| `ch_ppocr_mobile_v2.0_cls_infer.onnx` | PaddleOCR | same | Apache 2.0 | same |
| `dict_zh.txt` | PaddleOCR | same | Apache 2.0 | same |
| `dict_en.txt` | RapidOCR-json | https://github.com/hiroi-sora/RapidOCR-json | Apache 2.0 | same |
| `model-vit-base.onnx` | onnx-community (HuggingFace) | https://huggingface.co/onnx-community | Apache 2.0 | same |
| `model-distilled-vit.onnx` | onnx-community (HuggingFace) | same | Apache 2.0 | same |
| `model-rmbg-2.0.onnx` | BRIA AI / RMBG 2.0 | https://github.com/BRIA-AI/BRIA-RMBG-2.0 | CC BY-NC-SA 4.0 | [licenses/CC-BY-NC-SA-4.0.txt](licenses/CC-BY-NC-SA-4.0.txt) |
| `migan.onnx` | MI-GAN | https://github.com/1900zyh/MI-GAN | MIT | [licenses/MIT.txt](licenses/MIT.txt) |
| `onnxruntime-osx-arm64-*.tgz` | ONNX Runtime | https://github.com/microsoft/onnxruntime/releases | MIT | same |
| `onnxruntime-linux-x64-*.tgz` | ONNX Runtime | same | MIT | same |
| `onnxruntime-win-x64-*.zip` | ONNX Runtime | same | MIT | same |
| `onnxruntime-*-gpu_cuda13-*` | ONNX Runtime | same | MIT | same |
| `sherpa-onnx-c-api.*`, `libsherpa-onnx-c-api.*` | sherpa-onnx | https://github.com/k2-fsa/sherpa-onnx | Apache 2.0 | same |
| `aigc-sherpa-helper.*`, `libaigc-sherpa-helper.*` | sherpa-onnx (built from source) | https://github.com/k2-fsa/sherpa-onnx | Apache 2.0 | same |
| `dict_en_words.txt` | FrequencyWords (hermitdave) | https://github.com/hermitdave/FrequencyWords | CC BY-SA 4.0 | [licenses/CC-BY-SA-4.0.txt](licenses/CC-BY-SA-4.0.txt) |
| `ideas.json` | aigc-cli (generated) | N/A (bundled data) | MIT | same |

## Usage

Downloaded by `aigc-cli init` commands:

```bash
aigc-cli ocr init
aigc-cli detect init
aigc-cli background init
```

Base URL: `https://github.com/martianzhang/aigc-cli-models/releases/download/v1/`
