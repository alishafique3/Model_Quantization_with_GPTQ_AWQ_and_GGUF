# Model Quantization with GPTQ AWQ and GGUF

- You can find many (GGUF, GPTQ, and AWQ) models curated and distributed by [TheBloke](https://huggingface.co/TheBloke), a key contributor to the open-source LLM quantization community.
- GGUF support are integrated into several popular GUIs—including Oobabooga’s text-generation-web-ui, LM Studio, and ctransformers. Notably, Oobabooga also conducted a detailed benchmark comparing different quantized models based on perplexity in an insightful [blog post](https://oobabooga.github.io/blog/posts/perplexities/).
- TinyChatEngine: On-Device LLM/VLM Inference Library by MIT Han Lab. This is enabled by LLM model compression technique: SmoothQuant and AWQ (Activation-aware Weight Quantization) [Github Repo](https://github.com/mit-han-lab/TinyChatEngine/tree/main).

| Quantization | Description | Author | Colab Notebook |
|----------------------|-------------|----------------|----------------|
| Scratch - Pytorch | Absmax, Zeropoint, and LLM.int8, benchmarking them based on perplexity and memory | Myself | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/alishafique3/Quantization-From-Scratch-Pytorch/blob/main/Quantization_From_Scratch.ipynb) |
| llama.cpp (GGUF) | Quantize Llama 2 models using GGUF and llama.cpp, [blog](https://mlabonne.github.io/blog/posts/Quantize_Llama_2_models_using_ggml.html) | Maxime Labonne | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pL8k7m04mgE5jo2NrjGi8atB0j_37aDD?usp=sharing) |
| ExLlamaV2 (GPTQ) | ExLlamaV2: The fast library to run LLMs due to new kernels by maximelabonne, [blog](https://mlabonne.github.io/blog/posts/ExLlamaV2_The_Fastest_Library_to_Run%C2%A0LLMs.html) |Maxime Labonne | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1yrq4XBlxiA0fALtMoT2dwiACVc77PHou?usp=sharing) |
| AutoGPTQ (GPTQ)       | 4-bit LLM Quantization with GPTQ, [blog](https://mlabonne.github.io/blog/posts/4_bit_Quantization_with_GPTQ.html) | Maxime Labonne | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lSvVDaRgqQp_mWK_jC9gydz6_-y6Aq4A?usp=sharing) |
| GPTQModel, AutoGPTQ (GPTQ)       | The GPTQModel and AutoGPTQ implements the GPTQ algorithm in HF transformer using GPTQConfig with ExLlamaV2 kernel support, [blog](https://huggingface.co/docs/transformers/en/quantization/gptq#gptq) | HuggingFace | |
| llm-AWQ, AutoAWQ (AWQ)       | The AutoAWQ implements the AWQ algorithm in HF transformer using AwqConfig with ExLlamaV2 kernel support. Transformers supports loading models quantized with the llm-awq and autoawq libraries. [blog](https://huggingface.co/docs/transformers/en/quantization/awq?fuse=supported+architectures#awq) | HuggingFace | |
| - (GPTQ, GGUF, BitNet)       | A Visual Guide to Quantization, [blog](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-quantization) | Maarten Grootendorst | |
| TorchAO       | PyTorch architecture optimization library with support for custom high performance data types, quantization, and sparsity., [blog](https://pytorch.org/blog/pytorch-native-architecture-optimization/) | Pytorch | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/huggingface/notebooks/blob/main/transformers_doc/en/quantization/torchao.ipynb) |


