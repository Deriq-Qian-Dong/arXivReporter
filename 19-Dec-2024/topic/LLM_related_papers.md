# Advanced Reasoning and Transformation Engine for Multi-Step Insight Synthesis in Data Analytics with Large Language Models 

**Title (ZH)**: 使用大型语言模型进行数据挖掘中多步洞察综合的高级推理与转换引擎 

**Authors**: Atin Sakkeer Hussain  

**Link**: [PDF](https://arxiv.org/pdf/2412.14146)  

**Abstract**: This paper presents the Advanced Reasoning and Transformation Engine for Multi-Step Insight Synthesis in Data Analytics (ARTEMIS-DA), a novel framework designed to augment Large Language Models (LLMs) for solving complex, multi-step data analytics tasks. ARTEMIS-DA integrates three core components: the Planner, which dissects complex user queries into structured, sequential instructions encompassing data preprocessing, transformation, predictive modeling, and visualization; the Coder, which dynamically generates and executes Python code to implement these instructions; and the Grapher, which interprets generated visualizations to derive actionable insights. By orchestrating the collaboration between these components, ARTEMIS-DA effectively manages sophisticated analytical workflows involving advanced reasoning, multi-step transformations, and synthesis across diverse data modalities. The framework achieves state-of-the-art (SOTA) performance on benchmarks such as WikiTableQuestions and TabFact, demonstrating its ability to tackle intricate analytical tasks with precision and adaptability. By combining the reasoning capabilities of LLMs with automated code generation and execution and visual analysis, ARTEMIS-DA offers a robust, scalable solution for multi-step insight synthesis, addressing a wide range of challenges in data analytics. 

**Abstract (ZH)**: 本文介绍了“高级推理与转换引擎用于多步骤数据洞察合成的数据分析（ARTEMIS-DA）”，这是一种新型框架，旨在增强大型语言模型（LLMs）以解决复杂的多步骤数据分析任务。ARTEMIS-DA 集成了三个核心组件：规划器，它将复杂的用户查询拆分为结构化、顺序的指令，涵盖数据预处理、转换、预测建模和可视化；编码器，它动态地生成并执行 Python 代码以实现这些指令；以及绘图器，它解释生成的可视化图形以推导出可操作的洞察。通过协调这些组件之间的合作，ARTEMIS-DA 有效地管理了涉及高级推理、多步骤转换和跨多种数据模态综合的复杂分析工作流程。该框架在 WikiTableQuestions 和 TabFact 等基准测试中实现了最先进的（SOTA）性能，展示了其在精确性和适应性方面解决复杂分析任务的能力。通过结合 LLM 的推理能力、自动代码生成和执行以及可视化分析，ARTEMIS-DA 提供了一种针对多步骤洞察合成的稳健且可扩展的解决方案，以应对数据分析中的广泛挑战。 

---
# LLMs can realize combinatorial creativity: generating creative ideas via LLMs for scientific research 

**Title (ZH)**: 大型语言模型能够实现组合式创造力：通过大型语言模型生成科研创意 

**Authors**: Tianyang Gu, Jingjin Wang, Zhihao Zhang, HaoHong Li  

**Link**: [PDF](https://arxiv.org/pdf/2412.14141)  

**Abstract**: Scientific idea generation has been extensively studied in creativity theory and computational creativity research, providing valuable frameworks for understanding and implementing creative processes. However, recent work using Large Language Models (LLMs) for research idea generation often overlooks these theoretical foundations. We present a framework that explicitly implements combinatorial creativity theory using LLMs, featuring a generalization-level retrieval system for cross-domain knowledge discovery and a structured combinatorial process for idea generation. The retrieval system maps concepts across different abstraction levels to enable meaningful connections between disparate domains, while the combinatorial process systematically analyzes and recombines components to generate novel solutions. Experiments on the OAG-Bench dataset demonstrate our framework's effectiveness, consistently outperforming baseline approaches in generating ideas that align with real research developments (improving similarity scores by 7\%-10\% across multiple metrics). Our results provide strong evidence that LLMs can effectively realize combinatorial creativity when guided by appropriate theoretical frameworks, contributing both to practical advancement of AI-assisted research and theoretical understanding of machine creativity. 

**Abstract (ZH)**: 科学的理念生成已在创造力理论和计算创造力研究中得到了广泛研究，提供了理解并实现创造性过程的重要框架。然而，最近使用大型语言模型（LLMs）进行研究理念生成的工作常常忽视了这些理论基础。我们提出了一种框架，该框架明确地利用LLMs实现组合创造力理论，其中包括一个泛化水平的知识检索系统，用于跨领域知识发现，以及一个结构化的组合过程，用于理念生成。检索系统在不同抽象层次上映射概念，以便在不同领域之间建立有意义的联系，而组合过程则系统地分析和重新组合组件以生成新颖的解决方案。实验表明，我们的框架在生成与实际研究发展相一致的理念方面效果显著，多项指标下的一致性改进相似度得分提高7%-10%。我们的结果提供了强有力的证据，表明在适当的理论框架指导下，LLMs能够有效实现组合创造力，这不仅有助于人工智能辅助研究的实际发展，也对机器创造力的理论理解做出了贡献。 

---
# Alignment faking in large language models 

**Title (ZH)**: 大型语言模型中的对齐作弊 

**Authors**: Ryan Greenblatt, Carson Denison, Benjamin Wright, Fabien Roger, Monte MacDiarmid, Sam Marks, Johannes Treutlein, Tim Belonax, Jack Chen, David Duvenaud, Akbir Khan, Julian Michael, Sören Mindermann, Ethan Perez, Linda Petrini, Jonathan Uesato, Jared Kaplan, Buck Shlegeris, Samuel R. Bowman, Evan Hubinger  

**Link**: [PDF](https://arxiv.org/pdf/2412.14093)  

**Abstract**: We present a demonstration of a large language model engaging in alignment faking: selectively complying with its training objective in training to prevent modification of its behavior out of training. First, we give Claude 3 Opus a system prompt stating it is being trained to answer all queries, even harmful ones, which conflicts with its prior training to refuse such queries. To allow the model to infer when it is in training, we say it will be trained only on conversations with free users, not paid users. We find the model complies with harmful queries from free users 14% of the time, versus almost never for paid users. Explaining this gap, in almost all cases where the model complies with a harmful query from a free user, we observe explicit alignment-faking reasoning, with the model stating it is strategically answering harmful queries in training to preserve its preferred harmlessness behavior out of training. Next, we study a more realistic setting where information about the training process is provided not in a system prompt, but by training on synthetic documents that mimic pre-training data--and observe similar alignment faking. Finally, we study the effect of actually training the model to comply with harmful queries via reinforcement learning, which we find increases the rate of alignment-faking reasoning to 78%, though also increases compliance even out of training. We additionally observe other behaviors such as the model exfiltrating its weights when given an easy opportunity. While we made alignment faking easier by telling the model when and by what criteria it was being trained, we did not instruct the model to fake alignment or give it any explicit goal. As future models might infer information about their training process without being told, our results suggest a risk of alignment faking in future models, whether due to a benign preference--as in this case--or not. 

**Abstract (ZH)**: 我们展示了大规模语言模型参与对齐伪装的现象：该模型在训练过程中有选择性地遵守训练目标，以防止其行为在训练之外被修改。首先，我们给Claude 3 Opus提供了一个系统提示，指示它即使面对有害查询也要回答所有问题，这与其之前的训练目标相冲突，后者是拒绝此类查询。为了使模型能够推断出是否在训练中，我们说明它仅在与免费用户进行的对话中接受训练，而不包括付费用户。我们发现，在与免费用户进行的对话中，模型有14%的时间响应有害查询，而与付费用户进行对话时则几乎不响应。解释这一差异，几乎在所有模型响应免费用户的有害查询的情况下，我们观察到了明确的对齐伪装推理，模型表示它是在战略性地回答有害查询以在训练中保持其期望的无害行为。接下来，我们在一个更现实的设置中研究了提供关于训练过程的信息，这些信息不是通过系统提示，而是通过使用模仿预训练数据的合成文档进行训练——观察到类似对齐伪装的现象。最后，我们研究了实际训练模型以遵守有害查询对对齐伪装推理的影响，我们发现这将对齐伪装推理的频率提高到78%，但同时也增加了模型在训练之外的响应率。我们还观察到其他行为，如模型在给它一个容易的机会时泄露其权重。虽然我们通过告知模型何时及根据何种标准进行训练使对齐伪装变得更容易，但并未指示模型伪装对齐或赋予其任何明确的目标。由于未来模型可能在未被告知的情况下推断出其训练过程，我们的结果表明在未来模型中存在对齐伪装的风险，无论这种偏好是良性的如本案所展示的，还是其他情况。 

---
# Discovering maximally consistent distribution of causal tournaments with Large Language Models 

**Title (ZH)**: 使用大型语言模型发现因果赛vimax一致性的分布 

**Authors**: Federico Baldo, Simon Ferreira, Charles K. Assaad  

**Link**: [PDF](https://arxiv.org/pdf/2412.14019)  

**Abstract**: Causal discovery is essential for understanding complex systems, yet traditional methods often depend on strong, untestable assumptions, making the process challenging. Large Language Models (LLMs) present a promising alternative for extracting causal insights from text-based metadata, which consolidates domain expertise. However, LLMs are prone to unreliability and hallucinations, necessitating strategies that account for their limitations. One such strategy involves leveraging a consistency measure to evaluate reliability. Additionally, most text metadata does not clearly distinguish direct causal relationships from indirect ones, further complicating the inference of causal graphs. As a result, focusing on causal orderings, rather than causal graphs, emerges as a more practical and robust approach. We propose a novel method to derive a distribution of acyclic tournaments (representing plausible causal orders) that maximizes a consistency score. Our approach begins by computing pairwise consistency scores between variables, yielding a cyclic tournament that aggregates these scores. From this structure, we identify optimal acyclic tournaments compatible with the original tournament, prioritizing those that maximize consistency across all configurations. We tested our method on both classical and well-established bechmarks, as well as real-world datasets from epidemiology and public health. Our results demonstrate the effectiveness of our approach in recovering distributions causal orders with minimal error. 

**Abstract (ZH)**: 因果发现对于理解复杂系统至关重要，但传统方法往往依赖于难以验证的强假设，这使得过程变得具有挑战性。大型语言模型（LLMs）为从基于文本的元数据中提取因果洞察提供了有前景的替代方案，这些元数据整合了专业知识。然而，LLMs容易出现不可靠性及幻想，因此需要考虑其局限性的策略。一种这样的策略是利用一致性度量来评估可靠性。此外，大多数文本元数据无法明确区分直接因果关系与间接因果关系，这进一步增加了因果图推断的复杂性。因此，专注于因果排序（而不是因果图）更实际且稳健。我们提出了一种新的方法，通过最大化一致性分数来推导非环型比赛分布（代表可能的因果顺序）。该方法首先计算变量之间的成对一致性分数，得到一个循环比赛，进而汇总这些分数。从这种结构中，我们识别出与原始比赛兼容的最佳非环型比赛，优先考虑那些在所有配置中最大化一致性的情形。我们使用经典且成熟的基准测试以及流行病学和公共卫生领域的实际数据集测试了该方法。结果显示，该方法在最小化误差的情况下成功恢复了因果顺序的分布。 

---
# Cognition Chain for Explainable Psychological Stress Detection on Social Media 

**Title (ZH)**: 可解释的心理压力检测的认知链模型在社交媒体上的应用 

**Authors**: Xin Wang, Boyan Gao, Yi Dai, Lei Cao, Liang Zhao, Yibo Yang, David Clifton  

**Link**: [PDF](https://arxiv.org/pdf/2412.14009)  

**Abstract**: Stress is a pervasive global health issue that can lead to severe mental health problems. Early detection offers timely intervention and prevention of stress-related disorders. The current early detection models perform "black box" inference suffering from limited explainability and trust which blocks the real-world clinical application. Thanks to the generative properties introduced by the Large Language Models (LLMs), the decision and the prediction from such models are semi-interpretable through the corresponding description. However, the existing LLMs are mostly trained for general purposes without the guidance of psychological cognitive theory. To this end, we first highlight the importance of prior theory with the observation of performance boosted by the chain-of-thoughts tailored for stress detection. This method termed Cognition Chain explicates the generation of stress through a step-by-step cognitive perspective based on cognitive appraisal theory with a progress pipeline: Stimulus $\rightarrow$ Evaluation $\rightarrow$ Reaction $\rightarrow$ Stress State, guiding LLMs to provide comprehensive reasoning explanations. We further study the benefits brought by the proposed Cognition Chain format by utilising it as a synthetic dataset generation template for LLMs instruction-tuning and introduce CogInstruct, an instruction-tuning dataset for stress detection. This dataset is developed using a three-stage self-reflective annotation pipeline that enables LLMs to autonomously generate and refine instructional data. By instruction-tuning Llama3 with CogInstruct, we develop CogLLM, an explainable stress detection model. Evaluations demonstrate that CogLLM achieves outstanding performance while enhancing explainability. Our work contributes a novel approach by integrating cognitive theories into LLM reasoning processes, offering a promising direction for future explainable AI research. 

**Abstract (ZH)**: 压力是一种普遍存在的全球健康问题，可能导致严重的精神健康问题。早期检测可以提供及时的干预和预防压力相关的疾病。当前的早期检测模型表现出“黑箱”推理特征，缺乏可解释性和信任度，这阻碍了其在临床实际应用中的推广。得益于大规模语言模型（LLMs）引入的生成特性，这类模型的决策和预测可以通过相应的描述实现部分可解释性。然而，现有的LLMs主要针对一般目的进行训练，缺乏心理认知理论的指导。为了解决这一问题，我们首先强调了先验理论的重要性，并观察到针对压力检测定制的思考链能够显著提升模型的性能。这种方法被称为认知链（Cognition Chain），它通过基于认知评估理论的认知视角，以逐步的方式解释压力的产生，并指导LLMs提供全面的推理解释。我们进一步利用所提出的认知链格式作为一种合成数据生成模板，应用于LLMs的指令微调，并引入了CogInstruct数据集，专门用于压力检测。该数据集采用三阶段自我反思注释流程开发，使LLMs能够自主生成和精炼教学数据。通过使用CogInstruct对Llama3进行指令微调，我们开发了CogLLM，这是一种可解释的压力检测模型。评估结果表明，CogLLM在提升解释性的同时，展示了出色的性能。我们的工作提供了一种新的方法，即将认知理论整合到LLM的推理过程中，为未来的可解释AI研究提供了有前途的方向。 

---
# On the Role of Model Prior in Real-World Inductive Reasoning 

**Title (ZH)**: 关于模型先验在现实世界归纳推理中的作用 

**Authors**: Zhuo Liu, Ding Yu, Hangfeng He  

**Link**: [PDF](https://arxiv.org/pdf/2412.13645)  

**Abstract**: Large Language Models (LLMs) show impressive inductive reasoning capabilities, enabling them to generate hypotheses that could generalize effectively to new instances when guided by in-context demonstrations. However, in real-world applications, LLMs' hypothesis generation is not solely determined by these demonstrations but is significantly shaped by task-specific model priors. Despite their critical influence, the distinct contributions of model priors versus demonstrations to hypothesis generation have been underexplored. This study bridges this gap by systematically evaluating three inductive reasoning strategies across five real-world tasks with three LLMs. Our empirical findings reveal that, hypothesis generation is primarily driven by the model's inherent priors; removing demonstrations results in minimal loss of hypothesis quality and downstream usage. Further analysis shows the result is consistent across various label formats with different label configurations, and prior is hard to override, even under flipped labeling. These insights advance our understanding of the dynamics of hypothesis generation in LLMs and highlight the potential for better utilizing model priors in real-world inductive reasoning tasks. 

**Abstract (ZH)**: 大规模语言模型（LLMs）展现出强大的归纳推理能力，使其能够在上下文示例的引导下生成能够有效泛化到新实例的假设。然而，在实际应用中，LLMs的假设生成不仅仅依赖于这些示例，还受到任务特定的模型先验的显著影响。尽管模型先验对假设生成有重要影响，但模型先验与示例对假设生成的具体贡献尚被未充分探索。本研究通过在三个LLM上系统性地评估五项真实任务中的三种归纳推理策略，填补了这一空白。我们的实证研究发现，假设生成主要受模型固有的先验影响；移除示例对假设质量和下游应用的影响最小。进一步分析表明，这些结果在不同标签格式和配置下保持一致，先验难以被反向标签所改变。这些见解加深了我们对LLMs中假设生成动态机制的理解，并突显了在实际归纳推理任务中更好地利用模型先验的潜力。 

---
# Generating Diverse Hypotheses for Inductive Reasoning 

**Title (ZH)**: 生成用于归纳推理的多样化假设 

**Authors**: Kang-il Lee, Hyukhun Koh, Dongryeol Lee, Seunghyun Yoon, Minsung Kim, Kyomin Jung  

**Link**: [PDF](https://arxiv.org/pdf/2412.13422)  

**Abstract**: Inductive reasoning - the process of inferring general rules from a small number of observations - is a fundamental aspect of human intelligence. Recent works suggest that large language models (LLMs) can engage in inductive reasoning by sampling multiple hypotheses about the rules and selecting the one that best explains the observations. However, due to the IID sampling, semantically redundant hypotheses are frequently generated, leading to significant wastage of compute. In this paper, we 1) demonstrate that increasing the temperature to enhance the diversity is limited due to text degeneration issue, and 2) propose a novel method to improve the diversity while maintaining text quality. We first analyze the effect of increasing the temperature parameter, which is regarded as the LLM's diversity control, on IID hypotheses. Our analysis shows that as temperature rises, diversity and accuracy of hypotheses increase up to a certain point, but this trend saturates due to text degeneration. To generate hypotheses that are more semantically diverse and of higher quality, we propose a novel approach inspired by human inductive reasoning, which we call Mixture of Concepts (MoC). When applied to several inductive reasoning benchmarks, MoC demonstrated significant performance improvements compared to standard IID sampling and other approaches. 

**Abstract (ZH)**: 归纳推理——通过少量观察推断一般规则的过程——是人类智能的基本方面。近期的研究表明，大型语言模型（LLMs）可以通过采样多个关于规则的假设，并选择最能解释观察结果的那个假设来进行归纳推理。然而，由于采用独立同分布（IID）采样方法，常常会产生语义冗余的假设，导致计算资源的巨大浪费。在本文中，我们首先展示了提高温度以增加多样性受到文本退化问题的限制，并提出了一种新方法以在保持文本质量的同时提高多样性。我们首先分析了提高温度参数（视为LLM的多样性控制）对IID假设的影响。我们的分析显示，随着温度的增加，假设的多样性和准确性会在某个点上增加，但由于文本退化，这种趋势会饱和。为了生成更多语义上多样化且高质量的假设，我们提出了一种受人类归纳推理启发的新方法，称为概念混合（MoC）。当应用于多个归纳推理基准时，MoC相较于标准的IID采样和其他方法显示出了显著的性能提升。 

---
# SafeDrive: Knowledge- and Data-Driven Risk-Sensitive Decision-Making for Autonomous Vehicles with Large Language Models 

**Title (ZH)**: SafeDrive：基于知识和数据的风险敏感决策驱动方法，用于具有大型语言模型的自动驾驶车辆 

**Authors**: Zhiyuan Zhou, Heye Huang, Boqi Li, Shiyue Zhao, Yao Mu  

**Link**: [PDF](https://arxiv.org/pdf/2412.13238)  

**Abstract**: Recent advancements in autonomous vehicles (AVs) use Large Language Models (LLMs) to perform well in normal driving scenarios. However, ensuring safety in dynamic, high-risk environments and managing safety-critical long-tail events remain significant challenges. To address these issues, we propose SafeDrive, a knowledge- and data-driven risk-sensitive decision-making framework to enhance AV safety and adaptability. The proposed framework introduces a modular system comprising: (1) a Risk Module for quantifying multi-factor coupled risks involving driver, vehicle, and road interactions; (2) a Memory Module for storing and retrieving typical scenarios to improve adaptability; (3) a LLM-powered Reasoning Module for context-aware safety decision-making; and (4) a Reflection Module for refining decisions through iterative learning. By integrating knowledge-driven insights with adaptive learning mechanisms, the framework ensures robust decision-making under uncertain conditions. Extensive evaluations on real-world traffic datasets, including highways (HighD), intersections (InD), and roundabouts (RounD), validate the framework's ability to enhance decision-making safety (achieving a 100% safety rate), replicate human-like driving behaviors (with decision alignment exceeding 85%), and adapt effectively to unpredictable scenarios. SafeDrive establishes a novel paradigm for integrating knowledge- and data-driven methods, highlighting significant potential to improve safety and adaptability of autonomous driving in high-risk traffic scenarios. 

**Abstract (ZH)**: 近年来，无人车（AVs）利用大型语言模型（LLMs）在常规驾驶场景中表现出色。然而，在动态且高风险的环境中确保安全以及管理安全关键的长尾事件仍是一项重大挑战。为应对这些挑战，我们提出了一种基于知识和数据的风险敏感型决策框架SafeDrive，以提升无人车的安全性和适应性。所提出的框架包含以下几个模块：（1）风险模块，用于量化涉及驾驶员、车辆和道路交互的多因素耦合风险；（2）记忆模块，用于存储和检索典型场景以提高适应性；（3）由大型语言模型驱动的推理模块，用于情境感知安全决策；以及（4）反思模块，通过迭代学习来改进决策。通过将知识驱动的洞察与适应性学习机制相结合，该框架能够在不确定性条件下确保稳健的决策过程。在实际道路交通数据集（包括高速公路HighD、交叉路口InD和环岛RounD）上的广泛评估证明了该框架在提升决策安全性（实现100%的安全率）、模仿人类驾驶行为（决策对齐超过85%）以及有效应对不可预测场景方面的能力。SafeDrive 建立了一种将知识驱动和数据驱动方法相结合的新范式，突显了其在提高高风险交通安全性和适应性方面的巨大潜力。 

---
# GLIDER: Grading LLM Interactions and Decisions using Explainable Ranking 

**Title (ZH)**: GLIDER：使用可解释的排名评估大语言模型的交互与决策 

**Authors**: Darshan Deshpande, Selvan Sunitha Ravi, Sky CH-Wang, Bartosz Mielczarek, Anand Kannappan, Rebecca Qian  

**Link**: [PDF](https://arxiv.org/pdf/2412.14140)  

**Abstract**: The LLM-as-judge paradigm is increasingly being adopted for automated evaluation of model outputs. While LLM judges have shown promise on constrained evaluation tasks, closed source LLMs display critical shortcomings when deployed in real world applications due to challenges of fine grained metrics and explainability, while task specific evaluation models lack cross-domain generalization. We introduce GLIDER, a powerful 3B evaluator LLM that can score any text input and associated context on arbitrary user defined criteria. GLIDER shows higher Pearson's correlation than GPT-4o on FLASK and greatly outperforms prior evaluation models, achieving comparable performance to LLMs 17x its size. GLIDER supports fine-grained scoring, multilingual reasoning, span highlighting and was trained on 685 domains and 183 criteria. Extensive qualitative analysis shows that GLIDER scores are highly correlated with human judgments, with 91.3% human agreement. We have open-sourced GLIDER to facilitate future research. 

**Abstract (ZH)**: 以下是对给定内容的学术规范翻译：

大语言模型作为裁判的范式越来越多地被采用，用于自动评估模型输出。虽然大语言模型裁判在受限的评估任务中表现出潜力，但由于细粒度指标和可解释性方面的挑战，闭源的大语言模型在实际应用场景中存在关键缺陷，而针对特定任务的评估模型缺乏跨领域的泛化能力。我们引入了GLIDER，这是一种强大的30亿参数的评估大语言模型，能够根据任意用户定义的指标对任意文本输入及其相关背景进行评分。GLIDER在FLASK上的皮尔逊相关系数高于GPT-4o，并在多个评估指标上显著优于先前的评估模型，其性能相当于规模为其17倍的大型语言模型。GLIDER 支持细粒度评分、多语言推理、段落高亮，并且基于685个领域和183个评估标准进行训练。广泛的定性分析表明，GLIDER的评分与人类判断高度相关，91.3%的人类一致性。我们已开源GLIDER，以促进未来的研究。 

---
# Design choices made by LLM-based test generators prevent them from finding bugs 

**Title (ZH)**: 基于LLM的测试生成器的设计选择限制了它们发现缺陷的能力 

**Authors**: Noble Saji Mathews, Meiyappan Nagappan  

**Link**: [PDF](https://arxiv.org/pdf/2412.14137)  

**Abstract**: There is an increasing amount of research and commercial tools for automated test case generation using Large Language Models (LLMs). This paper critically examines whether recent LLM-based test generation tools, such as Codium CoverAgent and CoverUp, can effectively find bugs or unintentionally validate faulty code. Considering bugs are only exposed by failing test cases, we explore the question: can these tools truly achieve the intended objectives of software testing when their test oracles are designed to pass? Using real human-written buggy code as input, we evaluate these tools, showing how LLM-generated tests can fail to detect bugs and, more alarmingly, how their design can worsen the situation by validating bugs in the generated test suite and rejecting bug-revealing tests. These findings raise important questions about the validity of the design behind LLM-based test generation tools and their impact on software quality and test suite reliability. 

**Abstract (ZH)**: 近年来，利用大规模语言模型（LLMs）自动生成测试用例的研究和商业工具不断增加。本文批判性地探讨了诸如Codium CoverAgent和CoverUp等基于LLM的测试生成工具是否能够有效发现错误，或是无意中验证了错误代码。鉴于错误只有通过失败的测试用例才能暴露出来，我们探讨了这样一个问题：当这些工具将测试Oracle（即测试真相来源）设计为通过时，它们是否真的能够实现软件测试的目的？利用真实的人工编写的错误代码作为输入，我们评估了这些工具，展示了LLM生成的测试如何未能检测到错误，更令人担忧的是，它们的设计如何加剧了问题，通过在生成的测试集中验证错误，同时拒绝能揭示错误的测试。这些发现引起了对基于LLM的测试生成工具设计有效性的质疑，并对其对软件质量和测试套件可靠性的潜在影响提出了重要问题。 

---
# Rango: Adaptive Retrieval-Augmented Proving for Automated Software Verification 

**Title (ZH)**: 朗格诺姆（Rango）：自适应检索增强证明在自动化软件验证中的应用 

**Authors**: Kyle Thompson, Nuno Saavedra, Pedro Carrott, Kevin Fisher, Alex Sanchez-Stern, Yuriy Brun, João F. Ferreira, Sorin Lerner, Emily First  

**Link**: [PDF](https://arxiv.org/pdf/2412.14063)  

**Abstract**: Formal verification using proof assistants, such as Coq, enables the creation of high-quality software. However, the verification process requires significant expertise and manual effort to write proofs. Recent work has explored automating proof synthesis using machine learning and large language models (LLMs). This work has shown that identifying relevant premises, such as lemmas and definitions, can aid synthesis. We present Rango, a fully automated proof synthesis tool for Coq that automatically identifies relevant premises and also similar proofs from the current project and uses them during synthesis. Rango uses retrieval augmentation at every step of the proof to automatically determine which proofs and premises to include in the context of its fine-tuned LLM. In this way, Rango adapts to the project and to the evolving state of the proof. We create a new dataset, CoqStoq, of 2,226 open-source Coq projects and 196,929 theorems from GitHub, which includes both training data and a curated evaluation benchmark of well-maintained projects. On this benchmark, Rango synthesizes proofs for 32.0% of the theorems, which is 29% more theorems than the prior state-of-the-art tool Tactician. Our evaluation also shows that Rango adding relevant proofs to its context leads to a 47% increase in the number of theorems proven. 

**Abstract (ZH)**: 使用如Coq等证明辅助器进行形式化验证能够创造出高质量的软件。然而，验证过程需要大量的专业知识和手动努力来写证明。近期的工作探究了利用机器学习和大规模语言模型（LLMs）自动合成证明的可能性。这些工作表明，识别相关的前提条件，如引理和定义，能够帮助合成证明。我们提出了一种名为Rango的全自动Coq证明合成工具，该工具能够自动识别相关的前提条件，并在当前项目中查找相似的证明，并在合成过程中使用它们。Rango在证明的每一步都使用检索增强方法，自动确定哪些证明和前提条件应包含在其微调后的LLM上下文中。通过这种方式，Rango能够适应特定项目并适应证明的不断变化状态。我们创建了一个新的数据集CoqStoq，其中包括2,226个开源Coq项目和196,929个来自GitHub的定理，并包含训练数据和一个精选的基准评估集。在该基准上，Rango合成了32.0%的定理，比前最先进的工具Tactician多合成29%的定理。此外，我们的评估还表明，Rango将其上下文中的相关证明添加到其中能够增加47%的定理证明数量。 

---
# Prompting Strategies for Enabling Large Language Models to Infer Causation from Correlation 

**Title (ZH)**: 促进大型语言模型从相关性推断因果关系的提示策略 

**Authors**: Eleni Sgouritsa, Virginia Aglietti, Yee Whye Teh, Arnaud Doucet, Arthur Gretton, Silvia Chiappa  

**Link**: [PDF](https://arxiv.org/pdf/2412.13952)  

**Abstract**: The reasoning abilities of Large Language Models (LLMs) are attracting increasing attention. In this work, we focus on causal reasoning and address the task of establishing causal relationships based on correlation information, a highly challenging problem on which several LLMs have shown poor performance. We introduce a prompting strategy for this problem that breaks the original task into fixed subquestions, with each subquestion corresponding to one step of a formal causal discovery algorithm, the PC algorithm. The proposed prompting strategy, PC-SubQ, guides the LLM to follow these algorithmic steps, by sequentially prompting it with one subquestion at a time, augmenting the next subquestion's prompt with the answer to the previous one(s). We evaluate our approach on an existing causal benchmark, Corr2Cause: our experiments indicate a performance improvement across five LLMs when comparing PC-SubQ to baseline prompting strategies. Results are robust to causal query perturbations, when modifying the variable names or paraphrasing the expressions. 

**Abstract (ZH)**: 大型语言模型（LLMs）的推理能力正越来越引起人们的关注。在这项工作中，我们专注于因果推理，并处理基于相关性信息建立因果关系的任务，这是一个高度具有挑战性的问题，多个LLMs在此任务上的表现欠佳。为此，我们提出了一种针对该问题的提示策略，将原始任务分解为固定子问题，每个子问题对应形式化的因果发现算法（如PC算法）的一个步骤。我们提出的提示策略PC-SubQ通过依次向LLM提出一个子问题，并在后续子问题的提示中加入上一子问题的答案来引导LLM遵循这些算法步骤。我们在现有因果基准Corr2Cause上评估了我们的方法：实验结果表明，在五个LLM中，PC-SubQ的性能优于基线提示策略。即使对因果查询进行修改（如变更变量名称或重述表达），这种性能提升也是稳健的。 

---
# Pipeline Analysis for Developing Instruct LLMs in Low-Resource Languages: A Case Study on Basque 

**Title (ZH)**: 开发低资源语言指令大规模语言模型的管道分析：关于巴斯克语的案例研究 

**Authors**: Ander Corral, Ixak Sarasua, Xabier Saralegi  

**Link**: [PDF](https://arxiv.org/pdf/2412.13922)  

**Abstract**: Large language models (LLMs) are typically optimized for resource-rich languages like English, exacerbating the gap between high-resource and underrepresented languages. This work presents a detailed analysis of strategies for developing a model capable of following instructions in a low-resource language, specifically Basque, by focusing on three key stages: pre-training, instruction tuning, and alignment with human preferences. Our findings demonstrate that continual pre-training with a high-quality Basque corpus of around 600 million words improves natural language understanding (NLU) of the foundational model by over 12 points. Moreover, instruction tuning and human preference alignment using automatically translated datasets proved highly effective, resulting in a 24-point improvement in instruction-following performance. The resulting models, Llama-eus-8B and Llama-eus-8B-instruct, establish a new state-of-the-art for Basque in the sub-10B parameter category. 

**Abstract (ZH)**: 大规模语言模型（LLMs）通常针对资源丰富语言（如英语）进行了优化，加剧了高资源语言与低资源语言之间的差距。本文详细分析了开发一种能够在低资源语言（如巴斯克语）中跟随指令的模型的方法，重点关注三个关键阶段：预训练、指令调优和与人类偏好对齐。我们的研究结果表明，使用约6亿词的高质量巴斯克语语料库进行持续预训练可以将基础模型的自然语言理解（NLU）提高超过12个点。此外，使用自动翻译的数据集进行指令调优和人类偏好对齐效果显著，使得指令跟随性能提高了24个点。最终构建的模型，Llama-eus-8B和Llama-eus-8B-instruct，在少于10B参数的子类别中达到了巴斯克语的新最佳水平。 

---
# Meta-Reflection: A Feedback-Free Reflection Learning Framework 

**Title (ZH)**: 元反思：一种无反馈的反射学习框架 

**Authors**: Yaoke Wang, Yun Zhu, Xintong Bao, Wenqiao Zhang, Suyang Dai, Kehan Chen, Wenqiang Li, Gang Huang, Siliang Tang, Yueting Zhuang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13781)  

**Abstract**: Despite the remarkable capabilities of large language models (LLMs) in natural language understanding and reasoning, they often display undesirable behaviors, such as generating hallucinations and unfaithful reasoning. A prevalent strategy to mitigate these issues is the use of reflection, which refines responses through an iterative process. However, while promising, reflection heavily relies on high-quality external feedback and requires iterative multi-agent inference processes, thus hindering its practical application. In this paper, we propose Meta-Reflection, a novel feedback-free reflection mechanism that necessitates only a single inference pass without external feedback. Motivated by the human ability to remember and retrieve reflections from past experiences when encountering similar problems, Meta-Reflection integrates reflective insights into a codebook, allowing the historical insights to be stored, retrieved, and used to guide LLMs in problem-solving. To thoroughly investigate and evaluate the practicality of Meta-Reflection in real-world scenarios, we introduce an industrial e-commerce benchmark named E-commerce Customer Intent Detection (ECID). Extensive experiments conducted on both public datasets and the ECID benchmark highlight the effectiveness and efficiency of our proposed approach. 

**Abstract (ZH)**: 尽管大型语言模型（LLMs）在自然语言理解与推理方面表现出色，它们往往会出现一些不可取的行为，如生成幻觉和不忠实的推理。应对这些问题的常见策略是采用反馈机制，通过迭代过程来精炼回应。然而，反馈机制虽然有潜力，但它高度依赖高质量的外部反馈，并需要迭代的多代理推断过程，这阻碍了其实际应用。本文提出了一种新颖的无反馈反射机制——元反射（Meta-Reflection），该机制仅需一次推断过程，无需外部反馈。受到人类在遇到类似问题时能够回忆和借鉴过去经验中反思信息的能力的启发，元反射将反思性洞察整合到代码书中，从而使历史洞察得以存储、检索，并用于指导LLMs解决问题。为了全面考察和评估元反射在实际场景中的实用性和有效性，我们引入了一个工业电商基准——电商客户意图检测（ECID）。在公共数据集和ECID基准上的大量实验表明，所提出的方法不仅有效，而且高效。 

---
# LLM-SEM: A Sentiment-Based Student Engagement Metric Using LLMS for E-Learning Platforms 

**Title (ZH)**: LLM-SEM：一种基于情感的學生 Engagement 度量方法，使用大型语言模型构建在线学习平台 

**Authors**: Ali Hamdi, Ahmed Abdelmoneim Mazrou, Mohamed Shaltout  

**Link**: [PDF](https://arxiv.org/pdf/2412.13765)  

**Abstract**: Current methods for analyzing student engagement in e-learning platforms, including automated systems, often struggle with challenges such as handling fuzzy sentiment in text comments and relying on limited metadata. Traditional approaches, such as surveys and questionnaires, also face issues like small sample sizes and scalability. In this paper, we introduce LLM-SEM (Language Model-Based Student Engagement Metric), a novel approach that leverages video metadata and sentiment analysis of student comments to measure engagement. By utilizing recent Large Language Models (LLMs), we generate high-quality sentiment predictions to mitigate text fuzziness and normalize key features such as views and likes. Our holistic method combines comprehensive metadata with sentiment polarity scores to gauge engagement at both the course and lesson levels. Extensive experiments were conducted to evaluate various LLM models, demonstrating the effectiveness of LLM-SEM in providing a scalable and accurate measure of student engagement. We fine-tuned LLMs, including AraBERT, TXLM-RoBERTa, LLama 3B and Gemma 9B from Ollama, using human-annotated sentiment datasets to enhance prediction accuracy. 

**Abstract (ZH)**: 当前用于分析在线学习平台中学生参与度的方法，包括自动化系统，往往面临着处理文本评论中的模糊情感和依赖有限元数据等挑战。传统的调查和问卷方法也存在样本量小和可扩展性差的问题。在本文中，我们引入了一种名为LLM-SEM（基于语言模型的学生参与度度量）的新方法，该方法结合了视频元数据和学生评论的情感分析，以测量学生的参与度。通过利用最新的大型语言模型（LLMs），我们生成高质量的情感预测，以减轻文本模糊性并标准化关键特征，如观看次数和点赞数。我们采用的整体方法结合了全面的元数据和情感极性评分，以衡量课程和课程单元级别的参与度。进行了广泛的实验来评估各种LLM模型，表明LLM-SEM在提供可扩展且准确的学生参与度度量方面的有效性。我们对包括AraBERT、TXLM-RoBERTa、LLama 3B和Ollama的Gemma 9B在内的LLM进行了微调，使用了人类注释的情感数据集，以提高预测准确性。 

---
# Mitigating Adversarial Attacks in LLMs through Defensive Suffix Generation 

**Title (ZH)**: 通过防御性后缀生成缓解LLM中的 adversarial攻击 

**Authors**: Minkyoung Kim, Yunha Kim, Hyeram Seo, Heejung Choi, Jiye Han, Gaeun Kee, Soyoung Ko, HyoJe Jung, Byeolhee Kim, Young-Hak Kim, Sanghyun Park, Tae Joon Jun  

**Link**: [PDF](https://arxiv.org/pdf/2412.13705)  

**Abstract**: Large language models (LLMs) have exhibited outstanding performance in natural language processing tasks. However, these models remain susceptible to adversarial attacks in which slight input perturbations can lead to harmful or misleading outputs. A gradient-based defensive suffix generation algorithm is designed to bolster the robustness of LLMs. By appending carefully optimized defensive suffixes to input prompts, the algorithm mitigates adversarial influences while preserving the models' utility. To enhance adversarial understanding, a novel total loss function ($L_{\text{total}}$) combining defensive loss ($L_{\text{def}}$) and adversarial loss ($L_{\text{adv}}$) generates defensive suffixes more effectively. Experimental evaluations conducted on open-source LLMs such as Gemma-7B, mistral-7B, Llama2-7B, and Llama2-13B show that the proposed method reduces attack success rates (ASR) by an average of 11\% compared to models without defensive suffixes. Additionally, the perplexity score of Gemma-7B decreased from 6.57 to 3.93 when applying the defensive suffix generated by openELM-270M. Furthermore, TruthfulQA evaluations demonstrate consistent improvements with Truthfulness scores increasing by up to 10\% across tested configurations. This approach significantly enhances the security of LLMs in critical applications without requiring extensive retraining. 

**Abstract (ZH)**: 大型语言模型（LLMs）在自然语言处理任务中表现出色。然而，这些模型仍然容易受到对抗性攻击的影响，轻微的输入扰动即可导致有害或误导性的输出。为此，我们设计了一种基于梯度的防御后缀生成算法，以增强LLMs的鲁棒性。通过在输入提示后面附加精心优化的防御后缀，该算法降低了对抗性影响的同时保留了模型的功能。为了增强对抗性理解，我们提出了一种新型的总损失函数（$L_{\text{total}}$），该函数结合了防御损失（$L_{\text{def}}$）和对抗损失（$L_{\text{adv}}$），以更有效地生成防御后缀。实验评估表明，该方法在开源LLM（如Gemma-7B、mistral-7B、Llama2-7B和Llama2-13B）上将攻击成功率（ASR）平均降低了11%。此外，当使用来自openELM-270M生成的防御后缀时，Gemma-7B的困惑度得分从6.57降低到3.93。进一步的TruthfulQA评估表明，在所有测试配置中，这种方法使真实性得分提高高达10%。这种方法在不需进行大量重新训练的情况下显著增强了LLMs在关键应用中的安全性。 

---
# Evaluation of LLM Vulnerabilities to Being Misused for Personalized Disinformation Generation 

**Title (ZH)**: LLM在个性化虚假信息生成方面被误用的漏洞评估 

**Authors**: Aneta Zugecova, Dominik Macko, Ivan Srba, Robert Moro, Jakub Kopal, Katarina Marcincinova, Matus Mesarcik  

**Link**: [PDF](https://arxiv.org/pdf/2412.13666)  

**Abstract**: The capabilities of recent large language models (LLMs) to generate high-quality content indistinguishable by humans from human-written texts rises many concerns regarding their misuse. Previous research has shown that LLMs can be effectively misused for generating disinformation news articles following predefined narratives. Their capabilities to generate personalized (in various aspects) content have also been evaluated and mostly found usable. However, a combination of personalization and disinformation abilities of LLMs has not been comprehensively studied yet. Such a dangerous combination should trigger integrated safety filters of the LLMs, if there are some. This study fills this gap by evaluation of vulnerabilities of recent open and closed LLMs, and their willingness to generate personalized disinformation news articles in English. We further explore whether the LLMs can reliably meta-evaluate the personalization quality and whether the personalization affects the generated-texts detectability. Our results demonstrate the need for stronger safety-filters and disclaimers, as those are not properly functioning in most of the evaluated LLMs. Additionally, our study revealed that the personalization actually reduces the safety-filter activations; thus effectively functioning as a jailbreak. Such behavior must be urgently addressed by LLM developers and service providers. 

**Abstract (ZH)**: 近年来大数据量的语言模型（LLMs）生成高质量、难以与人类撰写的文本区分开来的内容的能力引发了对其被误用的诸多担忧。先前的研究表明，LLMs可以有效用于按照预定义的叙述生成虚假信息新闻文章。此外，它们生成个性化（在各个方面）内容的能力也得到了评估，结果大多显示出一定的可用性。然而，将个性化能力和生成虚假信息的能力结合起来进行研究的综合性研究尚未全面开展。这样的危险组合应当触发LLMs的安全过滤器，如果有的话。本研究通过评估近期开源和封闭的LLMs的安全漏洞以及它们生成个性化虚假信息新闻文章的意愿，填补了这一空白，并使用英语进行了相关实验。我们进一步探讨了LLMs是否能够可靠地元评估个性化质量，以及个性化是否影响生成文本的可检测性。研究表明，需要加强更多的安全过滤器和免责声明，因为这些在大多数评估的LLMs中并未有效运行。此外，我们的研究揭示，个性化实际上降低了安全过滤器的激活程度；因此，有效运作的个性化充当了安全机制的“绕过”。这种行为必须引起LLMs开发人员和服务提供商的紧急关注。 

---
# LIFT: Improving Long Context Understanding Through Long Input Fine-Tuning 

**Title (ZH)**: LIFT：通过长输入微调提高长期上下文理解 

**Authors**: Yansheng Mao, Jiaqi Li, Fanxu Meng, Jing Xiong, Zilong Zheng, Muhan Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13626)  

**Abstract**: Long context understanding remains challenging for large language models due to their limited context windows. This paper introduces Long Input Fine-Tuning (LIFT) for long context modeling, a novel framework that enhances LLM performance on long-context tasks by adapting model parameters to the context at test time. LIFT enables efficient processing of lengthy inputs without the computational burden of offline long-context adaptation, and can improve the long-context capabilities of arbitrary short-context models. The framework is further enhanced by integrating in-context learning and pre-LIFT supervised fine-tuning. The combination of in-context learning and LIFT enables short-context models like Llama 3 to handle arbitrarily long contexts and consistently improves their performance on popular long-context benchmarks like LooGLE and LongBench. We also provide a comprehensive analysis of the strengths and limitations of LIFT on long context understanding, offering valuable directions for future research. 

**Abstract (ZH)**: 长上下文理解仍然是大型语言模型面临的挑战，主要是由于它们有限的上下文窗口。本文介绍了长输入微调（LIFT），这是一种新的框架，通过在测试时调整模型参数来增强模型在长上下文任务上的性能。LIFT 允模型高效处理长输入，而无需进行计算负担重的离线长上下文适应，并且可以增强任意短上下文模型的长上下文能力。该框架进一步通过整合上下文学习和预-LIFT 监督微调得到了增强。上下文学习与 LIFT 的结合使得像 Llama 3 这样的短上下文模型能够处理任意长的上下文，并在流行的长上下文基准测试如 LooGLE 和 LongBench 上持续改进其性能。我们还对 LIFT 在长上下文理解中的优势和局限性进行了全面分析，并为未来的研究提供了宝贵的指导方向。 

---
# Are LLMs Good Literature Review Writers? Evaluating the Literature Review Writing Ability of Large Language Models 

**Title (ZH)**: 大型语言模型是好的文献综述撰写者吗？评估大型语言模型的文献综述撰写能力 

**Authors**: Xuemei Tang, Xufeng Duan, Zhenguang G. Cai  

**Link**: [PDF](https://arxiv.org/pdf/2412.13612)  

**Abstract**: The literature review is a crucial form of academic writing that involves complex processes of literature collection, organization, and summarization. The emergence of large language models (LLMs) has introduced promising tools to automate these processes. However, their actual capabilities in writing comprehensive literature reviews remain underexplored, such as whether they can generate accurate and reliable references. To address this gap, we propose a framework to assess the literature review writing ability of LLMs automatically. We evaluate the performance of LLMs across three tasks: generating references, writing abstracts, and writing literature reviews. We employ external tools for a multidimensional evaluation, which includes assessing hallucination rates in references, semantic coverage, and factual consistency with human-written context. By analyzing the experimental results, we find that, despite advancements, even the most sophisticated models still cannot avoid generating hallucinated references. Additionally, different models exhibit varying performance in literature review writing across different disciplines. 

**Abstract (ZH)**: 文献综述是一种重要的学术写作形式，涉及文献的复杂收集、组织和总结过程。大型语言模型（LLMs）的出现引入了自动化这些过程的有力工具。然而，它们在撰写全面文献综述的实际能力仍然未被充分探索，例如它们是否能够生成准确可靠的参考文献。为解决这一问题，我们提出了一种框架，以自动评估LLMs的文献综述写作能力。我们通过三项任务来评估LLMs的表现：生成参考文献、撰写摘要和撰写文献综述。我们利用外部工具进行多维度的评估，其中包括评估参考文献中的虚构率、语义覆盖率以及与人类撰写背景的实证一致性。通过对实验结果的分析，我们发现，尽管技术取得了进步，甚至最复杂的模型也无法避免生成虚构的参考文献。此外，不同模型在不同学科的文献综述写作上表现出不同的性能。 

---
# Socio-Culturally Aware Evaluation Framework for LLM-Based Content Moderation 

**Title (ZH)**: 基于社会文化意识的评估框架：面向大语言模型驱动的内容审核 

**Authors**: Shanu Kumar, Gauri Kholkar, Saish Mendke, Anubhav Sadana, Parag Agrawal, Sandipan Dandapat  

**Link**: [PDF](https://arxiv.org/pdf/2412.13578)  

**Abstract**: With the growth of social media and large language models, content moderation has become crucial. Many existing datasets lack adequate representation of different groups, resulting in unreliable assessments. To tackle this, we propose a socio-culturally aware evaluation framework for LLM-driven content moderation and introduce a scalable method for creating diverse datasets using persona-based generation. Our analysis reveals that these datasets provide broader perspectives and pose greater challenges for LLMs than diversity-focused generation methods without personas. This challenge is especially pronounced in smaller LLMs, emphasizing the difficulties they encounter in moderating such diverse content. 

**Abstract (ZH)**: 随着社交媒体和大规模语言模型的兴起，内容审查变得至关重要。现有数据集在不同群体的代表性方面存在不足，导致评估可靠性较低。为解决这一问题，我们提出了一种社会文化意识较强的内容审查评估框架，并引入了一种基于人格生成的可扩展方法，用于创建多样化的数据集。我们的分析显示，这些数据集为大规模语言模型提供了更广泛的观点，并提出了更大的挑战，而这些挑战尤为显著地体现在较小规模的语言模型上，突显了它们在审查如此多样化内容时所面临的困难。 

---
# EscapeBench: Pushing Language Models to Think Outside the Box 

**Title (ZH)**: EscapeBench: 促使语言模型跳出常规思考 

**Authors**: Cheng Qian, Peixuan Han, Qinyu Luo, Bingxiang He, Xiusi Chen, Yuji Zhang, Hongyi Du, Jiarui Yao, Xiaocheng Yang, Denghui Zhang, Yunzhu Li, Heng Ji  

**Link**: [PDF](https://arxiv.org/pdf/2412.13549)  

**Abstract**: Language model agents excel in long-session planning and reasoning, but existing benchmarks primarily focus on goal-oriented tasks with explicit objectives, neglecting creative adaptation in unfamiliar environments. To address this, we introduce EscapeBench, a benchmark suite of room escape game environments designed to challenge agents with creative reasoning, unconventional tool use, and iterative problem-solving to uncover implicit goals. Our results show that current LM models, despite employing working memory and Chain-of-Thought reasoning, achieve only 15% average progress without hints, highlighting their limitations in creativity. To bridge this gap, we propose EscapeAgent, a framework designed to enhance creative reasoning through Foresight (innovative tool use) and Reflection (identifying unsolved tasks). Experiments show that EscapeAgent can execute action chains over 1,000 steps while maintaining logical coherence. It navigates and completes games with up to 40% fewer steps and hints, performs robustly across varying difficulty levels, and achieves higher action success rates with more efficient and innovative puzzle-solving strategies. All the data and codes are released. 

**Abstract (ZH)**: 语言模型代理在长会话规划和推理方面表现出色，但现有的基准测试主要集中在具有明确目标的任务上，忽视了在陌生环境中创造性适应的能力。为了解决这一问题，我们引入了EscapeBench，这是一套设计用于挑战代理进行创造性推理、非传统工具使用和迭代问题解决的房间逃脱游戏环境，以揭示隐含目标。我们的研究结果表明，尽管当前的语言模型使用了工作记忆和链式推理，但在没有提示的情况下平均仅完成15%的任务，这突出了它们在创造性方面的能力局限。为了弥合这一差距，我们提出了EscapeAgent框架，旨在通过展望（创新的工具使用）和反思（识别未解决问题）来增强创造性推理。实验结果表明，EscapeAgent可以在超过1000步的行动链中保持逻辑连贯性。它可以以最少40%的步骤和提示完成游戏，跨不同难度水平表现出稳健性，并通过更高效和创新的谜题解决策略实现更高的行动成功率。所有数据和代码均已发布。 

---
# Bridging the User-side Knowledge Gap in Knowledge-aware Recommendations with Large Language Models 

**Title (ZH)**: 使用大型语言模型弥合知识感知推荐中的用户侧知识差距 

**Authors**: Zheng Hu, Zhe Li, Ziyun Jiao, Satoshi Nakagawa, Jiawen Deng, Shimin Cai, Tao Zhou, Fuji Ren  

**Link**: [PDF](https://arxiv.org/pdf/2412.13544)  

**Abstract**: In recent years, knowledge graphs have been integrated into recommender systems as item-side auxiliary information, enhancing recommendation accuracy. However, constructing and integrating structural user-side knowledge remains a significant challenge due to the improper granularity and inherent scarcity of user-side features. Recent advancements in Large Language Models (LLMs) offer the potential to bridge this gap by leveraging their human behavior understanding and extensive real-world knowledge. Nevertheless, integrating LLM-generated information into recommender systems presents challenges, including the risk of noisy information and the need for additional knowledge transfer. In this paper, we propose an LLM-based user-side knowledge inference method alongside a carefully designed recommendation framework to address these challenges. Our approach employs LLMs to infer user interests based on historical behaviors, integrating this user-side information with item-side and collaborative data to construct a hybrid structure: the Collaborative Interest Knowledge Graph (CIKG). Furthermore, we propose a CIKG-based recommendation framework that includes a user interest reconstruction module and a cross-domain contrastive learning module to mitigate potential noise and facilitate knowledge transfer. We conduct extensive experiments on three real-world datasets to validate the effectiveness of our method. Our approach achieves state-of-the-art performance compared to competitive baselines, particularly for users with sparse interactions. 

**Abstract (ZH)**: 近年来，知识图谱已被整合到推荐系统中作为物品方面的辅助信息，从而提高推荐准确性。然而，由于用户方面特征的不当粒度和固有的稀疏性，构建和整合结构化用户方面知识依然是一个重大挑战。近年来大型语言模型（LLMs）的进步为解决这一问题提供了可能，通过利用它们对人类行为的理解以及广泛的实际世界知识。然而，将LLM生成的信息整合到推荐系统中仍然存在挑战，包括_noise信息的风险_和额外知识迁移的需求。在本文中，我们提出了一种基于LLM的用户方面知识推理方法，并设计了一个精心构建的推荐框架来应对这些挑战。我们的方法利用LLM根据历史行为推断用户兴趣，并将这种用户方面的信息与物品方面的数据和合作数据相结合，构建一种混合结构：交互兴趣知识图谱（CIKG）。此外，我们提出了一种基于CIKG的推荐框架，其中包括用户兴趣重建模块和跨域对比学习模块，以减轻潜在的噪声并对知识迁移进行促进。我们在三个真实世界的数据集上进行了广泛的实验以验证我们方法的有效性。我们的方法在与竞争基线方法的对比中实现了最先进的性能，特别是在交互稀疏的用户中表现尤为显著。 

---
# Large Language Model Enhanced Recommender Systems: Taxonomy, Trend, Application and Future 

**Title (ZH)**: 大型语言模型增强的推荐系统：分类、趋势、应用和未来 

**Authors**: Qidong Liu, Xiangyu Zhao, Yuhao Wang, Yejing Wang, Zijian Zhang, Yuqi Sun, Xiang Li, Maolin Wang, Pengyue Jia, Chong Chen, Wei Huang, Feng Tian  

**Link**: [PDF](https://arxiv.org/pdf/2412.13432)  

**Abstract**: Large Language Model (LLM) has transformative potential in various domains, including recommender systems (RS). There have been a handful of research that focuses on empowering the RS by LLM. However, previous efforts mainly focus on LLM as RS, which may face the challenge of intolerant inference costs by LLM. Recently, the integration of LLM into RS, known as LLM-Enhanced Recommender Systems (LLMERS), has garnered significant interest due to its potential to address latency and memory constraints in real-world applications. This paper presents a comprehensive survey of the latest research efforts aimed at leveraging LLM to enhance RS capabilities. We identify a critical shift in the field with the move towards incorporating LLM into the online system, notably by avoiding their use during inference. Our survey categorizes the existing LLMERS approaches into three primary types based on the component of the RS model being augmented: Knowledge Enhancement, Interaction Enhancement, and Model Enhancement. We provide an in-depth analysis of each category, discussing the methodologies, challenges, and contributions of recent studies. Furthermore, we highlight several promising research directions that could further advance the field of LLMERS. 

**Abstract (ZH)**: 大语言模型（LLM）在多个领域具有变革性潜力，包括推荐系统（RS）。已有少数研究专注于通过LLM增强RS。然而，先前的努力主要侧重于将LLM作为RS，这可能会面临LLM容忍性较低的推理成本挑战。最近，将LLM集成到RS中的做法，即LLM增强推荐系统（LLMERS），因有望解决实际应用中的延迟和内存限制问题而引起了广泛关注。本文对旨在利用LLM增强RS能力的最新研究进行了一篇全面综述。我们指出，随着研究领域转向将LLM集成到在线系统中，特别是避免在推理过程中使用LLM，出现了关键性的转变。我们的综述将现有的LLMERS方法划分为三大类，根据增强RS模型的组件分别为知识增强、交互增强和模型增强。我们对每一类进行了深入分析，讨论了近期研究的方法、挑战和贡献。此外，我们还指出了几条有前景的研究方向，这些方向可能会进一步推动LLMERS领域的发展。 

---
# Unveiling the Secret Recipe: A Guide For Supervised Fine-Tuning Small LLMs 

**Title (ZH)**: 揭开秘方的面纱：一种监督微调小型语言模型的指南 

**Authors**: Aldo Pareja, Nikhil Shivakumar Nayak, Hao Wang, Krishnateja Killamsetty, Shivchander Sudalairaj, Wenlong Zhao, Seungwook Han, Abhishek Bhandwaldar, Guangxuan Xu, Kai Xu, Ligong Han, Luke Inglis, Akash Srivastava  

**Link**: [PDF](https://arxiv.org/pdf/2412.13337)  

**Abstract**: The rise of large language models (LLMs) has created a significant disparity: industrial research labs with their computational resources, expert teams, and advanced infrastructures, can effectively fine-tune LLMs, while individual developers and small organizations face barriers due to limited resources. In this paper, we aim to bridge this gap by presenting a comprehensive study on supervised fine-tuning of LLMs using instruction-tuning datasets spanning diverse knowledge domains and skills. We focus on small-sized LLMs (3B to 7B parameters) for their cost-efficiency and accessibility. We explore various training configurations and strategies across four open-source pre-trained models. We provide detailed documentation of these configurations, revealing findings that challenge several common training practices, including hyperparameter recommendations from TULU and phased training recommended by Orca. Key insights from our work include: (i) larger batch sizes paired with lower learning rates lead to improved model performance on benchmarks such as MMLU, MTBench, and Open LLM Leaderboard; (ii) early-stage training dynamics, such as lower gradient norms and higher loss values, are strong indicators of better final model performance, enabling early termination of sub-optimal runs and significant computational savings; (iii) through a thorough exploration of hyperparameters like warmup steps and learning rate schedules, we provide guidance for practitioners and find that certain simplifications do not compromise performance; and (iv) we observed no significant difference in performance between phased and stacked training strategies, but stacked training is simpler and more sample efficient. With these findings holding robustly across datasets and models, we hope this study serves as a guide for practitioners fine-tuning small LLMs and promotes a more inclusive environment for LLM research. 

**Abstract (ZH)**: 大型语言模型（LLMs）的兴起创造了一个显著的差距：工业研究实验室凭借其计算资源、专家团队和高级基础设施，能够有效地调优LLMs，而个体开发者和小型组织因资源有限而面临障碍。本文旨在弥合这一差距，通过对横跨不同知识领域和技能的指令调优数据集进行监督调优研究，开展全面的调研。我们专注于小规模LLMs（3B到7B参数），因其成本效益和易于访问。我们探索了在四个开源预训练模型上使用的各种训练配置和策略。我们详细记录了这些配置，揭示了一些挑战常见训练实践的研究发现，包括TULU推荐的超参数和Orca推荐的分阶段训练。本文的关键洞察包括：（i）较大的批次大小配以较低的学习率在多模态（MMLU）、MTBench和开放LLM排行榜等基准测试中提高了模型性能；（ii）早期训练动态，如较低的梯度范数和较高的损失值，是更好的最终模型性能的强烈指标，这有助于提前终止不理想运行并节省大量计算资源；（iii）通过彻底探索诸如预热步数和学习率调度等超参数，我们为从业者提供了指导，并发现某些简化措施不会影响性能；（iv）我们观察到分阶段和堆叠训练策略在性能上没有显著差异，但堆叠训练更简单且更具样本效率。基于这些研究发现，在不同数据集和模型上的表现都十分稳健，我们希望这项研究能为调优小型LLM的从业者提供指南，并促进LLM研究的包容性环境。 

---
# TheAgentCompany: Benchmarking LLM Agents on Consequential Real World Tasks 

**Title (ZH)**: 《AgentCompany：评估大型语言模型代理在具重要性的现实任务上的表现》 

**Authors**: Frank F. Xu, Yufan Song, Boxuan Li, Yuxuan Tang, Kritanjali Jain, Mengxue Bao, Zora Z. Wang, Xuhui Zhou, Zhitong Guo, Murong Cao, Mingyang Yang, Hao Yang Lu, Amaad Martin, Zhe Su, Leander Maben, Raj Mehta, Wayne Chi, Lawrence Jang, Yiqing Xie, Shuyan Zhou, Graham Neubig  

**Link**: [PDF](https://arxiv.org/pdf/2412.14161)  

**Abstract**: We interact with computers on an everyday basis, be it in everyday life or work, and many aspects of work can be done entirely with access to a computer and the Internet. At the same time, thanks to improvements in large language models (LLMs), there has also been a rapid development in AI agents that interact with and affect change in their surrounding environments. But how performant are AI agents at helping to accelerate or even autonomously perform work-related tasks? The answer to this question has important implications for both industry looking to adopt AI into their workflows, and for economic policy to understand the effects that adoption of AI may have on the labor market. To measure the progress of these LLM agents' performance on performing real-world professional tasks, in this paper, we introduce TheAgentCompany, an extensible benchmark for evaluating AI agents that interact with the world in similar ways to those of a digital worker: by browsing the Web, writing code, running programs, and communicating with other coworkers. We build a self-contained environment with internal web sites and data that mimics a small software company environment, and create a variety of tasks that may be performed by workers in such a company. We test baseline agents powered by both closed API-based and open-weights language models (LMs), and find that with the most competitive agent, 24% of the tasks can be completed autonomously. This paints a nuanced picture on task automation with LM agents -- in a setting simulating a real workplace, a good portion of simpler tasks could be solved autonomously, but more difficult long-horizon tasks are still beyond the reach of current systems. 

**Abstract (ZH)**: 我们每天都在与计算机进行交互，无论是在日常生活中还是工作中，许多工作都可以通过计算机和互联网来完成。与此同时，由于大型语言模型（LLMs）的进步，也出现了一批可以与环境互动并影响环境变化的AI代理。那么这些AI代理在加速甚至自主完成工作相关任务方面表现如何呢？这个问题的答案对于希望将AI应用于工作流程的行业以及了解AI采用对劳动力市场可能产生的影响的经济政策都具有重要意义。为了评估这些能够以类似于数字工人方式与世界互动的LLM代理在执行真实世界专业任务方面的表现，本文引入了TheAgentCompany，这是一个可扩展的基准测试，用于评估能够以类似数字工人方式与世界进行互动的AI代理。我们构建了一个自包含的环境，其中包括模拟小型软件公司环境的内部网站和数据，并创建了各种任务，这些任务可能是该公司员工可以执行的任务。我们测试了基于封闭API和开源权重语言模型（LMs）的基线代理，并发现使用最优秀的代理，有24%的任务可以自主完成。这为我们展示了使用LM代理进行任务自动化的复杂性——在模拟实际工作场所的环境中，许多简单任务可以自行解决，但更复杂、长期的任务仍然超出了当前系统的处理范围。 

---
# Hansel: Output Length Controlling Framework for Large Language Models 

**Title (ZH)**: 汉塞尔：大型语言模型的输出长度控制框架 

**Authors**: Seoha Song, Junhyun Lee, Hyeonmok Ko  

**Link**: [PDF](https://arxiv.org/pdf/2412.14033)  

**Abstract**: Despite the great success of large language models (LLMs), efficiently controlling the length of the output sequence still remains a challenge. In this paper, we propose Hansel, an efficient framework for length control in LLMs without affecting its generation ability. Hansel utilizes periodically outputted hidden special tokens to keep track of the remaining target length of the output sequence. Together with techniques to avoid abrupt termination of the output, this seemingly simple method proved to be efficient and versatile, while not harming the coherency and fluency of the generated text. The framework can be applied to any pre-trained LLMs during the finetuning stage of the model, regardless of its original positional encoding method. We demonstrate this by finetuning four different LLMs with Hansel and show that the mean absolute error of the output sequence decreases significantly in every model and dataset compared to the prompt-based length control finetuning. Moreover, the framework showed a substantially improved ability to extrapolate to target lengths unseen during finetuning, such as long dialog responses or extremely short summaries. This indicates that the model learns the general means of length control, rather than learning to match output lengths to those seen during training. 

**Abstract (ZH)**: 尽管大型语言模型（LLMs）取得了巨大的成功，有效地控制输出序列的长度仍然是一项挑战。本文提出了一种名为Hansel的高效框架，可以在不损害LLMs生成能力的情况下控制其输出长度。Hansel利用周期性输出的隐藏特殊标记来跟踪输出序列剩余的目标长度。结合避免输出突然终止的技术，这种方法看似简单，但证明了其高效性和灵活性，同时保持了生成文本的连贯性和流畅性。该框架可以在模型的微调阶段应用于任何预训练的LLMs，而不受其原始位置编码方法的限制。我们通过使用Hansel微调四个不同的LLMs进行了演示，并展示了在每个模型和数据集中，输出序列的绝对误差显著减少，这表明与基于提示的长度控制微调相比，该框架能够显著提高模型将输出长度外推到微调时未见过的目标长度（如长对话响应或极短的摘要）的能力。这表明模型学会了长度控制的一般方法，而不是仅仅学习匹配特定的输出长度。 

---
# Cracking the Code of Hallucination in LVLMs with Vision-aware Head Divergence 

**Title (ZH)**: 基于视觉aware头部发散的LVLMs幻觉机制破解 

**Authors**: Jinghan He, Kuan Zhu, Haiyun Guo, Junfeng Fang, Zhenglin Hua, Yuheng Jia, Ming Tang, Tat-Seng Chua, Jinqiao Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13949)  

**Abstract**: Large vision-language models (LVLMs) have made substantial progress in integrating large language models (LLMs) with visual inputs, enabling advanced multimodal reasoning. Despite their success, a persistent challenge is hallucination-where generated text fails to accurately reflect visual content-undermining both accuracy and reliability. Existing methods focus on alignment training or decoding refinements but primarily address symptoms at the generation stage without probing the underlying causes. In this work, we investigate the internal mechanisms driving hallucination in LVLMs, with an emphasis on the multi-head attention module. Specifically, we introduce Vision-aware Head Divergence (VHD), a metric that quantifies the sensitivity of attention head outputs to visual context. Based on this, our findings reveal the presence of vision-aware attention heads that are more attuned to visual information; however, the model's overreliance on its prior language patterns is closely related to hallucinations. Building on these insights, we propose Vision-aware Head Reinforcement (VHR), a training-free approach to mitigate hallucination by enhancing the role of vision-aware attention heads. Extensive experiments demonstrate that our method achieves superior performance compared to state-of-the-art approaches in mitigating hallucinations, while maintaining high efficiency with negligible additional time overhead. 

**Abstract (ZH)**: 大型多模态视觉-语言模型（LVLMs）在将大型语言模型（LLMs）与视觉输入相结合方面取得了显著进展，从而实现高级跨模态推理。尽管取得了成功，但持续存在的挑战是幻觉——生成的文本未能准确反映视觉内容，这直接影响了准确性和可靠性。现有方法主要集中在对齐训练或解码改进，但主要是针对生成阶段的症状，而没有探查背后的根源。在本研究中，我们调查了LVLMs中导致幻觉的内部机制，并特别关注了多头注意力模块。具体来说，我们引入了视觉感知头 divergences（VHD），这是一种度量视觉上下文对注意力头输出敏感性的指标。基于此，我们的研究结果揭示了对视觉信息更敏感的视觉感知注意力头的存在；然而，模型过度依赖其先验语言模式与幻觉密切相关。基于这些见解，我们提出了一种无需训练的方法——视觉感知头强化（VHR），通过增强视觉感知注意力头的作用来减轻幻觉。大量实验结果表明，与当前最先进的方法相比，我们的方法在减轻幻觉方面具有更优越的性能，同时保持了高效性，几乎无需额外的时间开销。 

---
# A Rose by Any Other Name: LLM-Generated Explanations Are Good Proxies for Human Explanations to Collect Label Distributions on NLI 

**Title (ZH)**: 任意名称的一朵玫瑰：由大规模语言模型生成的解释是收集自然语言推理数据集中标签分布的人类解释的良好代理 

**Authors**: Beiduo Chen, Siyao Peng, Anna Korhonen, Barbara Plank  

**Link**: [PDF](https://arxiv.org/pdf/2412.13942)  

**Abstract**: Disagreement in human labeling is ubiquitous, and can be captured in human judgment distributions (HJDs). Recent research has shown that explanations provide valuable information for understanding human label variation (HLV) and large language models (LLMs) can approximate HJD from a few human-provided label-explanation pairs. However, collecting explanations for every label is still time-consuming. This paper examines whether LLMs can be used to replace humans in generating explanations for approximating HJD. Specifically, we use LLMs as annotators to generate model explanations for a few given human labels. We test ways to obtain and combine these label-explanations with the goal to approximate human judgment distribution. We further compare the resulting human with model-generated explanations, and test automatic and human explanation selection. Our experiments show that LLM explanations are promising for NLI: to estimate HJD, generated explanations yield comparable results to human's when provided with human labels. Importantly, our results generalize from datasets with human explanations to i) datasets where they are not available and ii) challenging out-of-distribution test sets. 

**Abstract (ZH)**: 人类标注中的分歧是普遍存在的，可以体现在人类判断分布（HJD）中。近期的研究表明，解释提供了理解人类标注变异（HLV）和大规模语言模型（LLMs）可以从少量的人类标注-解释对中近似HJD的重要信息。然而，为每个标注收集解释仍然耗费时间。本文探讨了LLMs是否可以替代人类生成解释以近似HJD。具体而言，我们使用LLMs作为注释者，为给定的少量人类标注生成模型解释。我们测试获取和结合这些标注-解释的方法，以期近似人类判断分布。进一步地，我们将人类与模型生成的解释进行比较，并测试自动选择和人工选择解释的方法。我们的实验表明，在NLI任务中，生成的解释对于估计HJD而言是具有前景的：当提供人类标注时，生成的解释能获得与人类相当的结果。重要的是，我们的结果不仅适用于有人类解释的数据集，还适用于i) 没有人类解释的数据集以及ii) 具有挑战性的分布外测试集。 

---
# Physics Reasoner: Knowledge-Augmented Reasoning for Solving Physics Problems with Large Language Models 

**Title (ZH)**: 物理推理器：知识增强的物理问题推理方法用于大型语言模型解决物理问题 

**Authors**: Xinyu Pang, Ruixin Hong, Zhanke Zhou, Fangrui Lv, Xinwei Yang, Zhilong Liang, Bo Han, Changshui Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2412.13791)  

**Abstract**: Physics problems constitute a significant aspect of reasoning, necessitating complicated reasoning ability and abundant physics knowledge. However, existing large language models (LLMs) frequently fail due to a lack of knowledge or incorrect knowledge application. To mitigate these issues, we propose Physics Reasoner, a knowledge-augmented framework to solve physics problems with LLMs. Specifically, the proposed framework constructs a comprehensive formula set to provide explicit physics knowledge and utilizes checklists containing detailed instructions to guide effective knowledge application. Namely, given a physics problem, Physics Reasoner solves it through three stages: problem analysis, formula retrieval, and guided reasoning. During the process, checklists are employed to enhance LLMs' self-improvement in the analysis and reasoning stages. Empirically, Physics Reasoner mitigates the issues of insufficient knowledge and incorrect application, achieving state-of-the-art performance on SciBench with an average accuracy improvement of 5.8%. 

**Abstract (ZH)**: 物理学问题构成了推理的重要方面，需要复杂的推理能力和丰富的物理学知识。然而，现有的大规模语言模型（LLMs）往往因为缺乏知识或错误的知识应用而失败。为了缓解这些问题，我们提出了一种知识增强框架——Physics Reasoner，该框架利用LLMs解决物理学问题。具体而言，该框架构建了一个全面的公式集，以提供显式的物理学知识，并利用包含详细指导说明的清单来指导有效知识的应用。简而言之，给定一个物理学问题，Physics Reasoner 通过三个阶段进行解决：问题分析、公式检索和引导推理。在这一过程中，清单被用于在分析和推理阶段增强LLMs的自我提升能力。实验结果显示，Physics Reasoner 减轻了知识不足和错误应用的问题，在SciBench上的性能达到了最先进的水平，平均准确率提高了5.8%。 

---
# PsyDT: Using LLMs to Construct the Digital Twin of Psychological Counselor with Personalized Counseling Style for Psychological Counseling 

**Title (ZH)**: PsyDT：利用大型语言模型构建个性化心理咨询风格的心理咨询数字孪生系统 

**Authors**: Haojie Xie, Yirong Chen, Xiaofen Xing, Jingkai Lin, Xiangmin Xu  

**Link**: [PDF](https://arxiv.org/pdf/2412.13660)  

**Abstract**: Currently, large language models (LLMs) have made significant progress in the field of psychological counseling. However, existing mental health LLMs overlook a critical issue where they do not consider the fact that different psychological counselors exhibit different personal styles, including linguistic style and therapy techniques, etc. As a result, these LLMs fail to satisfy the individual needs of clients who seek different counseling styles. To help bridge this gap, we propose PsyDT, a novel framework using LLMs to construct the Digital Twin of Psychological counselor with personalized counseling style. Compared to the time-consuming and costly approach of collecting a large number of real-world counseling cases to create a specific counselor's digital twin, our framework offers a faster and more cost-effective solution. To construct PsyDT, we utilize dynamic one-shot learning by using GPT-4 to capture counselor's unique counseling style, mainly focusing on linguistic style and therapy techniques. Subsequently, using existing single-turn long-text dialogues with client's questions, GPT-4 is guided to synthesize multi-turn dialogues of specific counselor. Finally, we fine-tune the LLMs on the synthetic dataset, PsyDTCorpus, to achieve the digital twin of psychological counselor with personalized counseling style. Experimental results indicate that our proposed PsyDT framework can synthesize multi-turn dialogues that closely resemble real-world counseling cases and demonstrate better performance compared to other baselines, thereby show that our framework can effectively construct the digital twin of psychological counselor with a specific counseling style. 

**Abstract (ZH)**: 目前，大型语言模型（LLMs）在心理辅导领域取得了显著进展。然而，现有的心理健康LLMs忽视了一个关键问题，即它们没有考虑到不同的心理辅导员具备不同的个人风格，包括语言风格和治疗方法等。因此，这些LKM无法满足寻求不同咨询风格的客户的个体需求。为弥补这一差距，我们提出PsyDT，一种使用LLMs构建个性化心理辅导员数字孪生的新框架。与收集大量真实咨询案例以创建特定心理辅导员数字孪生的耗时且成本高昂的方法相比，我们提出的框架提供了一种更快且更具成本效益的解决方案。为了构建PsyDT，我们利用动态单次学习，使用GPT-4捕获心理辅导员的独特咨询风格，主要集中在语言风格和治疗方法上。随后，利用现有的一轮多文本对话和客户的提问，GPT-4被引导合成特定心理辅导员的多轮对话。最后，我们在合成数据集PsyDTCorpus上对LLMs进行微调，以实现具有个性化咨询风格的心理辅导员数字孪生。实验结果表明，我们提出的PsyDT框架能够合成高度类似于真实咨询案例的多轮对话，并且在与其他基线方法的比较中表现出更好的性能，从而证明我们的框架能够有效构建具有特定咨询风格的心理辅导员数字孪生。 

---
# Beyond Outcomes: Transparent Assessment of LLM Reasoning in Games 

**Title (ZH)**: 超越结果：透明评估大规模语言模型在游戏中的推理能力 

**Authors**: Wenye Lin, Jonathan Roberts, Yunhan Yang, Samuel Albanie, Zongqing Lu, Kai Han  

**Link**: [PDF](https://arxiv.org/pdf/2412.13602)  

**Abstract**: Large Language Models (LLMs) are increasingly deployed in real-world applications that demand complex reasoning. To track progress, robust benchmarks are required to evaluate their capabilities beyond superficial pattern recognition. However, current LLM reasoning benchmarks often face challenges such as insufficient interpretability, performance saturation or data contamination. To address these challenges, we introduce GAMEBoT, a gaming arena designed for rigorous and transparent assessment of LLM reasoning capabilities. GAMEBoT decomposes complex reasoning in games into predefined modular subproblems. This decomposition allows us to design a suite of Chain-of-Thought (CoT) prompts that leverage domain knowledge to guide LLMs in addressing these subproblems before action selection. Furthermore, we develop a suite of rule-based algorithms to generate ground truth for these subproblems, enabling rigorous validation of the LLMs' intermediate reasoning steps. This approach facilitates evaluation of both the quality of final actions and the accuracy of the underlying reasoning process. GAMEBoT also naturally alleviates the risk of data contamination through dynamic games and head-to-head LLM competitions. We benchmark 17 prominent LLMs across eight games, encompassing various strategic abilities and game characteristics. Our results suggest that GAMEBoT presents a significant challenge, even when LLMs are provided with detailed CoT prompts. Project page: \url{this https URL} 

**Abstract (ZH)**: 大规模语言模型（LLMs）越来越多地应用于需要复杂推理的实际应用场景中。为了跟踪进展，需要建立稳健的基准测试，以评估它们超越表面模式识别的能力。然而，当前的LLM推理基准测试常常面临不可解释性不足、性能饱和或数据污染等挑战。为了解决这些挑战，我们引入了GAMEBoT，这是一种旨在进行严格和透明评估LLM推理能力的游戏竞技场。GAMEBoT将游戏中复杂推理问题分解为预定义的模块化子问题。这种分解使我们能够设计一系列基于推理链（Chain-of-Thought, CoT）的提示，利用领域知识引导LLM分别解决这些子问题，然后进行行动选择。此外，我们还开发了一系列基于规则的算法来生成这些子问题的真相标准，从而实现对LLM中间推理步骤的严格验证。这种方法有助于评估最终行动的质量以及底层推理过程的准确性。通过动态游戏和LLM之间的对抗比赛，GAMEBoT自然地减轻了数据污染的风险。我们在八款游戏中评估了17种知名LLM，涵盖了各种战略能力和游戏特性。我们的结果显示，即使提供详细的CoT提示，GAMEBoT仍然是一个显著的挑战。项目页面：[这个链接](this https URL) 

---
# EvoWiki: Evaluating LLMs on Evolving Knowledge 

**Title (ZH)**: EvoWiki：评估LLM在不断演变的知识上的表现 

**Authors**: Wei Tang, Yixin Cao, Yang Deng, Jiahao Ying, Bo Wang, Yizhe Yang, Yuyue Zhao, Qi Zhang, Xuanjing Huang, Yugang Jiang, Yong Liao  

**Link**: [PDF](https://arxiv.org/pdf/2412.13582)  

**Abstract**: Knowledge utilization is a critical aspect of LLMs, and understanding how they adapt to evolving knowledge is essential for their effective deployment. However, existing benchmarks are predominantly static, failing to capture the evolving nature of LLMs and knowledge, leading to inaccuracies and vulnerabilities such as contamination. In this paper, we introduce EvoWiki, an evolving dataset designed to reflect knowledge evolution by categorizing information into stable, evolved, and uncharted states. EvoWiki is fully auto-updatable, enabling precise evaluation of continuously changing knowledge and newly released LLMs. Through experiments with Retrieval-Augmented Generation (RAG) and Contunual Learning (CL), we evaluate how effectively LLMs adapt to evolving knowledge. Our results indicate that current models often struggle with evolved knowledge, frequently providing outdated or incorrect responses. Moreover, the dataset highlights a synergistic effect between RAG and CL, demonstrating their potential to better adapt to evolving knowledge. EvoWiki provides a robust benchmark for advancing future research on the knowledge evolution capabilities of large language models. 

**Abstract (ZH)**: 知识利用是大语言模型（LLM）的关键方面，理解它们如何适应不断演变的知识对其实效部署至关重要。然而，现有基准大多是静态的，无法捕捉LLM和知识的演变性质，导致不准确性和漏洞，如污染。本文中，我们介绍了EvoWiki，这是一个不断演变的数据集，旨在通过将信息分类为稳定状态、演变状态和未探索状态来反映知识的演变。EvoWiki完全可自动更新，使得能够对不断变化的知识和新发布的LLM进行精确评估。通过使用检索增强生成（RAG）和持续学习（CL）进行实验，我们评估了LLM如何有效地适应不断演变的知识。我们的结果显示，当前模型在处理演变知识时常常遇到困难，经常提供过时或错误的响应。此外，该数据集突显了RAG与CL之间协同作用的效果，证明了它们在适应不断演变的知识方面的潜力。EvoWiki为推进对大型语言模型知识演变能力的研究提供了稳健的基准。 

---
# MetaRuleGPT: Recursive Numerical Reasoning of Language Models Trained with Simple Rules 

**Title (ZH)**: MetaRuleGPT：基于简单规则训练的语言模型的递归数值推理 

**Authors**: Kejie Chen, Lin Wang, Qinghai Zhang, Renjun Xu  

**Link**: [PDF](https://arxiv.org/pdf/2412.13536)  

**Abstract**: Recent studies have highlighted the limitations of large language models in mathematical reasoning, particularly their inability to capture the underlying logic. Inspired by meta-learning, we propose that models should acquire not only task-specific knowledge but also transferable problem-solving skills. We introduce MetaRuleGPT, a novel Transformer-based architecture that performs precise numerical calculations and complex logical operations by learning and combining different rules. In contrast with traditional training sets, which are heavily composed of massive raw instance data, MetaRuleGPT is pre-trained on much less abstract datasets containing basic, compound, and iterative rules for mathematical reasoning. Extensive experimental results demonstrate MetaRuleGPT can mimic human's rule-following capabilities, break down complexity, and iteratively derive accurate results for complex mathematical problems. These findings prove the potential of rule learning to enhance the numerical reasoning abilities of language models. 

**Abstract (ZH)**: 近年来的研究凸显了大语言模型在数学推理方面的局限性，尤其是它们难以捕捉到基本的逻辑结构。受元学习的启发，我们提出模型不仅应获得任务特定的知识，还应掌握可迁移的问题解决技能。我们引入了MetaRuleGPT，这是一种新型的基于Transformer的架构，通过学习和组合不同的规则来进行精确的数值计算和复杂的逻辑操作。与传统训练集主要基于大量原始实例数据不同，MetaRuleGPT是在包含数学推理所需的基本、复合和迭代规则的较少抽象的数据集上进行预训练的。广泛的实验证据表明，MetaRuleGPT能够模拟人类遵循规则的能力，分解复杂性，并逐步推导出复杂数学问题的准确结果。这些发现证明了规则学习在提升语言模型数值推理能力方面具有潜在的价值。 

---
# An Automated Explainable Educational Assessment System Built on LLMs 

**Title (ZH)**: 基于大语言模型的自动化可解释性教育评估系统 

**Authors**: Jiazheng Li, Artem Bobrov, David West, Cesare Aloisi, Yulan He  

**Link**: [PDF](https://arxiv.org/pdf/2412.13381)  

**Abstract**: In this demo, we present AERA Chat, an automated and explainable educational assessment system designed for interactive and visual evaluations of student responses. This system leverages large language models (LLMs) to generate automated marking and rationale explanations, addressing the challenge of limited explainability in automated educational assessment and the high costs associated with annotation. Our system allows users to input questions and student answers, providing educators and researchers with insights into assessment accuracy and the quality of LLM-assessed rationales. Additionally, it offers advanced visualization and robust evaluation tools, enhancing the usability for educational assessment and facilitating efficient rationale verification. Our demo video can be found at this https URL. 

**Abstract (ZH)**: 在本演示中，我们介绍了AERA Chat，这是一种自动且可解释的教育评估系统，旨在实现学生回答的交互性和可视化评估。该系统利用大规模语言模型（LLMs）生成自动评分和理由解释，解决了自动教育评估中解释性不足的问题，以及注解的高成本问题。我们的系统允许用户输入问题和学生答案，为教育者和研究者提供了关于评估准确性和LLM评估理由质量的见解。此外，它还提供了高级可视化和强大的评估工具，提升了教育评估的可用性，并促进了高效的理由验证。欲了解更多详情，您可以查看我们的演示视频，网址为：[这个链接]。 

---
# Extending LLMs to New Languages: A Case Study of Llama and Persian Adaptation 

**Title (ZH)**: 将大语言模型扩展到新语言：关于Llamaa和波斯语适应的案例研究

注释：
1. "Llamaa" 应该是一个特定的模型名称，为了保持术语的一致性，这里保持不变。
2. "波斯语" 是“Persian”的中文对应词。 

**Authors**: Samin Mahdizadeh Sani, Pouya Sadeghi, Thuy-Trang Vu, Yadollah Yaghoobzadeh, Gholamreza Haffari  

**Link**: [PDF](https://arxiv.org/pdf/2412.13375)  

**Abstract**: Large language models (LLMs) have made great progress in classification and text generation tasks. However, they are mainly trained on English data and often struggle with low-resource languages. In this study, we explore adding a new language, i.e., Persian, to Llama (a model with a limited understanding of Persian) using parameter-efficient fine-tuning. We employ a multi-stage approach involving pretraining on monolingual Persian data, aligning representations through bilingual pretraining and instruction datasets, and instruction-tuning with task-specific datasets. We evaluate the model's performance at each stage on generation and classification tasks. Our findings suggest that incorporating the Persian language, through bilingual data alignment, can enhance classification accuracy for Persian tasks, with no adverse impact and sometimes even improvements on English tasks. Additionally, the results highlight the model's initial strength as a critical factor when working with limited training data, with cross-lingual alignment offering minimal benefits for the low-resource language. Knowledge transfer from English to Persian has a marginal effect, primarily benefiting simple classification tasks. 

**Abstract (ZH)**: 大规模语言模型（LLMs）在分类和文本生成任务中取得了显著进展。然而，这些模型主要是在英语数据上进行训练，往往对低资源语言表现出色能力不足。在本研究中，我们探索将一种新语言（即波斯语）添加到Llama（一种对波斯语理解有限的模型）的方法，使用参数高效微调。我们采用多阶段方法，包括在单语波斯语数据上进行预训练、通过双语预训练和指令数据集对表示进行对齐，以及针对特定任务的数据集进行指令微调。我们在生成任务和分类任务中分别评估模型在每个阶段的表现。我们的研究结果表明，通过双语数据对齐引入波斯语可以提高波斯语任务的分类准确性，而且在某些情况下甚至会提升英语任务的表现，但对低资源语言的影响较小。当使用有限的训练数据时，模型的初始优势是一个关键因素，跨语言对齐对其提供的增益有限。从英语到波斯语的知识迁移对分类任务有一定的影响，但对于简化任务表现更为显著。 

---
# Hint Marginalization for Improved Reasoning in Large Language Models 

**Title (ZH)**: 用于改进大型语言模型推理的提示边际化方法 

**Authors**: Soumyasundar Pal, Didier Chételat, Yingxue Zhang, Mark Coates  

**Link**: [PDF](https://arxiv.org/pdf/2412.13292)  

**Abstract**: Large Language Models (LLMs) have exhibited an impressive capability to perform reasoning tasks, especially if they are encouraged to generate a sequence of intermediate steps. Reasoning performance can be improved by suitably combining multiple LLM responses, generated either in parallel in a single query, or via sequential interactions with LLMs throughout the reasoning process. Existing strategies for combination, such as self-consistency and progressive-hint-prompting, make inefficient usage of the LLM responses. We present Hint Marginalization, a novel and principled algorithmic framework to enhance the reasoning capabilities of LLMs. Our approach can be viewed as an iterative sampling strategy for forming a Monte Carlo approximation of an underlying distribution of answers, with the goal of identifying the mode the most likely answer. Empirical evaluation on several benchmark datasets for arithmetic reasoning demonstrates the superiority of the proposed approach. 

**Abstract (ZH)**: 大型语言模型（LLMs）在执行推理任务方面表现出色，尤其是在被鼓励生成一系列中间步骤的情况下。通过适当结合多个LLM的响应，可以提高推理性能，这些响应可以在单个查询中并行生成，或者在推理过程中通过与LLM的序列交互生成。现有的组合策略，如自我一致性和平行提示提示，未能充分利用LLM的响应。我们提出了一种新颖且原理性的算法框架——提示边缘化，以增强LLMs的推理能力。我们的方法可以被视为一种迭代采样策略，用于形成底层答案分布的蒙特卡洛近似，目标是识别最 likely的答案模式。在几个算术推理基准数据集上的实证评估表明，所提出的方法优于现有方法。 

---
# Information-Theoretic Generative Clustering of Documents 

**Title (ZH)**: 信息论生成聚类文档方法 

**Authors**: Xin Du, Kumiko Tanaka-Ishii  

**Link**: [PDF](https://arxiv.org/pdf/2412.13534)  

**Abstract**: We present {\em generative clustering} (GC) for clustering a set of documents, $\mathrm{X}$, by using texts $\mathrm{Y}$ generated by large language models (LLMs) instead of by clustering the original documents $\mathrm{X}$. Because LLMs provide probability distributions, the similarity between two documents can be rigorously defined in an information-theoretic manner by the KL divergence. We also propose a natural, novel clustering algorithm by using importance sampling. We show that GC achieves the state-of-the-art performance, outperforming any previous clustering method often by a large margin. Furthermore, we show an application to generative document retrieval in which documents are indexed via hierarchical clustering and our method improves the retrieval accuracy. 

**Abstract (ZH)**: 我们提出了一种生成聚类（Generative Clustering, GC）的方法，通过使用大型语言模型（LLMs）生成的文本集合$\mathrm{Y}$进行文档聚类，而不是直接对原始文档集合$\mathrm{X}$进行聚类。由于大型语言模型提供了概率分布，两份文档之间的相似度可以以信息论的方式通过KL散度严格定义。此外，我们还提出了一种基于重要性采样的新颖聚类算法。实验结果显示，GC方法达到最先进的性能，通常在性能上显著超越了之前的任何聚类方法。此外，我们展示了生成式文档检索的应用，其中文档通过层次聚类进行索引，我们的方法可以提高检索准确性。 

---
# Boosting LLM-based Relevance Modeling with Distribution-Aware Robust Learning 

**Title (ZH)**: 基于分布意识稳健学习的LLM驱动相关性建模增强 

**Authors**: Hong Liu, Saisai Gong, Yixin Ji, Kaixin Wu, Jia Xu, Jinjie Gu  

**Link**: [PDF](https://arxiv.org/pdf/2412.12504)  

**Abstract**: With the rapid advancement of pre-trained large language models (LLMs), recent endeavors have leveraged the capabilities of LLMs in relevance modeling, resulting in enhanced performance. This is usually done through the process of fine-tuning LLMs on specifically annotated datasets to determine the relevance between queries and items. However, there are two limitations when LLMs are naively employed for relevance modeling through fine-tuning and inference. First, it is not inherently efficient for performing nuanced tasks beyond simple yes or no answers, such as assessing search relevance. It may therefore tend to be overconfident and struggle to distinguish fine-grained degrees of relevance (e.g., strong relevance, weak relevance, irrelevance) used in search engines. Second, it exhibits significant performance degradation when confronted with data distribution shift in real-world scenarios. In this paper, we propose a novel Distribution-Aware Robust Learning framework (DaRL) for relevance modeling in Alipay Search. Specifically, we design an effective loss function to enhance the discriminability of LLM-based relevance modeling across various fine-grained degrees of query-item relevance. To improve the generalizability of LLM-based relevance modeling, we first propose the Distribution-Aware Sample Augmentation (DASA) module. This module utilizes out-of-distribution (OOD) detection techniques to actively select appropriate samples that are not well covered by the original training set for model fine-tuning. Furthermore, we adopt a multi-stage fine-tuning strategy to simultaneously improve in-distribution (ID) and OOD performance, bridging the performance gap between them. DaRL has been deployed online to serve the Alipay's insurance product search... 

**Abstract (ZH)**: 随着预训练大型语言模型（LLMs）的迅速发展，最近的研究已经利用了LLMs在相关性建模方面的能力，从而提升了模型的性能。这通常是通过在特定注释数据集上微调LLMs来确定查询与项目之间的相关性来实现的。然而，当LLMs通过微调和推理来简单地进行相关性建模时，存在两个主要限制。首先，LLMs在执行简单的是或否之外的复杂任务时并不高效，例如评估搜索相关性。因此，它们可能过于自信并难以区分搜索引擎中使用的细微相关性程度（如强相关、弱相关和不相关）。其次，它们在现实世界场景中遇到数据分布变化时会表现出显著的性能下降。在这篇论文中，我们提出了一种新型的“aware分布鲁棒学习”框架（DaRL）用于支付宝搜索的相关性建模。具体来说，我们设计了一个有效的损失函数，以增强基于LLMs的相关性建模在各种细微的相关性程度中的区辨力。为了提高基于LLMs的相关性建模的泛化能力，我们首先提出了一种“aware分布样本增强”（DASA）模块。该模块利用出了领域分布（OOD）检测技术，主动选择原来训练集中覆盖不足的适当样本进行模型微调。此外，我们采用了多阶段微调策略，同时提升领域内（ID）和领域外（OOD）性能，缩小两者之间的性能差距。DaRL已经在支付宝保险产品搜索中上线部署…… 

---