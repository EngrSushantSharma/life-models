# life-models
On-device AI model files for the Life Balance app (release assets only, no code).

## Assets

| Release | File | Size (bytes) | sha256 | Base model | License |
|---|---|---|---|---|---|
| brain-v1 | life-brain-qwen-v1.gguf | 396705216 | 4e3d283ce2e0c13869c3ea1d9455633daab1d98885c9e9a584ce3f4f79318cd5 | Qwen3-0.6B | Apache-2.0 |

`brain-v1` is an interim command model (fine-tune of Qwen3-0.6B, merged, GGUF). Holdout: 84.3% capability+type, 99.6% valid JSON.

## License notes
Qwen3-0.6B is released by the Qwen team under Apache-2.0. The fine-tuned weights here are distributed under the same license. Training data is app-specific synthetic and hand-written commands.
