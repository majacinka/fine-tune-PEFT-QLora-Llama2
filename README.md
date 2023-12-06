# Fine_tuned_Llama_PEFT_QLora

### Install necessary libraries

*Transformers* - Transformers provides APIs and tools to easily download and train state-of-the-art pretrained models

*Datasets* - Datasets is a library for easily accessing and sharing datasets for Audio, Computer Vision, and Natural Language Processing (NLP) tasks

*PEFT* - Parameter-Efficient Fine-Tuning (PEFT) methods enable efficient adaptation of pre-trained language models (PLMs) to various downstream applications without fine-tuning all the model's parameters

*trl* - a set of tools to train transformer language models. In this case the Supervised Fine-tuning step (SFT)

*accelerate* - Accelerate is a library that enables the same PyTorch code to be run across any distributed configuration by adding just four lines of code

*bitsandbytes* - Library you need to use in order to quantize the LLM