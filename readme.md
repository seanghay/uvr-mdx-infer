📦 Check out my new library called [Vocal](https://github.com/seanghay/vocal) for **Vocal/Speech Separation** built with simplicity in mind.

## Ultimate Vocal Remover Inference CLI

```shell
python separate.py sample_audio.wav -m UVR-MDX-NET-Inst_Main.onnx
```

## Available options

```
usage: separate.py [-h] [-o OUTPUT] [-m MODEL_PATH] [-d] [-M MARGIN] [-c CHUNKS] [-F N_FFT] [-t DIM_T] [-f DIM_F] files [files ...]

positional arguments:
  files                 Source audio path

options:
  -h, --help            show this help message and exit
  -o OUTPUT, --output OUTPUT
                        Output folder
  -m MODEL_PATH, --model_path MODEL_PATH
                        MDX Net ONNX Model path
  -d, --denoise         Enable Denoising
  -M MARGIN, --margin MARGIN
                        Margin
  -c CHUNKS, --chunks CHUNKS
                        Chunk size
  -F N_FFT, --n_fft N_FFT
  -t DIM_T, --dim_t DIM_T
  -f DIM_F, --dim_f DIM_F
```

## UVR MDX Models

[View Releases](
https://github.com/TRvlvr/model_repo/releases/tag/all_public_uvr_models)

### Recommended models

- `UVR-MDX-NET-Inst_Main.onnx`
- `UVR-MDX-NET-Inst_HQ_3.onnx`
- `UVR_MDXNET_KARA_2.onnx`
