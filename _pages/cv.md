---
layout: archive
title: "个人简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
-------
* 姓名：黄施洋
* 生日：2001年4月24日
* 籍贯：江苏 苏州
* 电话：13915714407
* 微信：[EEE1even](../images/wechat.jpg)
* 语言：CET-6
* [GitHub](https://github.com/EEE1even)(31 stars)
* [CSDN](https://blog.csdn.net/weixin_48435461?spm=1000.2115.3001.5343)(8w+ visit)

教育经历
======
* 硕士（2023-至今） 计算机技术 电子信息与工程学院 苏州科技大学
* 本科（2019-2023） 数据科学与大数据技术 数学科学学院 重庆师范大学 

实习经历
======
* 2024.07-2024.12 科大讯飞苏州研究院-自然语言处理算法实习
  * **agent plan（function call）：** 基于实际业务场景构建智能体，对复杂问题进行Thought规划，并调用对应function逐步解决。对于路径规划选择，构建对应数据，基于MCTS+PRM的方式选择最优路径来提供规划准确性。（相较于业务基线提高5.4%）
  * **信息抽取：** 设计对应任务的schema，基于schema来抽取对应信息。采用数据增强+sft的方式提高抽取的泛化性和准确性。通过大模型结合小模型的抽取方式来提高抽取模型在实际业务中的高效性和准确性（相较于业务基线提高15.7%）
  * **Text2SQL：** 通过双模型（sql生成者、sql验证者）协同处理，提高业务场景中的NL2SQL准确性（相较于业务基线提高7.6%）
  * **数据分析：** 对百万条业务数据进行数据挖掘、数据分析
> 签署保密协议，相关细节无法在简历上呈现

项目经历
======
* 2024.01-至今 苏州仲裁局智能仲裁项目-校企合作（已在苏州劳动人事仲裁院内部上线使用）
  * **庭审笔录事实抽取：** 对仲裁流程中的庭审笔录文本进行信息抽取，并基于抽取信息，针对业务的不同需求来处理抽取文本。
  * **证据模块与笔录抽取模块的协同治理：** 通过构建多模态智能体架构（证据是图片，笔录是文本），来将两个模块的数据进行交互
> 签署保密协议，相关细节无法在简历上呈现

* 2021.10-2022.12 智慧金融与大数据分析实验室-校企合作实验室
  * **单元测试：** 负责对项目的offline模块编写单元测试函数，主要使用python的unittest库进行测试。
  * **数据扩增实验：** 复现相关论文中的实验结果，并在个人数据集上进行实验。结果表明在模型蒸馏实验中，该对比学习框架能有效的在模型参数中保留知识，使得模型减重的同时也能在多分类任务中达到较高的准确度。
  * **docker服务部署：** 将实验室的相关代码仓库和文档上传部署到实验室内部服务器。
  * **wandb实验管理：** 使用WandB管理实验过程，确保数据和模型版本的一致性。对比不同变量的实验方法和效果，通过WandB的实验比较功能，找出最佳方案。

技能
======
* 熟悉pytorch、transformers、huggingface、sklearn等科学库，能快速对论文进行复现
* 熟悉FastAPI等相关api启动架构，能将相关服务启动成接口形式
* 理解大模型微调的相关架构如：sft、lora、PPO、DPO
* 了解并能使用模型训练的相关加速库如：deepspeed、flash_attention
* 理解docker使用原理，能对相关任务进行快速部署
* 熟悉Linux操作系统，能在Linux环境下进行实验和开发


