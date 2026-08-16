# Saudade-dataset

用于微调中文大模型，使其更贴合情感陪伴场景的训练数据

## 这是个啥

这是一个为中文大模型设计的微调数据集，目标是让模型学会更自然、温暖、有陪伴感的回应方式。**所有数据都由作者本人编写，不存在AI生成的数据。其中部分数据灵感来源于作者的亲身经历。**

数据风格：

- 避免对话聊天时的“人机味”，让对话像真人一样
- 提升共情和陪伴能力
- 在“有人味”的同时保持边界感，同时尽可能避免用户沉迷于AI

## 数据格式

训练数据按照jsonl格式或者sharegpt格式（json）

## 使用方式

可直接用于 LLaMA-Factory 微调或别的支持这个格式的微调工具。建议同时使用两个文件（jsonl和json）进行微调，train.jsonl 提供多样化的对话场景，train_json.json 提供更深入的上下文互动，这样效果更好。

## 许可证

本数据集采用 [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) 许可证，允许分享和修改，但不得用于商业用途。

## 免责声明
本数据集所提供的的对话旨在提供温暖，健康的陪伴风格微调数据，不构成任何形式的心理咨询、治疗或者专业建议。
本数据集所含内容均由作者本人人工编写，不包含违法、暴力、色情或诱导自残自杀等不良信息。使用者应确保其使用本数据集的方式符合其所在国家及地区的法律法规。
使用本数据集训练出的模型输出内容，均由机器学习算法自动生成，不代表数据集作者的观点、立场或意图。作者不对模型输出的内容做任何形式的主观判断或保证。
作者尊重用户的自主选择权，但强烈建议用户在使用基于本数据微调的AI（或任何AI产品）时，保持对现实世界人际关系的关注与投入。AI是工具，不是代替品。请在合法的范围内使用，并注意避免过度依赖或沉迷AI对话。如果你遇到严重的心理困扰或紧急情况，请及时联系专业的心理援助机构或拨打心理援助热线。
用户在使用本数据集进行微调、二次开发或集成应用时，应确保遵守许可证条款以及所在国家及地区的法律法规，并自行承担因使用本数据集而引发的任何直接或间接后果。
数据中存在的部分过激语言是为了让AI更加全面的学习各种语境下的正确回复，而并非用于其他用途，请大家注意甄别。同时也建议大家文明用语。
最终解释权归作者本人所有。

## 致谢

如果你使用了这个数据集，欢迎在项目中提及或引用。可以的话欢迎在Issue里留下你的使用体验或看法！

## 补充几句
如果你觉得这个仓库很眼熟或者在哪里见过，那你就感觉对了。我曾经在我的小号（HandsomeTurtleq，现已注销）中发布过这个仓库。具体原因是我目前的这个账号受到了Github的2FA限制，导致我的用户功能严重受限。不过目前我已通过了2FA验证，账号功能正在逐渐恢复，所以之后就会使用这个账号来进行后续更新哦！

## 关于这个项目

我是个学生，这个项目是我在课余时间完成的，所以数据集的数量刚开始可能有点少，还请大家见谅。如果你有任何建议、想法或者觉得哪里可以改进，欢迎提个Issue或者留个言，有时间的话我会不定期补充以及调整的，谢谢大家！（不喜勿喷哦~）


# Saudade-dataset

Training data for fine-tuning Chinese large models to better suit emotional companionship scenarios

## What is this?

This is a fine-tuning dataset designed for Chinese large language models, aiming to help the model learn more natural, warm, and companionable ways of responding.**All data was written by the author personally, with no AI-generated content. Some of the data is inspired by the author's own experiences.**

Data style:

- Avoids "robotic" tones in conversations, making interactions feel human-like
- Enhances empathy and companionship capabilities
- Maintains warmth while preserving healthy boundaries, minimizing the risk of user dependency on AI

## Data format

The training data is available in either JSONL or ShareGPT (JSON) format.

## Usage

Can be directly used with LLaMA-Factory or other fine-tuning tools that support these formats.train.jsonl offers a variety of conversation scenarios, while train_json.json provides deeper contextual interactions
## License

This dataset is released under the [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) license, allowing sharing and modification, but not for commercial purposes.

## Disclaimer

The dialogues provided in this dataset are intended solely as warm, healthy companionship-style fine-tuning material and do not constitute any form of psychological counseling, therapy, or professional advice.  
All content within this dataset has been manually crafted by the author and contains no illegal, violent, pornographic, or self-harm/suicide-inducing information. Users must ensure their use of this dataset complies with local laws and regulations.  
Model outputs generated using this dataset are automatically produced by machine learning algorithms and do not reflect the author’s opinions, positions, or intentions. The author assumes no responsibility for subjective judgments or guarantees regarding model outputs.  
While respecting users’ autonomy, we strongly encourage maintaining awareness and engagement in real-world human relationships when using AI models fine-tuned on this dataset. AI is a tool, not a replacement. Please use it responsibly and avoid over-reliance or addiction to AI conversations. If you experience serious psychological distress or an emergency, please contact professional mental health services or call a crisis hotline immediately.  
Users who fine-tune, redevelop, or integrate this dataset into applications must comply with the license terms and applicable laws and regulations, and assume full responsibility for any direct or indirect consequences arising from its use.  
Some of the overly strong language in the data is intended to help AI learn appropriate responses across various contexts more comprehensively, and is not meant for any other purpose. Please be mindful when using such content. We also encourage everyone to use polite and respectful language.
Final interpretation rights belong to the author.

## Acknowledgments

If you use this dataset, feel free to mention or cite it in your project. We welcome feedback and experiences shared via Issues!

## Note on Repository Migration

If this repository feels familiar or seems like you've seen it somewhere before—you're right! I previously published this project under my secondary account (HandsomeTurtleq, now deactivated). The reason was that my current account faced GitHub's two-factor authentication restrictions, severely limiting user functionality. However, I’ve since passed 2FA verification, and my account features are gradually being restored. From now on, I’ll be using this main account for future updates!

## About this project

I'm a student, and this project was developed during my spare time. As such, the initial dataset size may be relatively small—please bear with me. If you have any suggestions, ideas, or thoughts on improvements, feel free to open an issue or leave a comment. I'll periodically update and refine the dataset as time permits. Thank you all! (No harsh criticism, please~)

Note: The English version is translated by AI. If there are discrepancies between the English and Chinese versions, please refer to the Chinese version as the authoritative source.
