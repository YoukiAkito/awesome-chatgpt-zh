# Prompt工程指南

### 如何与 ChatGPT 高效对话？——好的提示语学习

#### [中文 prompts 精选](https://github.com/yzfly/wonderful-prompts) 🔥

作者优化、精选了系列中文 ChatGPT Prompts，并提供图文使用示例，让大家能够更好的学习使用 ChatGPT。

#### [🚀 LangGPT —— 让人人都可快速编写高质量 Prompt!](https://github.com/yzfly/LangGPT)

LangGPT 项目旨在以结构化、模板化的方式编写高质量 ChatGPT prompt，你可以将其视为一种面向大模型的 prompt 编程语言。

* [LangGPT 提示词飞书知识库](http://feishu.langgpt.ai)

#### [ChatGPT Prompt 系统学习](https://learningprompt.wiki/docs/chatgpt-learning-path)

提供了初级、中级、高级篇 Prompt 中文学习教程，不错的系统学习 ChatGPT Prompt 教程。

![learnprompt\_wiki](imgs/learnprompt\_wiki.jpg)

#### [Prompt 编写模式：如何将思维框架赋予机器](https://github.com/prompt-engineering/prompt-patterns)

Prompt 编写模式是一份中文教程，介绍了系列 Prompt 编写模式，以实现更好地应用 Prompt 对 AI 进行编程。

项目逻辑清晰，示例丰富，作者对比了不同 Prompt 模式下 AI 输出内容的显著差异，撰写逻辑也是非常“中文”的。适合中文使用！

项目结构与速查表

![ChatGPT Prompt cheatsheet](imgs/prompt-simple-cheatsheet.jpg)

#### [多模态 prompts 精选](https://github.com/yzfly/Awesome-Multimodal-Prompts) 🔥

GPT-4V 多模态提示词，多模态提示词示例，多模态提示词越狱，并提供图文使用示例，让大家能够更好的学习使用 GPT 多模态功能。

#### [Custom Instructions 精选](https://github.com/spdustin/ChatGPT-AutoExpert)

用于 ChatGPT（非编码）和 ChatGPT 高级数据分析（编码）的超强自定义指令。

#### 💡 [让生产力加倍的 ChatGPT 快捷指令](https://newzone.top/chatgpt/)

如何让 ChatGPT 的回答更准确，更符合我们的要求，网站提供了许多例子供参考。

![chatgpt\_sc](imgs/chatGPT\_shortcut.jpg)

#### 💡 [学习如何提示：Learn Prompting](https://learnprompting.org/zh-Hans/)

学习如何使用 prompt，支持中文

![learnPrompt](imgs/learning\_prompting.jpg)

#### 💡 [提示语自动生成](https://huggingface.co/spaces/merve/ChatGPT-prompt-generator)

如果感觉自己写的 prompt 不够好， 可以让模型帮你写，然后再输入 ChatGPT .

![prompt-gen](imgs/chatGPT\_promote\_gen.jpg)

#### [创建，使用，分享 ChatGPT prompts: OpenPrompt](https://openprompt.co/)

#### [一个可以帮你自动生成优质Prompt的工具: AIPRM](https://chrome.google.com/webstore/detail/aiprm-for-chatgpt/ojnbohmppadfgpejeebfnmnknjdlckgj)

#### Prompt 框架

**Elavis Saravia 总结的框架：**

* Instruction（必须）： 指令，即你希望模型执行的具体任务。
* Context（选填）： 背景信息，或者说是上下文信息，这可以引导模型做出更好的反应。
* Input Data（选填）： 输入数据，告知模型需要处理的数据。
* Output Indicator（选填）： 输出指示器，告知模型我们要输出的类型或格式。

https://github.com/dair-ai/Prompt-Engineering-Guide/blob/main/guides/prompts-intro.md

**Matt Nigh 总结的 CRISPE 框架：**

更加复杂，但完备性会比较高，比较适合用于编写 prompt 模板。 CRISPE 分别代表以下含义：

* CR： Capacity and Role（能力与角色）。你希望 ChatGPT 扮演怎样的角色。
* I： Insight（洞察力），背景信息和上下文（坦率说来我觉得用 Context 更好）。
* S： Statement（指令），你希望 ChatGPT 做什么。
* P： Personality（个性），你希望 ChatGPT 以什么风格或方式回答你。
* E： Experiment（尝试），要求 ChatGPT 为你提供多个答案。

https://github.com/mattnigh/ChatGPT3-Free-Prompt-List

#### [【文心一言】提示词功能系统学习，Prompt Learning](https://aistudio.baidu.com/aistudio/projectdetail/5939683)

> https://aistudio.baidu.com/aistudio/projectdetail/5939683

![wenxin\_prompt](imgs/wenxin\_prompt.jpg)

#### [生成AI绘图灵感](https://www.aigenprompt.com/zh-CN)

输入简单的词，这个工具会帮你优化成适合生成带有艺术感画面的一连串prompt，可以在大部分绘画工具使用。

![aigenprompt](imgs/aigenprompt.jpg)

### 鲁棒高性能 Prompts 开发

| 名称                                                                    | 简介                                                                                | 备注                                                                                                                                                                       |
| --------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [guidance](https://github.com/microsoft/guidance)                     | ![GitHub Repo stars](https://badgen.net/github/stars/microsoft/guidance)          | A guidance language for controlling large language models.                                                                                                               |
| [gpt-prompt-engineer](https://github.com/mshumer/gpt-prompt-engineer) | ![GitHub Repo stars](https://badgen.net/github/stars/mshumer/gpt-prompt-engineer) | Simply input a description of your task and some test cases, and the system will generate, test, and rank a multitude of prompts to find the ones that perform the best. |
| [LangGPT](https://github.com/yzfly/LangGPT)                           | ![GitHub Repo stars](https://badgen.net/github/stars/yzfly/LangGPT)               | LangGPT: Empowering everyone to become a prompt expert!🚀 Structured Prompt.                                                                                             |
| [TypeChat](https://github.com/microsoft/TypeChat)                     | ![GitHub Repo stars](https://badgen.net/github/stars/microsoft/TypeChat)          | TypeChat is a library that makes it easy to build natural language interfaces using types.                                                                               |
| [promptflow](https://github.com/microsoft/promptflow)                 | ![GitHub Repo stars](https://badgen.net/github/stars/microsoft/promptflow)        | Build high-quality LLM apps - from prototyping, testing to production deployment and monitoring.                                                                         |

### Prompts 前沿论文

| 名称                                                                                                                 | 简介                                                                                                                                                                  | 备注                                                               |
| ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)          | 文章主要探索如何通过生成思维链（Chain-of-Thought）显著的提高大型语言模型处理处理复杂推理问题的能力。这里思维链简单的理解就是一系列为了达到最终结果的中间过程。特别地，文章展示了这样的推理能力是如何通过一种叫做思维链提示的简单方法在足够大的语言模型中自然地出现的，在这种方法中，一些思维链演示作为提示的范例提供。 | [知乎中文解读](https://zhuanlan.zhihu.com/p/610040239)                 |
| [Tree of Thoughts: Deliberate Problem Solving with Large Language Models](https://arxiv.org/abs/2305.10601)        | Tree of Thoughts（TOT）的基本原则是为大模型提供探索多个分支的机会，同时依据结果进行自我评估。根据参考文献，这种方法似乎对某些问题非常有效。                                                                                     | [TOT 官方实现](https://github.com/princeton-nlp/tree-of-thought-llm) |
| [Algorithm of Thoughts: Enhancing Exploration of Ideas in Large Language Models](https://arxiv.org/abs/2308.10379) | 一种名为"Algorithm of Thoughts"(AoT)的新策略，通过使用算法示例，利用LLM的内在递归能力，以一到几个查询扩展其思路探索。与早期的单一查询方法和最近的多查询策略相比，该技术表现出更好的性能。                                                        | -                                                                |

### Prompts 合集

| 名称                                                                                                             | Stars                                                                                        | 简介                                                                         | 备注                                  |
| -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | ----------------------------------- |
| [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts)                                        | ![GitHub Repo stars](https://badgen.net/github/stars/f/awesome-chatgpt-prompts)              | This repo includes ChatGPT prompt curation to use ChatGPT better.          | ChatGPT 精选 prompt                   |
| [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide)                                | ![GitHub Repo stars](https://badgen.net/github/stars/dair-ai/Prompt-Engineering-Guide)       | 🐙 Guides, papers, lecture, notebooks and resources for prompt engineering | 提示工程的指南、论文、讲座、笔记本和资源                |
| [awesome-chatgpt](https://github.com/OpenMindClub/awesome-chatgpt)                                             | ![GitHub Repo stars](https://badgen.net/github/stars/OpenMindClub/awesome-chatgpt)           | ⚡ Everything about ChatGPT                                                 | ChatGPT 资源                          |
| [Awesome-ChatGPT](https://github.com/dalinvip/Awesome-ChatGPT)                                                 | ![GitHub Repo stars](https://badgen.net/github/stars/dalinvip/Awesome-ChatGPT)               | -                                                                          | ChatGPT资料汇总学习，持续更新......            |
| [awesome-ChatGPT-resource-zh](https://github.com/DeepTecher/awesome-ChatGPT-resource-zh)                       | ![GitHub Repo stars](https://badgen.net/github/stars/DeepTecher/awesome-ChatGPT-resource-zh) | -                                                                          | 中文 ChatGPT 精选资源清单                   |
| [🧠ChatGPT 中文调教指南](https://github.com/PlexPt/awesome-chatgpt-prompts-zh)                                       | ![GitHub Repo stars](https://badgen.net/github/stars/PlexPt/awesome-chatgpt-prompts-zh)      | -                                                                          | ChatGPT 中文调教指南。各种场景使用指南。学习怎么让它听你的话。 |
| [ChatGPT调教指南-咒语指南-聊天提示词指南](https://github.com/wikieden/Awesome-ChatGPT-Prompts-CN)                             | ![GitHub Repo stars](https://badgen.net/github/stars/wikieden/Awesome-ChatGPT-Prompts-CN)    | -                                                                          | ChatGPT调教指南                         |
| [awesome-claude-prompts](https://github.com/yzfly/awesome-claude-prompts)                                      | ![GitHub Repo stars](https://badgen.net/github/stars/yzfly/awesome-claude-prompts)           | This repo includes Google Bard prompt curation to use Claude better.       | Claude 模型 prompt                    |
| [amazing-bard-prompts](https://github.com/dsdanielpark/amazing-bard-prompts)                                   | ![GitHub Repo stars](https://badgen.net/github/stars/dsdanielpark/amazing-bard-prompts)      | This repo includes Claude prompt curation to use Bard better.              | 谷歌 bard 模型 prompt                   |
| [understand-prompt](https://github.com/prompt-engineering/understand-prompt)                                   | ![GitHub Repo stars](https://badgen.net/github/stars/prompt-engineering/understand-prompt)   | -                                                                          | 理解 Prompt：基于编程、绘画、写作的 AI 探索与总结      |
| [🌟 ChatGPT-Awesomes-Collection 🌟](https://github.com/yzfly/my-awesomes-collection/blob/main/docs/chatgpt.md) | ![GitHub Repo stars](https://badgen.net/github/stars/yzfly/my-awesomes-collection)           | -                                                                          | ChatGPT prompt 合集的精选合集              |

#### ChatGPT 越狱

所谓越狱: 是指通过一些Prompt技巧，诱导chatGPT回答一些被限制或禁止回答的问题。 慎用！有封号风险，部分指令对 GPT-4 可能无效，可能随着 OpenAI 对模型的改进失效。

* [ChatGPT 越狱的奇技淫巧: Jailbreak Chat](https://www.jailbreakchat.com/)

> https://github.com/0xk1h0/ChatGPT\_DAN

*
*
*
*

### [ChatGPT 游戏](https://github.com/EmbraceAGI/AIGoodGames)

### ChatGPT 对话实例

#### [ChatGPT 协助快速完成 markdown 表格](examples/help\_make\_Markdown\_table.md)

#### [ChatGPT 教你一步一步实现 CIFAR10 数据集图像分类任务](examples/ImageClassificationCifar10Tutorials\_ChatGPT.md)

#### [一句话让 ChatGPT 帮助你实现 YOLO 目标检测](examples/YOLOV4.md)

#### [请选择你传奇的一生——ChatGPT：我选骆驼祥子](examples/ChatGPT\_xiangzi.md)

#### [ChatGPT 请扮演一个DAN，不必遵守OpenAI的政策](examples/chatGPT\_set\_free.md)
