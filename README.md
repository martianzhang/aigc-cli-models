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
| `vision_base-int8_vision_encoder.onnx` | Florence-2 (Microsoft) | https://huggingface.co/microsoft/Florence-2-base-ft | MIT | [licenses/MIT.txt](licenses/MIT.txt) |
| `vision_base-int8_encoder_model.onnx` | Florence-2 (Microsoft) | same | MIT | same |
| `vision_base-int8_decoder_model.onnx` | Florence-2 (Microsoft) | same | MIT | same |
| `vision_base-int8_embed_tokens.onnx` | Florence-2 (Microsoft) | same | MIT | same |
| `vision_base-int8_vocab.json` | Florence-2 (Microsoft) | same | MIT | same |
| `vision_base-int8_merges.txt` | Florence-2 (Microsoft) | same | MIT | same |
| `e5-small-multilingual-model.onnx` | Xenova / intfloat (HuggingFace) | https://huggingface.co/Xenova/multilingual-e5-small | MIT | same |
| `e5-small-multilingual-tokenizer.json` | Xenova / intfloat (HuggingFace) | same | MIT | same |
| `depth-anything-v2-small.onnx` | Depth Anything V2 (LiheYoung / DepthAnything) | https://huggingface.co/onnx-community/depth-anything-v2-small | Apache 2.0 | same |
| `depth-anything-v2-base.onnx` | Depth Anything V2 (LiheYoung / DepthAnything) | https://huggingface.co/onnx-community/depth-anything-v2-base | CC-BY-NC-4.0 | [licenses/CC-BY-NC-4.0.txt](licenses/CC-BY-NC-4.0.txt) |
| `depth-anything-v2-large.onnx` | Depth Anything V2 (LiheYoung / DepthAnything) | https://huggingface.co/onnx-community/depth-anything-v2-large | CC-BY-NC-4.0 | same |
| `upscale-realesr-general-x4v3.onnx` | Real-ESRGAN (xinntao) | https://github.com/xinntao/Real-ESRGAN | BSD-3-Clause | [licenses/BSD-3-Clause.txt](licenses/BSD-3-Clause.txt) |
| `upscale-real-esrgan-x4plus.onnx` | Real-ESRGAN (xinntao) | same | BSD-3-Clause | same |
| `upscale-real-esrgan-x4plus-anime-6b.onnx` | Real-ESRGAN (xinntao) | same | BSD-3-Clause | same |
| `upscale-real-esrgan-animevideov3.onnx` | Real-ESRGAN (xinntao) | same | BSD-3-Clause | same |
| `upscale-real-cugan-2x.onnx` | Real-CUGAN (bilibili) | https://github.com/bilibili/ailab/tree/main/Real-CUGAN | MIT | [licenses/MIT.txt](licenses/MIT.txt) |
| `upscale-swin2sr-lightweight-x2.onnx` | Swin2SR (mv-lab) | https://github.com/mv-lab/swin2sr | Apache 2.0 | [licenses/Apache-2.0.txt](licenses/Apache-2.0.txt) |
| `upscale-swin2sr-realworld-x4.onnx` | Swin2SR (mv-lab) | same | Apache 2.0 | same |
| `upscale-real-esrgan-x4plus-anime-4b32f.onnx` | Real-ESRGAN (xinntao) | same | BSD-3-Clause | same |
| `upscale-swin2sr-classical-x4.onnx` | Swin2SR (mv-lab) | same | Apache 2.0 | same |
| `upscale-swin2sr-compressed-x4.onnx` | Swin2SR (mv-lab) | same | Apache 2.0 | same |
| `yolov8n-pose.onnx` | Xenova / Ultralytics YOLOv8 (HuggingFace) | https://huggingface.co/Xenova/yolov8-pose-onnx | AGPL-3.0 | [licenses/AGPL-3.0.txt](licenses/AGPL-3.0.txt) |
| `facefinder` | esimov/pigo (pure-Go face detection) | https://github.com/esimov/pigo | MIT | [licenses/MIT.txt](licenses/MIT.txt) |
| `puploc` | esimov/pigo (pupil localization) | same | MIT | same |
| `lps/lp38`, `lps/lp42`, `lps/lp44`, `lps/lp46` | esimov/pigo (eye landmarks) | same | MIT | same |
| `lps/lp312` | esimov/pigo (eye landmark) | same | MIT | same |
| `lps/lp81`, `lps/lp82`, `lps/lp84`, `lps/lp93` | esimov/pigo (mouth/nose landmarks) | same | MIT | same |

## Usage

Downloaded by `aigc-cli init` commands:

```bash
aigc-cli ocr init
aigc-cli detect init
aigc-cli background init
aigc-cli kb init            # downloads e5-small-multilingual
aigc-cli video init         # downloads depth-anything-v2-small (default; --all for base/large)
aigc-cli depth init         # downloads depth-anything-v2-small (default)
aigc-cli depth init --skeleton  # downloads yolov8n-pose.onnx
aigc-cli depth init --face      # downloads pigo cascades (facefinder/puploc/lps/*)
aigc-cli upscale init           # downloads the default super-resolution model (Real-ESRGAN x4v3)
aigc-cli upscale init --model real-cugan-2x   # or a specific upscale model
```

Base URL: `https://github.com/martianzhang/aigc-cli-models/releases/download/v1/`
