# Speech-to-speech
## SpeechT5 model fine-tuned for voice conversion (speech-to-speech) on CMU ARCTIC.

This model was introduced in <a href="https://arxiv.org/abs/2110.07205">SpeechT5: Unified-Modal Encoder-Decoder Pre-Training for Spoken Language Processing</a> by Junyi Ao, Rui Wang, Long Zhou, Chengyi Wang, Shuo Ren, Yu Wu, Shujie Liu, Tom Ko, Qing Li, Yu Zhang, Zhihua Wei, Yao Qian, Jinyu Li, Furu Wei.

SpeechT5 was first released in <a href="https://github.com/microsoft/SpeechT5/">this repository</a>, <a href="https://huggingface.co/mechanicalsea/speecht5-vc">original weights.</a>

Disclaimer: The team releasing SpeechT5 did not write a model card for this model so this model card has been written by the Hugging Face team.
## Model Description
Motivated by the success of T5 (Text-To-Text Transfer Transformer) in pre-trained natural language processing models, we propose a unified-modal SpeechT5 framework that explores the encoder-decoder pre-training for self-supervised speech/text representation learning. The SpeechT5 framework consists of a shared encoder-decoder network and six modal-specific (speech/text) pre/post-nets. After preprocessing the input speech/text through the pre-nets, the shared encoder-decoder network models the sequence-to-sequence transformation, and then the post-nets generate the output in the speech/text modality based on the output of the decoder.

Leveraging large-scale unlabeled speech and text data, we pre-train SpeechT5 to learn a unified-modal representation, hoping to improve the modeling capability for both speech and text. To align the textual and speech information into this unified semantic space, we propose a cross-modal vector quantization approach that randomly mixes up speech/text states with latent units as the interface between encoder and decoder.

Extensive evaluations show the superiority of the proposed SpeechT5 framework on a wide variety of spoken language processing tasks, including automatic speech recognition, speech synthesis, speech translation, voice conversion, speech enhancement, and speaker identification.

## Citation
## BibTeX:
If you find this work useful in your method, you can cite the paper as below:

    @inproceedings{ao-etal-2022-speecht5,
    title = {{S}peech{T}5: Unified-Modal Encoder-Decoder Pre-Training for Spoken Language Processing},
    author = {Ao, Junyi and Wang, Rui and Zhou, Long and Wang, Chengyi and Ren, Shuo and Wu, Yu and Liu, Shujie and Ko, Tom and Li, Qing and Zhang, Yu and Wei, Zhihua and Qian, Yao and Li, Jinyu and Wei, Furu},
    booktitle = {Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)},
    month = {May},
    year = {2022},
    pages={5723--5738},
    }
We are reaching out to kindly request your support and contribution for this project. Your assistance is crucial in helping us achieve our goals and make a positive impact on in College Project of every student in all over the world.

With your help, we can Create a more and more Projects for you all. Every contribution, no matter the size, brings us one step closer to better AI Application.


