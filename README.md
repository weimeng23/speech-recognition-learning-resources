# Speech Recognition Learning Resources

This repo contains several learning resources for speech recognition, including courses, books, tutorials, papers and toolkits.（continuously updating）

## Table of contens

- [Courses](#Courses)
- [Books](#Books)
- [Papers](#Papers)
- [Tutorials](#Tutorials)
- [Toolkits](#Toolkits)

## Courses

- (Recommended) Automatic Speech Recognition (ASR) 2018-2019 Lectures, School of Informatics, University of Edingburgh [[Website]](http://www.inf.ed.ac.uk/teaching/courses/asr/lectures-2019.html)
- Speech recognition, EECS E6870 - Spring 2016, Columbia University [[Website]](https://www.ee.columbia.edu/~stanchen/spring16/e6870/outline.html)
- CS224N: Natural Language Processing with Deep Learning, Stanford [[Website]](http://web.stanford.edu/class/cs224n/) [[Video(Winter 2021)]](https://www.youtube.com/playlist?list=PLoROMvodv4rOSH4v6133s9LFPRHjEmbmJ) [[Video(Winter 2017)]](https://www.youtube.com/watch?v=OQQ-W_63UgQ&list=PL3FW7Lu3i5Jsnh1rnUwq_TcylNr7EkRe6&index=1&t=77s)
- CS224S: Spoken Language Processing (Winter 2021), Stanford [[Website]](https://web.stanford.edu/class/cs224s/)
- DLHLP: DEEP LEARNING FOR HUMAN LANGUAGE PROCESSING, 2020 SPRING, Hung-yi Lee [[Website]](https://speech.ee.ntu.edu.tw/~hylee/dlhlp/2020-spring.php) [[Video(Spring 2020)]](https://www.youtube.com/playlist?list=PLJV_el3uVTsO07RpBYFsXg-bN5Lu0nhdG)
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

## Papers

- **HMM**: Rabiner L R. **A tutorial on hidden Markov models and selected applications in speech recognition**[J]. Proceedings of the IEEE, 1989, 77(2): 257-286. [[Paper]](https://courses.physics.illinois.edu/ece417/fa2017/rabiner89.pdf)
- **EM**: Bilmes J A. **A gentle tutorial of the EM algorithm and its application to parameter estimation for Gaussian mixture and hidden Markov models**[J]. International Computer Science Institute, 1998, 4(510): 126. [[Paper]](http://www.leap.ee.iisc.ac.in/sriram/teaching/MLSP_18/refs/GMM_Bilmes.pdf)
- **CTC**: Graves A, Fernández S, Gomez F, et al. **Connectionist temporal classification: labelling unsegmented sequence data with recurrent neural networks**[C]//Proceedings of the 23rd international conference on Machine learning. 2006: 369-376. [[Paper]](https://www.cs.toronto.edu/~graves/icml_2006.pdf)

## Tutorials

- **WFST**
  - An Introduction to Weighted Automata in Machine Learning, Awni Hannun, 2021. [[PDF]](https://awnihannun.com/writing/automata_ml/automata_in_machine_learning.pdf)
- **k2**
  - Speech Recognition with Next-Generation Kaldi (K2, Lhotse, Icefall), Interspeech 2021. [[Video]](https://www.youtube.com/watch?v=y6CJLFQlmhc)
  - Speech Recognition with Icefall + Lhotse, Interspeech 2023. [[Slides]](https://livejohnshopkins-my.sharepoint.com/:p:/g/personal/mwiesne2_jh_edu/EYqRDl8cIr5BsVDxi1MOW5EBUpdqh10WFkzqixPIFM63hg?e=u3lrmL)

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
- **espnet/espnet2** [[Github]](https://github.com/espnet/espnet)
  - Watanabe S, Hori T, Karita S, et al. [Espnet: End-to-end speech processing toolkit](https://arxiv.org/abs/1804.00015)[J]. arXiv preprint arXiv:1804.00015, 2018.
- **wenet** [[Github]](https://github.com/wenet-e2e/wenet)
  - Yao Z, Wu D, Wang X, et al. [Wenet: Production oriented streaming and non-streaming end-to-end speech recognition toolkit](https://arxiv.org/abs/2102.01547)[J]. arXiv preprint arXiv:2102.01547, 2021.
  - Zhang B, Wu D, Yao Z, et al. [Unified streaming and non-streaming two-pass end-to-end model for speech recognition](https://arxiv.org/abs/2012.05481)[J]. arXiv preprint arXiv:2012.05481, 2020.
  - Wu D, Zhang B, Yang C, et al. [U2++: Unified two-pass bidirectional end-to-end model for speech recognition](https://arxiv.org/abs/2106.05642)[J]. arXiv preprint arXiv:2106.05642, 2021.
- **NeMo** [[Github]](https://github.com/NVIDIA/NeMo) [[Doc]](https://nvidia.github.io/NeMo/)
- **Fairseq** [[Github]](<https://github.com/facebookresearch/fairseq>) [[Doc]](https://fairseq.readthedocs.io/)
  - Fairseq is a sequence modeling toolkit that allows researchers and developers to train custom models for translation, summarization, language modeling and other text generation tasks.
- **speechbrain** [[Github]](https://github.com/speechbrain/speechbrain) [[Doc]](https://speechbrain.github.io/)
  - SpeechBrain is an open-source and all-in-one conversational AI toolkit based on PyTorch.
- **paddlespeech** [[Github]](https://github.com/PaddlePaddle/PaddleSpeech) [[Doc]](https://paddlespeech.readthedocs.io/)
  - PaddleSpeech is an open-source toolkit on PaddlePaddle platform for a variety of critical tasks in speech and audio, with the state-of-art and influential models.
- **eesen** [[Github]](https://github.com/srvk/eesen)
  - Miao Y, Gowayyed M, Metze F. [EESEN: End-to-end speech recognition using deep RNN models and WFST-based decoding](https://arxiv.org/abs/1507.08240)[C]//2015 IEEE Workshop on Automatic Speech Recognition and Understanding (ASRU). IEEE, 2015: 167-174.
- **warp_ctc** [[Github]](https://github.com/baidu-research/warp-ctc)
  - A fast parallel implementation of CTC, on both CPU and GPU.
- **htk**
- **sphinx**
