# photoapp-models

Model weights for PhotoApp, hosted as Release assets so the app can download them on first run. This repository contains no application code.

## BiRefNet-general-epoch_244-fp16.onnx

- fp16 conversion of `BiRefNet-general-epoch_244.onnx` from [ZhengPeng7/BiRefNet](https://github.com/ZhengPeng7/BiRefNet), release `v1`.
- Converted with onnxconverter-common `convert_float_to_float16`, `keep_io_types=True`, `op_block_list=[]`.
- 489,657,967 bytes. Inputs and outputs remain float32; weights are float16. Model resolution 1024x1024.

Upstream model Copyright (c) 2024 ZhengPeng, MIT License. The conversion is distributed under the same MIT terms — see [LICENSE](LICENSE).
