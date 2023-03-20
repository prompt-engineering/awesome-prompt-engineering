# awesome-prompts

> awesome for your to collections 

## LLMs

based on: [总结当下可用的大模型LLMs](https://zhuanlan.zhihu.com/p/611403556)

| Model | 作者 | Size | 类型 | 开源？ |
|-------|-------|-------|-------|-------|
| LLaMa | Meta AI | 7B-65B | Decoder | open |
| OPT | Meta AI | 125M-175B | Decoder | open |
| T5 | Google | 220M-11B | Encoder-Decoder | open |
| mT5 | Google | 235M-13B | Encoder-Decoder | open |
| UL2 | Google | 20B | Encoder-Decoder | open |
| PaLM | Google | 540B | Decoder | no |
| LaMDA | Google | 2B-137B | Decoder | no |
| FLAN-T5 | Google | 同T5 | Encoder-Decoder | open |
| FLAN-UL2 | Google | 同U2 | Encoder-Decoder | open |
| FLAN-PaLM | Google | 同PaLM | Decoder | no |
| FLAN | Google | 同LaMDA | Decoder | no |
| BLOOM | BigScience | 176B | Decoder | open |
| T0 | BigScience | 3B | Decoder | open |
| BLOOMZ | BigScience | 同BLOOM | Decoder | open |
| mT0 | BigScience | 同T0 | Decoder | open |
| GPT-Neo | EleutherAI | 125M-2.7B | Decoder | open |
| GPT-NeoX | EleutherAI | 20B | Decoder | open |
| GPT3 | OpenAI | 175B (davinci) | Decoder | no |
| GPT4 | OpenAI | unknown | OpenAI | no |
| InstructGPT | OpenAI | 1.3B | Decoder | no |
| Alpaca | Stanford | 同LLaMa | Decoder | open |


## Instruct/Prompt Tuning Data

based on [总结开源可用的Instruct/Prompt Tuning数据](https://zhuanlan.zhihu.com/p/615277009)

| 数据集/项目名称 | 组织/作者 | 简介 |
|-------------|-------------|-------------|
| Natural Instruction / Super-Natural Instruction | Allen AI | 包含61个NLP任务（Natural Instruction）和1600个NLP任务（Super-Natural Instruction）的指令数据 |
| PromptSource / P3 | BigScience | 包含270个NLP任务的2000多个prompt模版（PromptSource）和规模在100M-1B之间的P3数据集 |
| xMTF | BigScience | 包含13个NLP任务、46种语言的多语言prompt数据 |
| HH-RLHF | Anthropic | 旨在训练Helpful and Harmless（HH）的LLMs的RLHF数据集 |
| Unnatural Instruction | orhonovich | 使用GPT3生成64k的instruction prompt数据，经改写后得到240k条instruction数据 |
| Self-Instruct | yizhongw | 使用LLMs生成prompt进行instruct-tuning的方法，引入Task pool和Quality filtering等概念 |
| UnifiedSKG | HKU | 在Text-to-Text框架中加入knowledge grounding，将结构化数据序列化并嵌入到prompt中 |
| Flan Collection | Google | 将Flan 2021数据与一些开源的instruction数据（P3，super-natural instruction等）进行合并 |
| InstructDial | prakharguptaz | 在特定的一种任务类型（对话指令）上进行指令微调的尝试 |
| Alpaca | Stanford | 53k data, very powerful performance (GPT-3.5 level). |

## Prompter Papers

- MathPrompter: Mathematical Reasoning using Large Language Models 
