# Normal1919/chatglm2-6b-int4-LIL-prefix

## 模型:THUDM/chatglm2-6b-int4: [chat_glm2](https://huggingface.co/THUDM/chatglm2-6b-int4)

* base model: chatglm2-6b-int4
* pretrained_ckpt: facebook/THUDM/chatglm2-6b-int4
* This model was trained for [rpy dl translate](https://github.com/O5-7/rpy_dl_translate)

## Model description

* source group: English
* target group: Chinese
* model: transformer
* source language(s): eng
* target language(s): cjy_Hans cjy_Hant cmn cmn_Hans cmn_Hant gan lzh lzh_Hans nan wuu yue yue_Hans yue_Hant
* fine_tune: On the basis of mbart-large-50-one-to-many-mmt checkpoints, train English original text with renpy text features (including but not limited to {i} [text] {/i}) to Chinese with the same reserved flag, as well as training for English name retention for LIL

## Fine Tuning

* 这是chatglm2-6b-int4通过P-Tuning v2微调后的PrefixEncoder部分的参数,不含有chatglm2-6b-int4本体
* This is the parameter of the PrefixEncoder section of chatglm2-6b-int4 after fine-tuning through P-Tuning v2, without the chatglm2-6b-int4 body
* Tuning脚本:[ChatGLM2-6B/ptuning](https://github.com/THUDM/ChatGLM2-6B/tree/main/ptuning)
* 此微调未经过测试,请自行测试

## How to use

* https://github.com/THUDM/ChatGLM2-6B/blob/main/ptuning/README.md

## Contact

* 517205163@qq.com
* a4564563@gmail.com