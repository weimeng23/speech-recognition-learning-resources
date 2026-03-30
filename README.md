# Speech Recognition Learning Resources

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of speech recognition learning resources, models, and toolkits. (continuously updating)

## Table of Contents

- [Courses](#courses)
- [Books](#books)
- [Models](#models)
- [Tutorials](#tutorials)
- [Toolkits](#toolkits)
- [Papers](#papers)

## Courses

- (Recommended) Automatic Speech Recognition (ASR) 2018-2019 Lectures, School of Informatics, University of Edingburgh [[Website]](http://www.inf.ed.ac.uk/teaching/courses/asr/lectures-2019.html)
- Speech recognition, EECS E6870 - Spring 2016, Columbia University [[Website]](https://www.ee.columbia.edu/~stanchen/spring16/e6870/outline.html)
- CS224N: Natural Language Processing with Deep Learning, Stanford [[Website]](http://web.stanford.edu/class/cs224n/) [[Video(Winter 2021)]](https://www.youtube.com/playlist?list=PLoROMvodv4rOSH4v6133s9LFPRHjEmbmJ) [[Video(Winter 2017)]](https://www.youtube.com/watch?v=OQQ-W_63UgQ&list=PL3FW7Lu3i5Jsnh1rnUwq_TcylNr7EkRe6&index=1&t=77s)
- CS224S: Spoken Language Processing (Winter 2021), Stanford [[Website]](https://web.stanford.edu/class/cs224s/)
- DLHLP: DEEP LEARNING FOR HUMAN LANGUAGE PROCESSING, 2020 SPRING, Hung-yi Lee [[Website]](https://speech.ee.ntu.edu.tw/~hylee/dlhlp/2020-spring.php) [[Video(Spring 2020)]](https://www.youtube.com/playlist?list=PLJV_el3uVTsO07RpBYFsXg-bN5Lu0nhdG)
- Microsoft DEV287x: Speech Recognition Systems, 2019 [[Website]](https://learning.edx.org/course/course-v1:Microsoft+DEV287x+2T2019/home)
- 语音识别从入门到精通，2019，谢磊 (NOT FREE) [[Website]](https://www.shenlanxueyuan.com/course/381)
- 數位語音處理概論，国立台湾大学，李琳山 [[Website]](http://ocw.aca.ntu.edu.tw/ntu-ocw/ocw/cou/104S204)

## Books

- **Fundamentals of speech recognition**, Lawrence Rabiner, Being-Hwang Juang, 1993 [[Book]](book/Fundamentals_of_speech_recognition_1993.pdf)
- **Spoken language processing**: A guide to theory, algorithm, and system levelopment,  xuedong Huang, Alex acero, hsiao-wuen Hon, 2001 [[Book]](book/Spoken_Language_Processing_2001.pdf)
- **Speech and Language Processing**: An Introduction to Natural Language Processing, Computational Linguistics, and Speech Recognition, Daniel Jurafsky & James H. Martin [[Website]](https://web.stanford.edu/~jurafsky/slp3/) [[Book 3rd Ed]](book/stanford_slp3.pdf)
- **Automatic speech recognition**: A Deep Learning Approach, Dong Yu and Li Deng, Springer, 2014 [[Book]](book/automatic_speech_recognition_yu2015.pdf)
- **Foundations of Statistical Natural Language Processing**, Chris Manning and Hinrich Schütze, 1999 [[Website]](https://nlp.stanford.edu/fsnlp/) [[Book]](book/foundations_Of_Natural_Language_Processing_1999.pdf)
- 《解析深度学习：语音识别实践》，俞栋，邓力，电子工业出版社
- 《Kaldi 语音识别实战》，陈果果，电子工业出版社
- 《语音识别：原理与应用》，洪青阳，电子工业出版社
- 《语音识别基本法》，汤志远，电子工业出版社
- 《统计学习方法》李航，清华大学出版社
- 《语音信号处理》韩继庆，清华大学出版社
- 《语音信号处理》赵力，机械工业出版社

## Models

### Pre-trained / Foundation Models

- **Qwen3-ASR** (2025) - Speech recognition model supporting 52 languages/dialects with streaming and non-streaming inference. Alibaba.
  [[Paper]](https://arxiv.org/abs/2601.21337) [[Code]](https://github.com/QwenLM/Qwen3-ASR)
- **Fun-ASR** (2025) - End-to-end speech recognition large model by Tongyi Lab, providing Fun-ASR-Nano and Fun-ASR-MLT-Nano. Alibaba.
  [[Paper]](https://arxiv.org/abs/2509.12508) [[Code]](https://github.com/FunAudioLLM/Fun-ASR)
- **FireRedASR** (2025) - Open-source industrial-grade Mandarin speech recognition models. Xiaohongshu.
  [[Paper]](https://arxiv.org/abs/2501.14350) [[Code]](https://github.com/FireRedTeam/FireRedASR)
- **Qwen2-Audio** (2024) - Large audio-language model supporting ASR, translation, and audio understanding. Alibaba.
  [[Paper]](https://arxiv.org/abs/2407.10759) [[Code]](https://github.com/QwenLM/Qwen2-Audio)
- **SenseVoice** (2024) - Multilingual speech recognition with emotion and audio event detection. Alibaba.
  [[Paper]](https://arxiv.org/abs/2407.04051) [[Code]](https://github.com/FunAudioLLM/SenseVoice)
- **Moonshine** (2024) - Tiny yet powerful ASR models optimized for edge devices. Useful Sensors.
  [[Paper]](https://arxiv.org/abs/2410.15608) [[Code]](https://github.com/usefulsensors/moonshine)
- **USM** (2023) - Universal Speech Model scaling ASR to 100+ languages with 12M hours of speech. Google.
  [[Paper]](https://arxiv.org/abs/2303.01037)
- **SeamlessM4T** (2023) - Massively multilingual & multimodal machine translation supporting speech and text. Meta.
  [[Paper]](https://arxiv.org/abs/2308.11596) [[Code]](https://github.com/facebookresearch/seamless_communication)
- **Whisper** (2022) - Large-scale weakly supervised speech recognition trained on 680k hours of web data. OpenAI.
  [[Paper]](https://arxiv.org/abs/2212.04356) [[Code]](https://github.com/openai/whisper)
- **WavLM** (2022) - Pre-trained model for full stack speech processing tasks. Microsoft.
  [[Paper]](https://arxiv.org/abs/2110.13900) [[Code]](https://github.com/microsoft/unilm/tree/master/wavlm)
- **HuBERT** (2021) - Self-supervised speech representation learning by masked prediction. Meta.
  [[Paper]](https://arxiv.org/abs/2106.07447) [[Code]](https://github.com/facebookresearch/fairseq/tree/main/examples/hubert)
- **wav2vec 2.0** (2020) - Self-supervised learning framework for speech representations. Meta.
  [[Paper]](https://arxiv.org/abs/2006.11477) [[Code]](https://github.com/facebookresearch/fairseq/tree/main/examples/wav2vec)
- **wav2vec** (2019) - Unsupervised pre-training for speech recognition. Meta.
  [[Paper]](https://arxiv.org/abs/1904.05862) [[Code]](https://github.com/facebookresearch/fairseq/tree/main/examples/wav2vec)

### End-to-End Models

- **Canary** (2024) - Multilingual ASR and translation model with FastConformer encoder and Transformer decoder, supporting 25 languages. NVIDIA.
  [[Code]](https://github.com/NVIDIA/NeMo)
- **FastConformer / Parakeet** (2023) - Optimized Conformer variant approximately 2.4x faster. Parakeet is a family of ASR models built on FastConformer with CTC/RNN-T/TDT decoders. NVIDIA.
  [[Paper - FastConformer]](https://arxiv.org/abs/2305.05084) [[Paper - TDT]](https://arxiv.org/abs/2304.06795) [[Code]](https://github.com/NVIDIA/NeMo)
- **Zipformer** (2023) - Efficient Conformer variant with a reweighted attention mechanism for ASR. Next-gen Kaldi.
  [[Paper]](https://arxiv.org/abs/2310.11230) [[Code]](https://github.com/k2-fsa/icefall)
- **Paraformer** (2022) - Fast and accurate non-autoregressive end-to-end speech recognition with parallel Transformer. Alibaba.
  [[Paper]](https://arxiv.org/abs/2206.08317) [[Code]](https://github.com/modelscope/FunASR)
- **E-Branchformer** (2022) - Enhanced Branchformer for speech recognition. CMU & JHU.
  [[Paper]](https://arxiv.org/abs/2210.00077) [[Code]](https://github.com/espnet/espnet)
- **Branchformer** (2022) - Parallel branch architecture combining self-attention and convolution. NTT.
  [[Paper]](https://arxiv.org/abs/2207.02971) [[Code]](https://github.com/espnet/espnet)
- **Conformer** (2020) - Convolution-augmented Transformer for speech recognition. Google.
  [[Paper]](https://arxiv.org/abs/2005.08100)
- **ContextNet** (2020) - CNN-RNN-Transducer model with global context for streaming ASR. Google.
  [[Paper]](https://arxiv.org/abs/2005.03191)
- **Transformer-Transducer** (2020) - Transformer-based model for streaming end-to-end ASR. Facebook.
  [[Paper]](https://arxiv.org/abs/2002.02562)
- **LAS / Listen, Attend and Spell** (2015) - Attention-based sequence-to-sequence model for ASR. Google.
  [[Paper]](https://arxiv.org/abs/1508.01211)
- **Deep Speech 2** (2015) - End-to-end speech recognition in English and Mandarin. Baidu.
  [[Paper]](https://arxiv.org/abs/1512.02595) [[Code]](https://github.com/PaddlePaddle/DeepSpeech)
- **Deep Speech** (2014) - Scaling up end-to-end speech recognition. Baidu.
  [[Paper]](https://arxiv.org/abs/1412.5567)
- **RNN-Transducer** (2012) - Sequence transduction with recurrent neural networks. Graves.
  [[Paper]](https://arxiv.org/abs/1211.3711)

### Traditional Models

- **DNN-HMM** (2012) - Deep neural networks for acoustic modeling in speech recognition. Hinton et al.
  [[Paper]](https://ieeexplore.ieee.org/document/6296526)
- **GMM-HMM** (2007) - The application of hidden Markov models in speech recognition. Gales & Young.
  [[Paper]](https://scholar.archive.org/work/qp3242x2ojag5jzsvw4l35zwa4/access/wayback/http://svr-www.eng.cam.ac.uk/~sjy/papers/gayo07.pdf)

## Tutorials

- **WFST**
  - An Introduction to Weighted Automata in Machine Learning, Awni Hannun, 2021. [[PDF]](https://awnihannun.com/writing/automata_ml/automata_in_machine_learning.pdf)
- **k2**
  - Speech Recognition with Next-Generation Kaldi (K2, Lhotse, Icefall), Interspeech 2021. [[Video]](https://www.youtube.com/watch?v=y6CJLFQlmhc)
  - Progress in ASR with Next-Gen Kaldi, BAAI 2022. [[Video]](https://www.youtube.com/watch?v=Q3gNj7XlArs) [[Slides]](https://docs.google.com/presentation/d/14-hKMamyLXPsmsxCl-b0mBxrOiEakSoQ/edit#slide=id.p1)
  - Speech Recognition with Icefall + Lhotse, Interspeech 2023. [[Slides]](https://livejohnshopkins-my.sharepoint.com/:p:/g/personal/mwiesne2_jh_edu/EYqRDl8cIr5BsVDxi1MOW5EBUpdqh10WFkzqixPIFM63hg?e=u3lrmL) Tutorial notebook [![Interspeech 2023 Tutorial](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1obZjUuVwks3A4oFX3gXFtPOM2LtrPQfL?usp=sharing)

## Toolkits

listed in no particular order

- **kaldi** [[Github]](https://github.com/kaldi-asr/kaldi) [[Doc]](http://kaldi-asr.org/doc/)
- **next-gen Kaldi** [[Github]](https://github.com/k2-fsa)
  - **k2**: FSA/FST algorithms, differentiable, with PyTorch compatibility. [[Github]](https://github.com/k2-fsa/k2) [[Doc]](https://k2-fsa.github.io/k2)
  - **icefall**: Speech recognition recipes using k2. [[Github]](https://github.com/k2-fsa/icefall) [[Doc]](https://k2-fsa.github.io/icefall/)
  - **sherpa**: Streaming and non-streaming ASR server for next-gen Kaldi. [[Github]](https://github.com/k2-fsa/sherpa) [[Doc]](https://k2-fsa.github.io/sherpa/)
  - **sherpa-onnx**: Real-time speech recognition using next-gen Kaldi with onnxruntime without Internet connection. Support embedded systems, Android, iOS, Raspberry Pi, x86_64 servers, websocket server/client, C/C++, Python, Kotlin, C#, Go. [[Github]](https://github.com/k2-fsa/sherpa-onnx) [[Doc]](https://k2-fsa.github.io/sherpa/onnx/index.html)
  - **sherpa-ncnn**: Real-time speech recognition using next-gen Kaldi with ncnn without Internet connection. Support iOS, Android, Raspberry Pi, VisionFive2, etc. [[Github]](https://github.com/k2-fsa/sherpa-ncnn) [[Doc]](https://k2-fsa.github.io/sherpa/ncnn/index.html)
  - **lhotse**: Tools for handling speech data in machine learning projects. [[Github]](https://github.com/lhotse-speech/lhotse) [[Doc]](https://lhotse.readthedocs.io/en/latest/)
  - **~~snowfall(deprecated)~~** [[Github]](https://github.com/k2-fsa/snowfall)
- **FunASR** [[Github]](https://github.com/modelscope/FunASR) [[Doc]](https://alibaba-damo-academy.github.io/FunASR/en/index.html)
  - A Fundamental End-to-End Speech Recognition Toolkit and Open Source SOTA Pretrained Models.
  - Gao, Z., Li, Z., Wang, J., Luo, H., Shi, X., Chen, M., ... & Zhang, S. (2023). [FunASR: A Fundamental End-to-End Speech Recognition Toolkit](https://arxiv.org/abs/2305.11013). *arXiv preprint arXiv:2305.11013*.
- **espnet/espnet2** [[Github]](https://github.com/espnet/espnet)
  - Watanabe S, Hori T, Karita S, et al. [Espnet: End-to-end speech processing toolkit](https://arxiv.org/abs/1804.00015)\[J]. arXiv preprint arXiv:1804.00015, 2018.
- **wenet** [[Github]](https://github.com/wenet-e2e/wenet)
  - Yao Z, Wu D, Wang X, et al. [Wenet: Production oriented streaming and non-streaming end-to-end speech recognition toolkit](https://arxiv.org/abs/2102.01547)\[J]. arXiv preprint arXiv:2102.01547, 2021.
  - Zhang B, Wu D, Yao Z, et al. [Unified streaming and non-streaming two-pass end-to-end model for speech recognition](https://arxiv.org/abs/2012.05481)\[J]. arXiv preprint arXiv:2012.05481, 2020.
  - Wu D, Zhang B, Yang C, et al. [U2++: Unified two-pass bidirectional end-to-end model for speech recognition](https://arxiv.org/abs/2106.05642)\[J]. arXiv preprint arXiv:2106.05642, 2021.
- **NeMo** [[Github]](https://github.com/NVIDIA/NeMo) [[Doc]](https://nvidia.github.io/NeMo/)
  - NVIDIA NeMo Framework is a generative AI framework built for researchers and pytorch developers working on large language models (LLMs), multimodal models (MM), automatic speech recognition (ASR), and text-to-speech synthesis (TTS).
- **Fairseq** [[Github]](<https://github.com/facebookresearch/fairseq>) [[Doc]](https://fairseq.readthedocs.io/)
  - Fairseq is a sequence modeling toolkit that allows researchers and developers to train custom models for translation, summarization, language modeling and other text generation tasks.
- **speechbrain** [[Github]](https://github.com/speechbrain/speechbrain) [[Doc]](https://speechbrain.github.io/)
  - SpeechBrain is an open-source and all-in-one conversational AI toolkit based on PyTorch.
- **paddlespeech** [[Github]](https://github.com/PaddlePaddle/PaddleSpeech) [[Doc]](https://paddlespeech.readthedocs.io/)
  - PaddleSpeech is an open-source toolkit on PaddlePaddle platform for a variety of critical tasks in speech and audio, with the state-of-art and influential models.
- **eesen** ***R.I.P.*** [[Github]](https://github.com/srvk/eesen)
  - Miao Y, Gowayyed M, Metze F. [EESEN: End-to-end speech recognition using deep RNN models and WFST-based decoding](https://arxiv.org/abs/1507.08240)\[C]//2015 IEEE Workshop on Automatic Speech Recognition and Understanding (ASRU). IEEE, 2015: 167-174.
- **warp_ctc** [[Github]](https://github.com/baidu-research/warp-ctc)
  - A fast parallel implementation of CTC, on both CPU and GPU.
- **htk**
- **sphinx**

## Papers

### Survey / Overview

- Prabhavalkar R, Horiguchi S, Jain A, et al. **End-to-end speech recognition: A survey**[J]. IEEE/ACM Transactions on Audio, Speech, and Language Processing, 2024. [[Paper]](https://arxiv.org/abs/2303.03329)
- Li J, Deng L, Haeb-Umbach R, et al. **Robust automatic speech recognition: A bridge to practical applications**[M]. Academic Press, 2015.

### Pre-training & Self-supervised Learning

- Chen S, Wang C, Chen Z, et al. **WavLM: Large-scale self-supervised pre-training for full stack speech processing**[J]. IEEE Journal of Selected Topics in Signal Processing, 2022. [[Paper]](https://arxiv.org/abs/2110.13900)
- Hsu W N, Bolte B, Tsai Y H, et al. **HuBERT: Self-supervised speech representation learning by masked prediction of hidden units**[J]. IEEE/ACM Transactions on Audio, Speech, and Language Processing, 2021. [[Paper]](https://arxiv.org/abs/2106.07447)
- Baevski A, Zhou Y, Mohamed A, et al. **wav2vec 2.0: A framework for self-supervised learning of speech representations**[C]//NeurIPS. 2020. [[Paper]](https://arxiv.org/abs/2006.11477)

### End-to-End ASR

- Gulati A, Qin J, Chiu C C, et al. **Conformer: Convolution-augmented transformer for speech recognition**[C]//Interspeech. 2020. [[Paper]](https://arxiv.org/abs/2005.08100)
- Chan W, Jaitly N, Le Q V, et al. **Listen, attend and spell: A neural network that learns to translate speech to text**[C]//ICASSP. 2016. [[Paper]](https://arxiv.org/abs/1508.01211)
- Amodei D, Ananthanarayanan S, Anubhai R, et al. **Deep Speech 2: End-to-end speech recognition in English and Mandarin**[C]//ICML. 2016. [[Paper]](https://arxiv.org/abs/1512.02595)
- Graves A. **Sequence transduction with recurrent neural networks**[J]. arXiv preprint arXiv:1211.3711, 2012. [[Paper]](https://arxiv.org/abs/1211.3711)
- **CTC**: Graves A, Fernández S, Gomez F, et al. **Connectionist temporal classification: labelling unsegmented sequence data with recurrent neural networks**[C]//Proceedings of the 23rd international conference on Machine learning. 2006: 369-376. [[Paper]](https://www.cs.toronto.edu/~graves/icml_2006.pdf)

### Traditional / Foundational

- **Chain/LF-MMI**: Povey D, Peddinti V, Galvez D, et al. **Purely sequence-trained neural networks for ASR based on lattice-free MMI**[C]//Interspeech. 2016: 2751-2755. [[Paper]](https://www.danielpovey.com/files/2016_interspeech_mmi.pdf)
- **TDNN**: Peddinti V, Povey D, Khudanpur S. **A time delay neural network architecture for efficient modeling of long temporal contexts**[C]//Interspeech. 2015: 3214-3218. [[Paper]](https://www.danielpovey.com/files/2015_interspeech_multisplice.pdf)
- **DNN-HMM**: Hinton G, Deng L, Yu D, et al. **Deep neural networks for acoustic modeling in speech recognition: The shared views of four research groups**[J]. IEEE Signal Processing Magazine, 2012, 29(6): 82-97. [[Paper]](https://ieeexplore.ieee.org/document/6296526)
- **EM**: Bilmes J A. **A gentle tutorial of the EM algorithm and its application to parameter estimation for Gaussian mixture and hidden Markov models**[J]. International Computer Science Institute, 1998, 4(510): 126. [[Paper]](http://www.leap.ee.iisc.ac.in/sriram/teaching/MLSP_18/refs/GMM_Bilmes.pdf)
- **HMM**: Rabiner L R. **A tutorial on hidden Markov models and selected applications in speech recognition**[J]. Proceedings of the IEEE, 1989, 77(2): 257-286. [[Paper]](https://courses.physics.illinois.edu/ece417/fa2017/rabiner89.pdf)
