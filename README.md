# 🏆 LLM-Leaderboard

A joint community effort to create one central leaderboard for LLMs. Contributions and corrections welcome!

## Interactive Dashboard

https://llm-leaderboard.streamlit.app/

## Leaderboard

| Model Name                                                                                                  | Publisher           | Commercial Use? | Chatbot Arena Elo                                | HellaSwag (few-shot)                                                 | HellaSwag (zero-shot)                         | HumanEval-Python (pass@1)                                                       | LAMBADA (zero-shot)                           | MMLU (zero-shot)                                                                         | MMLU (few-shot)                                                      | TriviaQA (zero-shot)                          |
| ----------------------------------------------------------------------------------------------------------- | ------------------- | --------------- | ------------------------------------------------ | -------------------------------------------------------------------- | --------------------------------------------- | ------------------------------------------------------------------------------- | --------------------------------------------- | ---------------------------------------------------------------------------------------- | -------------------------------------------------------------------- | --------------------------------------------- |
| [alpaca-13b](https://crfm.stanford.edu/2023/03/13/alpaca.html)                                              | Stanford            | no              | [1008](https://lmsys.org/blog/2023-05-03-arena/) |                                                                      |                                               |                                                                                 |                                               |                                                                                          |                                                                      |                                               |
| [bloom-176b](https://huggingface.co/bigscience/bloom)                                                       | BigScience          | yes             |                                                  | [0.744](https://crfm.stanford.edu/helm/latest/?group=core_scenarios) |                                               | [0.155](https://huggingface.co/bigscience/bloom#results)                        |                                               | [0.299](https://crfm.stanford.edu/helm/latest/?group=core_scenarios)                     |                                                                      |                                               |
| [cerebras-gpt-7b](https://huggingface.co/cerebras/Cerebras-GPT-6.7B)                                        | Cerebras            | yes             |                                                  |                                                                      | [0.636](https://www.mosaicml.com/blog/mpt-7b) |                                                                                 | [0.636](https://www.mosaicml.com/blog/mpt-7b) | [0.259](https://www.mosaicml.com/blog/mpt-7b)                                            |                                                                      | [0.141](https://www.mosaicml.com/blog/mpt-7b) |
| [cerebras-gpt-13b](https://huggingface.co/cerebras/Cerebras-GPT-13B)                                        | Cerebras            | yes             |                                                  |                                                                      | [0.635](https://www.mosaicml.com/blog/mpt-7b) |                                                                                 | [0.635](https://www.mosaicml.com/blog/mpt-7b) | [0.258](https://www.mosaicml.com/blog/mpt-7b)                                            |                                                                      | [0.146](https://www.mosaicml.com/blog/mpt-7b) |
| [chatglm-6b](https://chatglm.cn/blog)                                                                       | ChatGLM             | yes             | [985](https://lmsys.org/blog/2023-05-03-arena/)  |                                                                      |                                               |                                                                                 |                                               |                                                                                          |                                                                      |                                               |
| [chinchilla-70b](https://arxiv.org/abs/2203.15556v1)                                                        | DeepMind            | no              |                                                  |                                                                      | [0.808](https://arxiv.org/abs/2203.15556v1)   |                                                                                 | [0.774](https://arxiv.org/abs/2203.15556v1)   |                                                                                          | [0.675](https://arxiv.org/abs/2203.15556v1)                          |                                               |
| [codex-12b / code-cushman-001](https://arxiv.org/abs/2107.03374)                                            | OpenAI              | yes             |                                                  |                                                                      |                                               | [0.317](https://crfm.stanford.edu/helm/latest/?group=targeted_evaluations)      |                                               |                                                                                          |                                                                      |                                               |
| [code-davinci-002](https://arxiv.org/abs/2207.10397v2)                                                      | OpenAI              | yes             |                                                  |                                                                      |                                               | [0.658](https://arxiv.org/abs/2207.10397v2)                                     |                                               |                                                                                          |                                                                      |                                               |
| [codegen-16B-mono](https://huggingface.co/Salesforce/codegen-16B-mono)                                      | Salesforce          | yes             |                                                  |                                                                      |                                               | [0.293](https://drive.google.com/file/d/1cN-b9GnWtHzQRoE7M7gAEyivY0kl4BYs/view) |                                               |                                                                                          |                                                                      |                                               |
| [codegen-16B-multi](https://huggingface.co/Salesforce/codegen-16B-multi)                                    | Salesforce          | yes             |                                                  |                                                                      |                                               | [0.183](https://drive.google.com/file/d/1cN-b9GnWtHzQRoE7M7gAEyivY0kl4BYs/view) |                                               |                                                                                          |                                                                      |                                               |
| [codegx-13b](http://keg.cs.tsinghua.edu.cn/codegeex/)                                                       | Tsinghua University | no              |                                                  |                                                                      |                                               | [0.229](https://drive.google.com/file/d/1cN-b9GnWtHzQRoE7M7gAEyivY0kl4BYs/view) |                                               |                                                                                          |                                                                      |                                               |
| [dolly-v2-12b](https://huggingface.co/databricks/dolly-v2-12b)                                              | Databricks          | yes             | [944](https://lmsys.org/blog/2023-05-03-arena/)  |                                                                      |                                               |                                                                                 |                                               |                                                                                          |                                                                      |                                               |
| [eleuther-pythia-7b](https://huggingface.co/EleutherAI/pythia-6.9b)                                         | EleutherAI          | yes             |                                                  |                                                                      | [0.667](https://www.mosaicml.com/blog/mpt-7b) |                                                                                 | [0.667](https://www.mosaicml.com/blog/mpt-7b) | [0.265](https://www.mosaicml.com/blog/mpt-7b)                                            |                                                                      | [0.198](https://www.mosaicml.com/blog/mpt-7b) |
| [eleuther-pythia-12b](https://huggingface.co/EleutherAI/pythia-12b)                                         | EleutherAI          | yes             |                                                  |                                                                      | [0.704](https://www.mosaicml.com/blog/mpt-7b) |                                                                                 | [0.704](https://www.mosaicml.com/blog/mpt-7b) | [0.253](https://www.mosaicml.com/blog/mpt-7b)                                            |                                                                      | [0.233](https://www.mosaicml.com/blog/mpt-7b) |
| [fastchat-t5-3b](https://huggingface.co/lmsys/fastchat-t5-3b-v1.0)                                          | lmsys.org           | yes             | [951](https://lmsys.org/blog/2023-05-03-arena/)  |                                                                      |                                               |                                                                                 |                                               |                                                                                          |                                                                      |                                               |
| [gal-120b](https://arxiv.org/abs/2211.09085v1)                                                              | lmsys.org           | no              |                                                  |                                                                      |                                               |                                                                                 |                                               | [0.526](https://paperswithcode.com/paper/galactica-a-large-language-model-for-science-1) |                                                                      |                                               |
| [gpt-3-7b / curie](https://arxiv.org/abs/2005.14165)                                                        | OpenAI              | yes             |                                                  | [0.682](https://crfm.stanford.edu/helm/latest/?group=core_scenarios) |                                               |                                                                                 |                                               |                                                                                          | [0.243](https://crfm.stanford.edu/helm/latest/?group=core_scenarios) |                                               |
| [gpt-3-175b / davinci](https://arxiv.org/abs/2005.14165)                                                    | OpenAI              | yes             |                                                  | [0.793](https://arxiv.org/abs/2005.14165)                            | [0.789](https://arxiv.org/abs/2005.14165)     |                                                                                 |                                               |                                                                                          | [0.439](https://arxiv.org/abs/2005.14165)                            |                                               |
| [gpt-3.5-175b / text-davinci-003](https://arxiv.org/abs/2303.08774v3)                                       | OpenAI              | yes             |                                                  | [0.822](https://crfm.stanford.edu/helm/latest/?group=core_scenarios) |                                               | [0.481](https://arxiv.org/abs/2303.08774v3)                                     | [0.762](https://arxiv.org/abs/2303.08774v3)   |                                                                                          | [0.569](https://crfm.stanford.edu/helm/latest/?group=core_scenarios) |                                               |
| [gpt-3.5-175b / code-davinci-002](https://platform.openai.com/docs/model-index-for-researchers)             | OpenAI              | yes             |                                                  |                                                                      |                                               | [0.463](https://crfm.stanford.edu/helm/latest/?group=targeted_evaluations)      |                                               |                                                                                          |                                                                      |                                               |
| [gpt-4](https://arxiv.org/abs/2303.08774v3)                                                                 | OpenAI              | yes             |                                                  | [0.953](https://arxiv.org/abs/2303.08774v3)                          |                                               | [0.670](https://arxiv.org/abs/2303.08774v3)                                     |                                               |                                                                                          | [0.864](https://arxiv.org/abs/2303.08774v3)                          |                                               |
| [gpt-neox-20b](https://huggingface.co/EleutherAI/gpt-neox-20b)                                              | EleutherAI          | yes             |                                                  | [0.718](https://crfm.stanford.edu/helm/latest/?group=core_scenarios) | [0.719](https://www.mosaicml.com/blog/mpt-7b) |                                                                                 | [0.719](https://www.mosaicml.com/blog/mpt-7b) | [0.269](https://www.mosaicml.com/blog/mpt-7b)                                            | [0.276](https://crfm.stanford.edu/helm/latest/?group=core_scenarios) | [0.347](https://www.mosaicml.com/blog/mpt-7b) |
| [gpt-j-6b](https://huggingface.co/EleutherAI/gpt-j-6b)                                                      | EleutherAI          | yes             |                                                  | [0.663](https://crfm.stanford.edu/helm/latest/?group=core_scenarios) | [0.683](https://www.mosaicml.com/blog/mpt-7b) |                                                                                 | [0.683](https://www.mosaicml.com/blog/mpt-7b) | [0.261](https://www.mosaicml.com/blog/mpt-7b)                                            | [0.249](https://crfm.stanford.edu/helm/latest/?group=core_scenarios) | [0.234](https://www.mosaicml.com/blog/mpt-7b) |
| [koala-13b](https://bair.berkeley.edu/blog/2023/04/03/koala/)                                               | Berkeley BAIR       | no              | [1082](https://lmsys.org/blog/2023-05-03-arena/) |                                                                      |                                               |                                                                                 |                                               |                                                                                          |                                                                      |                                               |
| [llama-7b](https://arxiv.org/abs/2302.13971)                                                                | Meta AI             | no              |                                                  |                                                                      | [0.738](https://www.mosaicml.com/blog/mpt-7b) | [0.105](https://drive.google.com/file/d/1cN-b9GnWtHzQRoE7M7gAEyivY0kl4BYs/view) | [0.738](https://www.mosaicml.com/blog/mpt-7b) | [0.302](https://www.mosaicml.com/blog/mpt-7b)                                            |                                                                      | [0.443](https://www.mosaicml.com/blog/mpt-7b) |
| [llama-13b](https://arxiv.org/abs/2302.13971)                                                               | Meta AI             | no              | [932](https://lmsys.org/blog/2023-05-03-arena/)  |                                                                      | [0.792](https://arxiv.org/abs/2302.13971)     | [0.158](https://drive.google.com/file/d/1cN-b9GnWtHzQRoE7M7gAEyivY0kl4BYs/view) |                                               |                                                                                          |                                                                      |                                               |
| [llama-33b](https://arxiv.org/abs/2302.13971)                                                               | Meta AI             | no              |                                                  |                                                                      | [0.828](https://arxiv.org/abs/2302.13971)     | [0.217](https://drive.google.com/file/d/1cN-b9GnWtHzQRoE7M7gAEyivY0kl4BYs/view) |                                               |                                                                                          |                                                                      |                                               |
| [llama-65b](https://arxiv.org/abs/2302.13971)                                                               | Meta AI             | no              |                                                  |                                                                      | [0.842](https://arxiv.org/abs/2302.13971)     | [0.237](https://drive.google.com/file/d/1cN-b9GnWtHzQRoE7M7gAEyivY0kl4BYs/view) |                                               |                                                                                          | [0.634](https://arxiv.org/abs/2302.13971v1)                          |                                               |
| [mpt-7b](https://huggingface.co/mosaicml/mpt-7b)                                                            | MosaicML            | yes             |                                                  |                                                                      | [0.761](https://www.mosaicml.com/blog/mpt-7b) |                                                                                 | [0.702](https://www.mosaicml.com/blog/mpt-7b) | [0.296](https://www.mosaicml.com/blog/mpt-7b)                                            |                                                                      | [0.343](https://www.mosaicml.com/blog/mpt-7b) |
| [oasst-pythia-12b](https://huggingface.co/OpenAssistant/pythia-12b-pre-v8-12.5k-steps)                      | Open Assistant      | yes             | [1065](https://lmsys.org/blog/2023-05-03-arena/) |                                                                      |                                               |                                                                                 |                                               |                                                                                          |                                                                      |                                               |
| [opt-7b](https://huggingface.co/facebook/opt-6.7b)                                                          | Meta AI             | no              |                                                  |                                                                      | [0.677](https://www.mosaicml.com/blog/mpt-7b) |                                                                                 | [0.677](https://www.mosaicml.com/blog/mpt-7b) | [0.251](https://www.mosaicml.com/blog/mpt-7b)                                            |                                                                      | [0.227](https://www.mosaicml.com/blog/mpt-7b) |
| [opt-13b](https://huggingface.co/facebook/opt-13b)                                                          | Meta AI             | no              |                                                  |                                                                      | [0.692](https://www.mosaicml.com/blog/mpt-7b) |                                                                                 | [0.692](https://www.mosaicml.com/blog/mpt-7b) | [0.257](https://www.mosaicml.com/blog/mpt-7b)                                            |                                                                      | [0.282](https://www.mosaicml.com/blog/mpt-7b) |
| [opt-66b](https://huggingface.co/facebook/opt-66b)                                                          | Meta AI             | no              |                                                  | [0.745](https://crfm.stanford.edu/helm/latest/?group=core_scenarios) |                                               |                                                                                 |                                               |                                                                                          | [0.276](https://crfm.stanford.edu/helm/latest/?group=core_scenarios) |                                               |
| [opt-175b](https://ai.facebook.com/blog/democratizing-access-to-large-scale-language-models-with-opt-175b/) | Meta AI             | no              |                                                  | [0.791](https://crfm.stanford.edu/helm/latest/?group=core_scenarios) |                                               |                                                                                 |                                               |                                                                                          | [0.318](https://crfm.stanford.edu/helm/latest/?group=core_scenarios) |                                               |
| [palm-540b](https://arxiv.org/abs/2204.02311v5)                                                             | Google Research     | no              |                                                  | [0.838](https://arxiv.org/abs/2204.02311v5)                          | [0.834](https://arxiv.org/abs/2204.02311v5)   | [0.262](https://drive.google.com/file/d/1cN-b9GnWtHzQRoE7M7gAEyivY0kl4BYs/view) | [0.779](https://arxiv.org/abs/2204.02311v5)   |                                                                                          | [0.693](https://arxiv.org/abs/2204.02311v5)                          |                                               |
| [replit-code-v1-3b](https://huggingface.co/replit/replit-code-v1-3b)                                        | Replit              | yes             |                                                  |                                                                      |                                               | [0.219](https://twitter.com/amasad/status/1651019556423598081/photo/2)          |                                               |                                                                                          |                                                                      |                                               |
| [stablelm-base-alpha-7b](https://huggingface.co/stabilityai/stablelm-base-alpha-7b)                         | Stability AI        | yes             |                                                  |                                                                      | [0.533](https://www.mosaicml.com/blog/mpt-7b) |                                                                                 | [0.533](https://www.mosaicml.com/blog/mpt-7b) | [0.251](https://www.mosaicml.com/blog/mpt-7b)                                            |                                                                      | [0.049](https://www.mosaicml.com/blog/mpt-7b) |
| [stablelm-tuned-alpha-7b](https://huggingface.co/stabilityai/stablelm-tuned-alpha-7b)                       | Stability AI        | no              | [858](https://lmsys.org/blog/2023-05-03-arena/)  |                                                                      |                                               |                                                                                 |                                               |                                                                                          |                                                                      |                                               |
| [starcoder-base-16b](https://huggingface.co/bigcode/starcoderbase)                                          | BigCode             | yes             |                                                  |                                                                      |                                               | [0.304](https://drive.google.com/file/d/1cN-b9GnWtHzQRoE7M7gAEyivY0kl4BYs/view) |                                               |                                                                                          |                                                                      |                                               |
| [starcoder-16b](https://huggingface.co/bigcode/starcoder)                                                   | BigCode             | yes             |                                                  |                                                                      |                                               | [0.336](https://drive.google.com/file/d/1cN-b9GnWtHzQRoE7M7gAEyivY0kl4BYs/view) |                                               |                                                                                          |                                                                      |                                               |
| [starcoder-16b (prompted)](https://huggingface.co/bigcode/starcoder)                                        | BigCode             | yes             |                                                  |                                                                      |                                               | [0.408](https://drive.google.com/file/d/1cN-b9GnWtHzQRoE7M7gAEyivY0kl4BYs/view) |                                               |                                                                                          |                                                                      |                                               |
| [vicuna-13b](https://huggingface.co/lmsys/vicuna-13b-delta-v0)                                              | lmsys.org           | no              | [1169](https://lmsys.org/blog/2023-05-03-arena/) |                                                                      |                                               |                                                                                 |                                               |                                                                                          |                                                                      |                                               |

## Benchmarks

| Benchmark Name    | Author           | Link                                     | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| ----------------- | ---------------- | ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Chatbot Arena Elo | LMSYS            | https://lmsys.org/blog/2023-05-03-arena/ | "In this blog post, we introduce Chatbot Arena, an LLM benchmark platform featuring anonymous randomized battles in a crowdsourced manner. Chatbot Arena adopts the Elo rating system, which is a widely-used rating system in chess and other competitive games." (Source: https://lmsys.org/blog/2023-05-03-arena/)                                                                                                                                                                                                                                                                 |
| HellaSwag         | Zellers et al.   | https://arxiv.org/abs/1905.07830v1       | "HellaSwag is a challenge dataset for evaluating commonsense NLI that is specially hard for state-of-the-art models, though its questions are trivial for humans (>95% accuracy)." (Source: https://paperswithcode.com/dataset/hellaswag)                                                                                                                                                                                                                                                                                                                                             |
| HumanEval         | Chen et al.      | https://arxiv.org/abs/2107.03374v2       | "It used to measure functional correctness for synthesizing programs from docstrings. It consists of 164 original programming problems, assessing language comprehension, algorithms, and simple mathematics, with some comparable to simple software interview questions." (Source: https://paperswithcode.com/dataset/humaneval)                                                                                                                                                                                                                                                    |
| LAMBADA           | Paperno et al.   | https://arxiv.org/abs/1606.06031         | "The LAMBADA evaluates the capabilities of computational models for text understanding by means of a word prediction task. LAMBADA is a collection of narrative passages sharing the characteristic that human subjects are able to guess their last word if they are exposed to the whole passage, but not if they only see the last sentence preceding the target word. To succeed on LAMBADA, computational models cannot simply rely on local context, but must be able to keep track of information in the broader discourse." (Source: https://huggingface.co/datasets/lambada) |
| MMLU              | Hendrycks et al. | https://github.com/hendrycks/test        | "The benchmark covers 57 subjects across STEM, the humanities, the social sciences, and more. It ranges in difficulty from an elementary level to an advanced professional level, and it tests both world knowledge and problem solving ability. Subjects range from traditional areas, such as mathematics and history, to more specialized areas like law and ethics. The granularity and breadth of the subjects makes the benchmark ideal for identifying a model’s blind spots." (Source: "https://paperswithcode.com/dataset/mmlu")                                             |
| TriviaQA          | Joshi et al.     | https://arxiv.org/abs/1705.03551v2       | "We present TriviaQA, a challenging reading comprehension dataset containing over 650K question-answer-evidence triples. TriviaQA includes 95K question-answer pairs authored by trivia enthusiasts and independently gathered evidence documents, six per question on average, that provide high quality distant supervision for answering the questions." (Source: https://arxiv.org/abs/1705.03551v2)                                                                                                                                                                              |

## How to Contribute

We are always happy for contributions! You can contribute by the following:

- table work (don't forget the links):
    - filling missing entries
    - adding a new model as a new row to the leaderboard. Please keep alphabetic order.
    - adding a new benchmark as a new column in the leaderboard and add the benchmark to the benchmarks table. Please keep alphabetic order.
- code work:
    - improving the existing code
    - requesting and implementing new features

## Future Ideas

- (TBD) add model year
- (TBD) add model details:
    - #params
    - #tokens seen during training
    - length context window
    - architecture type (transformer-decoder, transformer-encoder, transformer-encoder-decoder, ...)

## More Open LLMs

If you are interested in an overview about open llms for commercial use and finetuning, check out the [open-llms](https://github.com/eugeneyan/open-llms) repository.

## Sources

The results of this leaderboard are collected from the individual papers and published results of the model authors. For each reported value, the source is added as a link.

Special thanks to the following pages:
- [MosaicML - Model benchmarks](https://www.mosaicml.com/blog/mpt-7b)
- [lmsys.org - Chatbot Arena benchmarks](https://lmsys.org/blog/2023-05-03-arena/)
- [Papers With Code](https://paperswithcode.com/)
- [Stanford HELM](https://crfm.stanford.edu/helm/latest/)

## Disclaimer

Above information may be wrong. If you want to use a published model for commercial use, please contact a lawyer.