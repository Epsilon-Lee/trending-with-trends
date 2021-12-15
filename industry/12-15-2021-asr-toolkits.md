
# ASR Toolkits

![image](https://user-images.githubusercontent.com/7335618/146106750-170743ad-0cc6-4ea1-a6f7-eead6bff4772.png)

Most of the toolkits are known from the paper [Performance vs. hardware requirements in state-of-the-art automatic speech recognition](https://asmp-eurasipjournals.springeropen.com/track/pdf/10.1186/s13636-021-00217-4.pdf), EURASIP Journal on Audio, Speech, and Music Processing, 2021, see the above table form the paper.

- `chainer` [EPSneet](https://espnet.github.io/espnet/), ESPnet is an end-to-end speech processing toolkit, mainly focuses on end-to-end speech recognition and end-to-end text-to-speech.
- `pytorch` [SpeechBrain](https://speechbrain.github.io/), better speech toolkit after [pytorch-kaldi](https://github.com/mravanelli/pytorch-kaldi).
- `C++` [FlashLight](https://github.com/flashlight/flashlight), Flashlight is a fast, flexible machine learning library written entirely in C++ from the Facebook AI Research Speech team and the creators of Torch and Deep Speech. Its core features include: i) just-in-time kernel compilation with modern C++ with the ArrayFire tensor library; ii) CUDA and CPU backends for GPU and CPU training; iii) an emphasis on efficiency and scale. The subproject for [asr](https://github.com/flashlight/flashlight/tree/main/flashlight/app/asr).
- `pytorch` [NeMo](https://github.com/NVIDIA/NeMo), NeMo: a toolkit for conversational AI. The suproject for [asr](https://docs.nvidia.com/deeplearning/nemo/user-guide/docs/en/main/asr/intro.html), for example, the `conformer` model.
- `PaddlePaddle` [PaddleSpeech](https://github.com/PaddlePaddle/PaddleSpeech), a Speech Toolkit based on PaddlePaddle.

