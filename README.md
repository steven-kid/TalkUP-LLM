# TalkUp-LLM

<p align="center">
   🌐 <a href="https://chatglm.cn/blog" target="_blank">Blog</a> • 🤗 <a href="https://huggingface.co/THUDM/chatglm-6b" target="_blank">HF Repo</a> • 👻 
</p>

## 介绍
本仓库用于存放**TalkUp-LLM**（基于ChatGLM-6B）进行微调的大语言模型

[ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B) 是一个开源的、支持中英双语的对话语言模型，基于 [General Language Model (GLM)](https://github.com/THUDM/GLM) 架构，具有 62 亿参数。

页面设计基于 [Chatgpt-Demo](https://github.com/anse-app/chatgpt-demo)

为达成智能教育的目标，本项目利用自然语言处理技术复现微调并训练符合英语课标要求的**大型语言模型**、导入包含英文课本英文实际对话的数据库、设计语法纠错与发音纠正算法，并利用数据挖掘与机器学习算法实现学生个性化学习，而开发的一款英语口语在线练习平台。

该平台提供基本的英语口语对话、对话人物选择、语法纠错、敏感词过滤与健康话题引导功能，支持生成学生个性化题目，导出学生个性化学习报告，旨在为欠发达地区学生提供优质的英语学习资源，助力以“**优师计划**”为代表的乡村教师开展英语教学活动。

![TalkUp.png](https://s2.loli.net/2023/07/27/zqULlIkE3j19hrH.png)

## 研究目标
本项目旨在积极响应国家“推进教育公平，共享优质资源”号召，以为我国欠发达地区学生提供优质的英语口语学习资源、助力“优师计划”英语教师提高教师数字素养，开展英语教学为研究目的，通过结合已有的前沿人工智能技术，改进与训练更优质的大型语言模型、提高优化语法纠错，并利用数据挖掘技术，开发出一款个性化的、优质且极富吸引力的在线英语口语练习平台。

<p align="center">
<img src="https://github.com/steven-kid/TalkUP-LLM/assets/96154058/9f0008b8-6313-4c21-b5fa-a5bde6c12728"/>
</p>

该平台可实现多角色、多场景的人物对话模型的选择，提供符合课程要求的英语口语对话功能，对话过程中支持敏感词检测和健康话题引导、语法纠错、，结合学生练习情况可生成学生个性化题目，学习报告。

## 现有架构设计

<p align="center">
<img src="https://github.com/steven-kid/TalkUP-LLM/assets/96154058/34ebd147-a50a-44b5-82a5-044ecf60b3bc"/ width="400px">
</p>

## 现实现功能&预期功能
人物角色选择

<p align="center">
<img width="599" alt="image" src="https://github.com/steven-kid/TalkUP-LLM/assets/96154058/b43c045e-12f0-4af4-86da-0b1574d703c4">
</p>

敏感词检测

<p align="center">
<img width="399" alt="image" src="https://github.com/steven-kid/TalkUP-LLM/assets/96154058/c50d8526-636c-4343-9e76-808cef39c047">
</p>

语法纠错示例
<p align="center">
<img width="399" alt="image" src="https://github.com/steven-kid/TalkUP-LLM/assets/96154058/b5ca09d3-aa09-436a-b729-c900372b01a1">
</p>

个性化习题

个性化报告

## 协议
本仓库的代码依照 [Apache-2.0](LICENSE) 协议开源，ChatGLM-6B 模型的权重的使用则需要遵循 [Model License](MODEL_LICENSE)。ChatGLM-6B 权重对学术研究**完全开放**，在填写[问卷](https://open.bigmodel.cn/mla/form)进行登记后**亦允许免费商业使用**。

## 参考文献
[1] 教育部等九部门. (2021). 《中西部欠发达地区优秀教师定向培养计划》. 教育部等九部门.

[2] 教育部. (2020). 教育部关于加强“三个课堂”应用的指导意见. 教科技〔2020〕3号.

[3] 刘娟娟. (2022). 乡村振兴背景下农村英语口语教学面临的机遇和挑战[J]. 名师在线, (18), 29-31.

[4] Alpaca. (2023). A Strong, Replicable Instruction-Following Model. Retrieved from https://github.com/tatsu-lab/stanford_alpaca

[5] 教育部. (2022). 推进教育公平 共享优质教育. 人民日报. Retrieved from http://www.moe.gov.cn/jyb_xwfb/moe_2082/2022/2022_zl11/202205/t20220505_624723.html

[6] 黄国栋, 徐久珺, 马传香. (2021). 基于BERT-Encoder和数据增强的语法纠错模型[J]. 湖北大学学报(自然科学版), 1-7.

[7] 王蕊. (2021). 基于神经机器翻译的英语语法错误纠正方法分析[J]. 自动化技术与应用, 40(08), 57-60+74.

[8] 邓俊锋, 朱聪慧, 赵铁军. (2020). 基于Back-translation的语法错误纠正[J]. 智能计算机与应用, 10(06), 187-190.

[9] 董权. (2019). 基于机器学习的自动发音检错系统研究[D]. 东华大学. DOI: 10.27012/d.cnki.gdhuu.2019.000022.

[10] 高源. (2018). 基于音素的语音可懂度评价方法的研究与实现[D]. 北京工业大学.

[11] Wang, J., & Gu, F. (2022). An Automatic Error Correction Method for English Composition Grammar Based on Multilayer Perceptron[J]. Mathematical Problems in Engineering, 2022, 1-7.

[12] 涂晴宇. (2019). 面向人机交互的语音情感识别与文本敏感词检测[D]. 长沙理工大学. DOI: 10.26985/d.cnki.gcsjc.2019.000026.

[13] Alibaba at IJCNLP-2017 Task 1. (2018). Embedding Grammatical Features into LSTMs for Chinese Grammatical Error Diagnosis Task: NLPTEA-2018 Task1（top 1.

[14] Devlin, J., Chang, M. W., Lee, K., & Toutanova, K. (2018). Bert: Pre-training of deep bidirectional transformers for language understanding. arXiv preprint arXiv:1810.04805.

[15] Rozovskaya, A., & Roth, D. (2016, August). Grammatical error correction: Machine translation and classifiers. In Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) (pp. 2205-2215).

[16] Ge, T., Wei, F., & Zhou, M. (2018). Reaching human-level performance in automatic grammatical error correction: An empirical study. arXiv preprint arXiv:1807.01270.

[17] Graham, S. (2017). Research into practice: The influence of discourse and oral activities on second language motivation. Language Teaching, 50(1), 1-21.

[18] UNESCO. (2020). Education for All Global Monitoring Report 2020: Inclusion and Education. UNESCO Publishing.

[19] VanLehn, K. (2011). The relative effectiveness of human tutoring, intelligent tutoring systems, and other tutoring systems. Educational Psychologist, 46(4), 197-221.

[20] Woolf, B. P. (2009). Building intelligent interactive tutors: Student-centered strategies for revolutionizing e-learning. Morgan Kaufmann.

[21] Dede, C., Ketelhut, D. J., Whitehouse, P., Breit, L., & McCloskey, E. M. (2005). An overview of current findings on the efficacy of advanced learning technologies. In Towards a new generation of educational environments (pp. 5-16). Sense Publishers, Rotterdam.

[22] Papastergiou, M. (2009). Digital Game-Based Learning in high school Computer Science education: Impact on educational effectiveness and student motivation. Computers & Education, 52(1), 1-12.

[23] Byram, M. (2008). From foreign language education to education for intercultural citizenship: Essays and reflections. Multilingual Matters.

[24] Neri, A., Cucchiarini, C., & Strik, H. (2008). The effectiveness of computer-based speech corrective feedback for improving segmental quality in L2 Dutch. ReCALL, 20(2), 225-243.

[25] Hinton, G., Deng, L., Yu, D., Dahl, G. E., Mohamed, A. R., Jaitly, N., ... & Kingsbury, B. (2012). Deep neural networks for acoustic modeling in speech recognition: The shared views of four research groups. IEEE Signal Processing Magazine, 29(6), 82-97.

[26] Woolf, B. P. (2009). Building intelligent interactive tutors: Student-centered strategies for revolutionizing e-learning. Morgan Kaufmann.
