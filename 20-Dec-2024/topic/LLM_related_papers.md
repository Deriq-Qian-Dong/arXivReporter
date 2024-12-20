# Nano-ESG: Extracting Corporate Sustainability Information from News Articles 

**Title (ZH)**: 纳米ESG：从新闻文章中提取企业可持续性信息 

**Authors**: Fabian Billert, Stefan Conrad  

**Link**: [PDF](https://arxiv.org/pdf/2412.15093)  

**Abstract**: Determining the sustainability impact of companies is a highly complex subject which has garnered more and more attention over the past few years. Today, investors largely rely on sustainability-ratings from established rating-providers in order to analyze how responsibly a company acts. However, those ratings have recently been criticized for being hard to understand and nearly impossible to reproduce.
An independent way to find out about the sustainability practices of companies lies in the rich landscape of news article data. In this paper, we explore a different approach to identify key opportunities and challenges of companies in the sustainability domain. We present a novel dataset of more than 840,000 news articles which were gathered for major German companies between January 2023 and September 2024. By applying a mixture of Natural Language Processing techniques, we first identify relevant articles, before summarizing them and extracting their sustainability-related sentiment and aspect using Large Language Models (LLMs). Furthermore, we conduct an evaluation of the obtained data and determine that the LLM-produced answers are accurate. We release both datasets at this https URL. 

**Abstract (ZH)**: 确定公司可持续性影响是一项高度复杂的研究课题，近年来越来越受到关注。如今，投资者越来越多地依赖于可持续性评级机构提供的评级数据，以分析公司的行为是否负责任。然而，这些评级最近受到了批评，被认为是难以理解且难以复现的。

从丰富的新闻文章数据中了解公司的可持续性实践提供了一种独立的方法。在本文中，我们探讨了一种不同的方法来识别公司在可持续性领域的关键机遇与挑战。我们汇集了一个包含超过840,000篇新闻文章的新数据集，这些文章是为2023年1月至2024年9月期间的主要德国公司收集的。通过应用多种自然语言处理技术，我们首先识别出相关文章，然后对其进行总结，并使用大规模语言模型（LLMs）提取其可持续性相关的观点和方面。此外，我们对该数据进行了评估，并确定LLM生成的答案是准确的。我们将这两个数据集公开发布在如下链接：[在此处插入链接]。 

---
# Sliding Windows Are Not the End: Exploring Full Ranking with Long-Context Large Language Models 

**Title (ZH)**: 滑动窗口并非终点：探索长上下文大型语言模型的全面排名 

**Authors**: Wenhan Liu, Xinyu Ma, Yutao Zhu, Ziliang Zhao, Shuaiqiang Wang, Dawei Yin, Zhicheng Dou  

**Link**: [PDF](https://arxiv.org/pdf/2412.14574)  

**Abstract**: Large Language Models (LLMs) have shown exciting performance in listwise passage ranking. Due to the limited input length, existing methods often adopt the sliding window strategy. Such a strategy, though effective, is inefficient as it involves repetitive and serialized processing, which usually re-evaluates relevant passages multiple times. As a result, it incurs redundant API costs, which are proportional to the number of inference tokens. The development of long-context LLMs enables the full ranking of all passages within a single inference, avoiding redundant API costs. In this paper, we conduct a comprehensive study of long-context LLMs for ranking tasks in terms of efficiency and effectiveness. Surprisingly, our experiments reveal that full ranking with long-context LLMs can deliver superior performance in the supervised fine-tuning setting with a huge efficiency improvement. Furthermore, we identify two limitations of fine-tuning the full ranking model based on existing methods: (1) sliding window strategy fails to produce a full ranking list as a training label, and (2) the language modeling loss cannot emphasize top-ranked passage IDs in the label. To alleviate these issues, we propose a new complete listwise label construction approach and a novel importance-aware learning objective for full ranking. Experiments show the superior performance of our method over baselines. Our codes are available at \url{this https URL}. 

**Abstract (ZH)**: 大型语言模型（LLMs）在列表级段落排序任务中展现了令人兴奋的性能。由于输入长度有限，现有方法常常采用滑动窗口策略。这种策略虽然有效，但由于涉及重复且串行的处理，通常需要多次重新评估相关段落，导致计算冗余，计算成本与推理令牌的数量成正比。随着具有长上下文能力的LLMs的发展，现在可以在单次推理中对所有段落进行全面排序，从而避免了冗余的API成本。在本文中，我们对具有长上下文的LLMs在排序任务中的效率和效果进行了全面研究。令人惊讶的是，我们的实验表明，在监督微调设置中，使用长上下文的LLMs进行全面排序可以显著提高性能，且具有巨大的效率改进。此外，我们还发现基于现有方法微调全排序模型的两个限制：（1）滑动窗口策略不能生成一个完整的排序列表作为训练标签，（2）语言模型损失无法强调标签中排名靠前的段落ID。为了缓解这些问题，我们提出了一种新的完整列表标签构建方法和一种新颖的重要性感知学习目标，以促进全排序。实验结果表明，我们的方法优于基线方法。我们已在<https://this-url> 公开了我们的代码。 

---
# Are Longer Prompts Always Better? Prompt Selection in Large Language Models for Recommendation Systems 

**Title (ZH)**: 较长的提示是否Always更好？大型语言模型在推荐系统中的提示选择研究 

**Authors**: Genki Kusano, Kosuke Akimoto, Kunihiro Takeoka  

**Link**: [PDF](https://arxiv.org/pdf/2412.14454)  

**Abstract**: In large language models (LLM)-based recommendation systems (LLM-RSs), accurately predicting user preferences by leveraging the general knowledge of LLMs is possible without requiring extensive training data. By converting recommendation tasks into natural language inputs called prompts, LLM-RSs can efficiently solve issues that have been difficult to address due to data scarcity but are crucial in applications such as cold-start and cross-domain problems. However, when applying this in practice, selecting the prompt that matches tasks and data is essential. Although numerous prompts have been proposed in LLM-RSs and representing the target user in prompts significantly impacts recommendation accuracy, there are still no clear guidelines for selecting specific prompts.
In this paper, we categorize and analyze prompts from previous research to establish practical prompt selection guidelines. Through 450 experiments with 90 prompts and five real-world datasets, we examined the relationship between prompts and dataset characteristics in recommendation accuracy. We found that no single prompt consistently outperforms others; thus, selecting prompts on the basis of dataset characteristics is crucial. Here, we propose a prompt selection method that achieves higher accuracy with minimal validation data. Because increasing the number of prompts to explore raises costs, we also introduce a cost-efficient strategy using high-performance and cost-efficient LLMs, significantly reducing exploration costs while maintaining high prediction accuracy. Our work offers valuable insights into the prompt selection, advancing accurate and efficient LLM-RSs. 

**Abstract (ZH)**: 在基于大规模语言模型（LLM）的推荐系统（LLM-RSs）中，通过利用LLM的一般知识，可以在不依赖大量训练数据的情况下准确预测用户偏好。通过将推荐任务转化为称为提示的自然语言输入，LLM-RSs可以高效地解决由于数据稀缺而难以解决但在冷启动和跨域问题等应用中至关重要的问题。然而，在实际应用中，选择与任务和数据相匹配的提示至关重要。尽管在LLM-RS中提出了许多提示，并且提示中表示目标用户对推荐准确性的显著影响，但仍然没有明确的指导原则来选择具体的提示。

在本文中，我们对先前研究中的提示进行分类和分析，以建立实用的提示选择指南。通过在90个提示和五个真实世界数据集上的450次实验，我们研究了提示与数据集特征之间的关系对推荐准确性的影响。我们发现没有哪种提示能够始终优于其他提示，因此，根据数据集特征选择提示至关重要。在此基础上，我们提出了一种提示选择方法，该方法能够在最少的验证数据下实现更高的准确率。由于增加提示的数量以进行探索会增加成本，我们还提出了一个成本效益策略，使用高性能且成本效益高的LLM，显著降低了探索成本，同时保持了高预测准确率。我们的工作为提示选择提供了有价值的观点，推动了准确高效的LLM-RS的发展。 

---
# ChainRank-DPO: Chain Rank Direct Preference Optimization for LLM Rankers 

**Title (ZH)**: ChainRank-DPO：链式排序直接偏好优化算法 vatandaşlar ve onların hakları konusunda daha derin bir bilgi edinme ve tartışmacompanions and their rights concerning chainrank-dpo: 链式排序直接偏好优化算法中的同伴及其权利探讨

这里的翻译需要稍微解释一下：

1. "ChainRank-DPO" 是一个具体的算法名称，保持不变。

2. "companions" 在这里翻译为“同伴”，与原文内容相对应。

3. "and their rights concerning chainrank-dpo" 翻译为“及其在链式排序直接偏好优化算法中的权利”，以确保语义准确。

若原文意图是指某种与CHAINRANK-DPO算法相关的权利问题或伦理考量，可进一步调整为：

"ChainRank-DPO中的权利问题：同伴及其在该算法中的权益"

这样更符合学术论文标题的要求。 

**Authors**: Haowei Liu, Xuyang Wu, Guohao Sun, Zhiqiang Tao, Yi Fang  

**Link**: [PDF](https://arxiv.org/pdf/2412.14405)  

**Abstract**: Large language models (LLMs) have demonstrated remarkable effectiveness in text reranking through works like RankGPT, leveraging their human-like reasoning about relevance. However, supervised fine-tuning for ranking often diminishes these models' general-purpose capabilities, including the crucial reasoning abilities that make them valuable for ranking. We introduce a novel approach integrating Chain-of-Thought prompting with an SFT-DPO (Supervised Fine-Tuning followed by Direct Preference Optimization) pipeline to preserve these capabilities while improving ranking performance. Our experiments on TREC 2019 and 2020 Deep Learning datasets show that our approach outperforms the state-of-the-art RankZephyr while maintaining strong performance on the Massive Multitask Language Understanding (MMLU) benchmark, demonstrating effective preservation of general-purpose capabilities through thoughtful fine-tuning strategies. Our code and data will be publicly released upon the acceptance of the paper. 

**Abstract (ZH)**: 大型语言模型（LLMs）在通过如RankGPT等研究工作中的文本重排名任务中展现出了显著的效果，得益于它们在相关性方面的类人推理能力。然而，针对排序任务的监督微调往往会削弱这些模型的一般化能力，包括使它们在排序任务中具有价值的重要推理能力。我们提出了一种新的方法，将Chain-of-Thought提示与SFT-DPO（监督微调后直接偏好优化）管道相结合，以在保持这些能力的同时提升排序性能。我们的实验在TREC 2019和2020年深度学习数据集上表明，我们的方法在性能上优于最新的RankZephyr，同时在大规模多任务语言理解（MMLU）基准测试中保持了强大的性能，证明了通过精心设计的微调策略有效地保留了这些一般化能力。论文被接受后，我们将公开发布我们的代码和数据。 

---
# Progressive Multimodal Reasoning via Active Retrieval 

**Title (ZH)**: 基于主动检索的渐进多模态推理 

**Authors**: Guanting Dong, Chenghao Zhang, Mengjie Deng, Yutao Zhu, Zhicheng Dou, Ji-Rong Wen  

**Link**: [PDF](https://arxiv.org/pdf/2412.14835)  

**Abstract**: Multi-step multimodal reasoning tasks pose significant challenges for multimodal large language models (MLLMs), and finding effective ways to enhance their performance in such scenarios remains an unresolved issue. In this paper, we propose AR-MCTS, a universal framework designed to progressively improve the reasoning capabilities of MLLMs through Active Retrieval (AR) and Monte Carlo Tree Search (MCTS). Our approach begins with the development of a unified retrieval module that retrieves key supporting insights for solving complex reasoning problems from a hybrid-modal retrieval corpus. To bridge the gap in automated multimodal reasoning verification, we employ the MCTS algorithm combined with an active retrieval mechanism, which enables the automatic generation of step-wise annotations. This strategy dynamically retrieves key insights for each reasoning step, moving beyond traditional beam search sampling to improve the diversity and reliability of the reasoning space. Additionally, we introduce a process reward model that aligns progressively to support the automatic verification of multimodal reasoning tasks. Experimental results across three complex multimodal reasoning benchmarks confirm the effectiveness of the AR-MCTS framework in enhancing the performance of various multimodal models. Further analysis demonstrates that AR-MCTS can optimize sampling diversity and accuracy, yielding reliable multimodal reasoning. 

**Abstract (ZH)**: 多步骤多模态推理任务为多模态大型语言模型（MLLMs）带来了重大挑战，如何在这种场景中有效地提升其性能仍是未解问题。本文提出了一种名为AR-MCTS的通用框架，旨在通过主动检索（AR）和蒙特卡洛树搜索（MCTS）逐步提高MLLMs的推理能力。该方法首先开发了一个统一的检索模块，从混合模态检索库中检索解决复杂推理问题的关键支持见解。为了弥合自动多模态推理验证的差距，我们采用了结合主动检索机制的Monte Carlo树搜索算法，这使得能够自动生成逐步标注。这一策略动态检索每个推理步骤的关键见解，超越了传统的束搜索采样，以改善推理空间的多样性和可靠性。此外，我们引入了一种过程奖励模型，以逐步支持多模态推理任务的自动验证。在三个复杂的多模态推理基准测试中，实验结果证实了AR-MCTS框架增强各种多模态模型性能的有效性。进一步分析表明，AR-MCTS可以优化采样多样性和准确性，从而实现可靠的多模态推理。 

---
# Moving Beyond LDA: A Comparison of Unsupervised Topic Modelling Techniques for Qualitative Data Analysis of Online Communities 

**Title (ZH)**: 超越LDA：无监督主题建模技术在在线社区定性数据分析中的比较 

**Authors**: Amandeep Kaur, James R. Wallace  

**Link**: [PDF](https://arxiv.org/pdf/2412.14486)  

**Abstract**: Social media constitutes a rich and influential source of information for qualitative researchers. Although computational techniques like topic modelling assist with managing the volume and diversity of social media content, qualitative researcher's lack of programming expertise creates a significant barrier to their adoption. In this paper we explore how BERTopic, an advanced Large Language Model (LLM)-based topic modelling technique, can support qualitative data analysis of social media. We conducted interviews and hands-on evaluations in which qualitative researchers compared topics from three modelling techniques: LDA, NMF, and BERTopic. BERTopic was favoured by 8 of 12 participants for its ability to provide detailed, coherent clusters for deeper understanding and actionable insights. Participants also prioritised topic relevance, logical organisation, and the capacity to reveal unexpected relationships within the data. Our findings underscore the potential of LLM-based techniques for supporting qualitative analysis. 

**Abstract (ZH)**: 社交媒体是一种丰富且有影响力的定性研究信息来源。尽管计算技术，如主题建模，有助于管理社交媒体内容的规模和多样性，但缺乏编程技能的定性研究人员在使用这些技术方面面临着重大障碍。本文探讨了如何利用基于大型语言模型（LLM）的主题建模技术BERTopic 支持社交媒体的定性数据分析。我们进行了访谈和实际操作评估，让定性研究人员将三种建模技术（LDA、NMF 和 BERTopic）生成的主题进行了比较。结果显示，12 名参与者中有 8 人更偏好 BERTopic，因为它能够提供详细、连贯的主题聚类，从而有助于深入理解和获取行动性见解。参与者还优先考虑了主题的相关性、逻辑组织以及揭示数据中未预见关系的能力。我们的研究结果突显了基于大型语言模型的方法在支持定性分析方面的潜在价值。 

---
# Advanced Reasoning and Transformation Engine for Multi-Step Insight Synthesis in Data Analytics with Large Language Models 

**Title (ZH)**: 使用大型语言模型在数据-analytics中进行多步洞察综合的先进推理与转换引擎 

**Authors**: Atin Sakkeer Hussain  

**Link**: [PDF](https://arxiv.org/pdf/2412.14146)  

**Abstract**: This paper presents the Advanced Reasoning and Transformation Engine for Multi-Step Insight Synthesis in Data Analytics (ARTEMIS-DA), a novel framework designed to augment Large Language Models (LLMs) for solving complex, multi-step data analytics tasks. ARTEMIS-DA integrates three core components: the Planner, which dissects complex user queries into structured, sequential instructions encompassing data preprocessing, transformation, predictive modeling, and visualization; the Coder, which dynamically generates and executes Python code to implement these instructions; and the Grapher, which interprets generated visualizations to derive actionable insights. By orchestrating the collaboration between these components, ARTEMIS-DA effectively manages sophisticated analytical workflows involving advanced reasoning, multi-step transformations, and synthesis across diverse data modalities. The framework achieves state-of-the-art (SOTA) performance on benchmarks such as WikiTableQuestions and TabFact, demonstrating its ability to tackle intricate analytical tasks with precision and adaptability. By combining the reasoning capabilities of LLMs with automated code generation and execution and visual analysis, ARTEMIS-DA offers a robust, scalable solution for multi-step insight synthesis, addressing a wide range of challenges in data analytics. 

**Abstract (ZH)**: 本文介绍了Advanced Reasoning and Transformation Engine for Multi-Step Insight Synthesis in Data Analytics（ARTEMIS-DA），这是一种新颖的框架，旨在增强大型语言模型（LLMs）以解决复杂的多步数据分析任务。ARTEMIS-DA 集成了三个核心组件：规划器（Planner），它将复杂的用户查询分解为结构化、序列化的指令，涵盖数据预处理、变换、预测建模和可视化；编码器（Coder），它动态生成并执行 Python 代码以实现这些指令；以及图形生成器（Grapher），它解释生成的可视化以得出 actionable 的洞见。通过协调这些组件之间的合作，ARTEMIS-DA 有效管理了涉及高级推理、多步骤变换和跨多种数据模态综合的复杂分析工作流。该框架在 WikiTableQuestions 和 TabFact 等基准测试中实现了最先进的（SOTA）性能，展示了其解决复杂分析任务的精确性和适应性。通过结合 LLM 的推理能力、自动化代码生成与执行以及可视化分析，ARTEMIS-DA 提供了一种稳健且可扩展的解决方案，用于多步洞见综合，解决了数据分析中广泛存在的挑战。 

---
# Large Language Model Enhanced Recommender Systems: Taxonomy, Trend, Application and Future 

**Title (ZH)**: 增强型大型语言模型推荐系统：分类、趋势、应用与未来 

**Authors**: Qidong Liu, Xiangyu Zhao, Yuhao Wang, Yejing Wang, Zijian Zhang, Yuqi Sun, Xiang Li, Maolin Wang, Pengyue Jia, Chong Chen, Wei Huang, Feng Tian  

**Link**: [PDF](https://arxiv.org/pdf/2412.13432)  

**Abstract**: Large Language Model (LLM) has transformative potential in various domains, including recommender systems (RS). There have been a handful of research that focuses on empowering the RS by LLM. However, previous efforts mainly focus on LLM as RS, which may face the challenge of intolerant inference costs by LLM. Recently, the integration of LLM into RS, known as LLM-Enhanced Recommender Systems (LLMERS), has garnered significant interest due to its potential to address latency and memory constraints in real-world applications. This paper presents a comprehensive survey of the latest research efforts aimed at leveraging LLM to enhance RS capabilities. We identify a critical shift in the field with the move towards incorporating LLM into the online system, notably by avoiding their use during inference. Our survey categorizes the existing LLMERS approaches into three primary types based on the component of the RS model being augmented: Knowledge Enhancement, Interaction Enhancement, and Model Enhancement. We provide an in-depth analysis of each category, discussing the methodologies, challenges, and contributions of recent studies. Furthermore, we highlight several promising research directions that could further advance the field of LLMERS. 

**Abstract (ZH)**: 大型语言模型（LLM）在多个领域具有变革性的潜力，包括推荐系统（RS）。已有少量研究关注通过LLM来增强RS。然而，之前的大部分努力主要集中在将LLM作为RS本身，这可能会面临LLM不可容忍的推理成本挑战。最近，将LLM集成到RS中，被称为LLM增强推荐系统（LLMERS），因其在解决实际应用中延迟和内存限制方面的潜力而引起了广泛关注。本文对最新的研究努力进行了全面综述，旨在利用LLM来增强RS能力。我们识别出领域内的一项关键转变，即转向将LLM集成到在线系统中，特别是在推理阶段避免使用LLM。我们按照被增强的RS模型组件将现有的LLMERS方法分类为三类：知识增强、交互增强和模型增强。我们对每类进行了深入分析，讨论了最近研究的方法、挑战和贡献。此外，我们还指出了几种有前途的研究方向，这些方向有望进一步推动LLMERS领域的进展。 

---
# LongBench v2: Towards Deeper Understanding and Reasoning on Realistic Long-context Multitasks 

**Title (ZH)**: LongBench v2：朝着对现实环境中长上下文多任务有更深的理解和推理方向发展 

**Authors**: Yushi Bai, Shangqing Tu, Jiajie Zhang, Hao Peng, Xiaozhi Wang, Xin Lv, Shulin Cao, Jiazheng Xu, Lei Hou, Yuxiao Dong, Jie Tang, Juanzi Li  

**Link**: [PDF](https://arxiv.org/pdf/2412.15204)  

**Abstract**: This paper introduces LongBench v2, a benchmark designed to assess the ability of LLMs to handle long-context problems requiring deep understanding and reasoning across real-world multitasks. LongBench v2 consists of 503 challenging multiple-choice questions, with contexts ranging from 8k to 2M words, across six major task categories: single-document QA, multi-document QA, long in-context learning, long-dialogue history understanding, code repository understanding, and long structured data understanding. To ensure the breadth and the practicality, we collect data from nearly 100 highly educated individuals with diverse professional backgrounds. We employ both automated and manual review processes to maintain high quality and difficulty, resulting in human experts achieving only 53.7% accuracy under a 15-minute time constraint. Our evaluation reveals that the best-performing model, when directly answers the questions, achieves only 50.1% accuracy. In contrast, the o1-preview model, which includes longer reasoning, achieves 57.7%, surpassing the human baseline by 4%. These results highlight the importance of enhanced reasoning ability and scaling inference-time compute to tackle the long-context challenges in LongBench v2. The project is available at this https URL. 

**Abstract (ZH)**: 本文介绍了LongBench v2，这是一个基准测试，旨在评估大语言模型（LLMs）在处理需要深入理解和推理的长上下文问题方面的能力，特别是在实际多任务中的表现。LongBench v2 包含了 503 个具有挑战性的多项选择题，上下文范围从 8 千字到 2 百万字，涉及六个主要任务类别：单文档问答、多文档问答、长上下文学习、长对话历史理解、代码仓库理解以及长结构化数据理解。为了确保数据的广泛性和实用性，我们从来自多个专业背景的近 100 名高度教育的个体收集了数据。我们采用自动和手动审查相结合的方式，以保持高质量和难度，最终在 15 分钟的时间限制下，人类专家的准确率仅为 53.7%。我们的评估结果显示，当最佳模型直接回答问题时，其准确率仅为 50.1%。相比之下，o1-preview 模型包含了更长时间的推理，其准确率为 57.7%，超过了人类基准 4%。这些结果突显了增强推理能力和扩展推理时计算量在应对 LongBench v2 中长上下文挑战方面的重要性。该项目可在以下网址访问：[该项目网址]。 

---
# MMLU-CF: A Contamination-free Multi-task Language Understanding Benchmark 

**Title (ZH)**: MMLU-CF：一个无污染的多任务语言理解基准测试 

**Authors**: Qihao Zhao, Yangyu Huang, Tengchao Lv, Lei Cui, Qinzheng Sun, Shaoguang Mao, Xin Zhang, Ying Xin, Qiufeng Yin, Scarlett Li, Furu Wei  

**Link**: [PDF](https://arxiv.org/pdf/2412.15194)  

**Abstract**: Multiple-choice question (MCQ) datasets like Massive Multitask Language Understanding (MMLU) are widely used to evaluate the commonsense, understanding, and problem-solving abilities of large language models (LLMs). However, the open-source nature of these benchmarks and the broad sources of training data for LLMs have inevitably led to benchmark contamination, resulting in unreliable evaluation results. To alleviate this issue, we propose a contamination-free and more challenging MCQ benchmark called MMLU-CF. This benchmark reassesses LLMs' understanding of world knowledge by averting both unintentional and malicious data leakage. To avoid unintentional data leakage, we source data from a broader domain and design three decontamination rules. To prevent malicious data leakage, we divide the benchmark into validation and test sets with similar difficulty and subject distributions. The test set remains closed-source to ensure reliable results, while the validation set is publicly available to promote transparency and facilitate independent verification. Our evaluation of mainstream LLMs reveals that the powerful GPT-4o achieves merely a 5-shot score of 73.4% and a 0-shot score of 71.9% on the test set, which indicates the effectiveness of our approach in creating a more rigorous and contamination-free evaluation standard. The GitHub repository is available at this https URL and the dataset refers to this https URL. 

**Abstract (ZH)**: 多选题数据集（MCQ数据集），如大规模多任务语言理解（MMLU），广泛用于评估大型语言模型（LLMs）的常识、理解和问题解决能力。然而，这些基准的开源性质以及LLMs广泛的数据来源不可避免地导致了基准数据的污染，从而产生了不可靠的评估结果。为了解决这一问题，我们提出了一种无污染且更具挑战性的MCQ基准——MMLU-CF。该基准通过避免无意和恶意的数据泄漏，重新评估LLMs对世界知识的理解能力。为了防止无意数据泄漏，我们从更广泛的领域获取数据，并设计了三个去污染规则。为了防止恶意数据泄漏，我们将基准划分为具有类似难度和主题分布的验证集和测试集。测试集保持封闭源代码状态，以确保结果的可靠性，验证集则公开发布，促进透明度并方便独立验证。我们的评估显示，强大的GPT-4o在测试集上的5-shot得分为73.4%，0-shot得分为71.9%，这表明了我们方法在建立更为严格和无污染的评价标准方面的有效性。GitHub仓库地址为：[这里](https://github.com/)，数据集请参考：[这里](https://dataset.com/)。 

---
# LlamaFusion: Adapting Pretrained Language Models for Multimodal Generation 

**Title (ZH)**: LlamaFusion：适应多模态生成的预训练语言模型 

**Authors**: Weijia Shi, Xiaochuang Han, Chunting Zhou, Weixin Liang, Xi Victoria Lin, Luke Zettlemoyer, Lili Yu  

**Link**: [PDF](https://arxiv.org/pdf/2412.15188)  

**Abstract**: We present LlamaFusion, a framework for empowering pretrained text-only large language models (LLMs) with multimodal generative capabilities, enabling them to understand and generate both text and images in arbitrary sequences. LlamaFusion leverages existing Llama-3's weights for processing texts autoregressively while introducing additional and parallel transformer modules for processing images with diffusion. During training, the data from each modality is routed to its dedicated modules: modality-specific feedforward layers, query-key-value projections, and normalization layers process each modality independently, while the shared self-attention layers allow interactions across text and image features. By freezing the text-specific modules and only training the image-specific modules, LlamaFusion preserves the language capabilities of text-only LLMs while developing strong visual understanding and generation abilities. Compared to methods that pretrain multimodal generative models from scratch, our experiments demonstrate that, LlamaFusion improves image understanding by 20% and image generation by 3.6% using only 50% of the FLOPs while maintaining Llama-3's language capabilities. We also demonstrate that this framework can adapt existing vision-language models with multimodal generation ability. Overall, this framework not only leverages existing computational investments in text-only LLMs but also enables the parallel development of language and vision capabilities, presenting a promising direction for efficient multimodal model development. 

**Abstract (ZH)**: 我们提出了LlamaFusion框架，该框架旨在赋予仅预训练文本的大语言模型（LLM）多模态生成能力，使其能够理解和生成任意序列的文本和图像。LlamaFusion利用现有的Llama-3权重进行自回归文本处理，同时引入额外且并行的变压器模块以通过扩散处理图像。在训练过程中，来自不同模态的数据会流向其专用模块：特定于模态的前馈层、查询-键-值投影以及规范化层分别独立处理每个模态，而共享的自注意力层则允许文本和图像特征之间的交互。通过冻结特定于文本的模块，并仅训练特定于图像的模块，LlamaFusion保留了仅文本LLM的语言能力，同时发展了强大的视觉理解与生成能力。与从零开始预训练多模态生成模型的方法相比，我们的实验表明，LlamaFusion仅使用50%的FLOPs即可提升20%的图像理解能力和3.6%的图像生成能力，同时保持Llama-3的语言能力。此外，我们还展示了该框架可以适应已有的具有多模态生成能力的视觉-语言模型。总体而言，该框架不仅利用了现有仅文本LLM的计算投资，还实现了语言与视觉能力的并行开发，为高效的多模态模型开发提供了颇有前景的方向。 

---
# Language Models as Continuous Self-Evolving Data Engineers 

**Title (ZH)**: 语言模型作为连续自我进化的数据工程师 

**Authors**: Peidong Wang, Ming Wang, Zhiming Ma, Xiaocui Yang, Shi Feng, Daling Wang, Yifei Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2412.15151)  

**Abstract**: Large Language Models (LLMs) have demonstrated remarkable capabilities on various tasks, while the further evolvement is limited to the lack of high-quality training data. In addition, traditional training approaches rely too much on expert-labeled data, setting an upper limit on the performance of LLMs. To address this issue, we propose a novel paradigm that enables LLMs to train itself by autonomously generating, cleaning, reviewing, and annotating data with preference information, named LANCE. Our approach demonstrates that LLMs can serve as continuous self-evolving data engineers, significantly reducing the time and cost of the post-training data construction process. Through iterative fine-tuning on different variants of the Qwen2, we validate the effectiveness of LANCE across various tasks, showing that it can continuously improve model performance and maintain high-quality data generation. Across eight benchmark dimensions, LANCE resulted in an average score enhancement of 3.36 for Qwen2-7B and 2.70 for Qwen2-7B-Instruct. This training paradigm with autonomous data construction not only reduces the reliance on human experts or external models but also ensures that the data aligns with human values and preferences, paving the way for the development of future superintelligent systems that can exceed human capabilities. 

**Abstract (ZH)**: 大型语言模型（LLMs）在多种任务上展现了卓越的能力，但进一步的发展受限于高质量训练数据的不足。此外，传统的训练方法过于依赖专家标注的数据，从而对LLMs的性能设立了上限。为了解决这一问题，我们提出了一种新的范式，使LLMs能够自主生成、清洗、审查和注释带有偏好信息的数据，这一过程被命名为LANCE。我们的方法表明，LLMs可以作为持续自我演化的数据工程师，显著减少了后训练数据构建过程的时间和成本。通过在不同版本的Qwen2上进行迭代微调，我们验证了LANCE在各种任务中的有效性，显示其能够持续提升模型性能并维持高质量的数据生成。LANCE在八个基准维度上分别提高了Qwen2-7B和Qwen2-7B-Instruct 3.36和2.70的分数。这种具有自主数据构建的训练范式不仅减少了对人类专家或外部模型的依赖，还确保了数据与人类价值观和偏好的一致性，为未来超智能系统的开发铺平了道路，这些系统能够超越人类的能力。 

---
# Qwen2.5 Technical Report 

**Title (ZH)**: Qwen2.5 技术报告 

**Authors**: Qwen, An Yang, Baosong Yang, Beichen Zhang, Binyuan Hui, Bo Zheng, Bowen Yu, Chengyuan Li, Dayiheng Liu, Fei Huang, Haoran Wei, Huan Lin, Jian Yang, Jianhong Tu, Jianwei Zhang, Jianxin Yang, Jiaxi Yang, Jingren Zhou, Junyang Lin, Kai Dang, Keming Lu, Keqin Bao, Kexin Yang, Le Yu, Mei Li, Mingfeng Xue, Pei Zhang, Qin Zhu, Rui Men, Runji Lin, Tianhao Li, Tingyu Xia, Xingzhang Ren, Xuancheng Ren, Yang Fan, Yang Su, Yichang Zhang, Yu Wan, Yuqiong Liu, Zeyu Cui, Zhenru Zhang, Zihan Qiu  

**Link**: [PDF](https://arxiv.org/pdf/2412.15115)  

**Abstract**: In this report, we introduce Qwen2.5, a comprehensive series of large language models (LLMs) designed to meet diverse needs. Compared to previous iterations, Qwen 2.5 has been significantly improved during both the pre-training and post-training stages. In terms of pre-training, we have scaled the high-quality pre-training datasets from the previous 7 trillion tokens to 18 trillion tokens. This provides a strong foundation for common sense, expert knowledge, and reasoning capabilities. In terms of post-training, we implement intricate supervised finetuning with over 1 million samples, as well as multistage reinforcement learning. Post-training techniques enhance human preference, and notably improve long text generation, structural data analysis, and instruction following. To handle diverse and varied use cases effectively, we present Qwen2.5 LLM series in rich sizes. Open-weight offerings include base and instruction-tuned models, with quantized versions available. In addition, for hosted solutions, the proprietary models currently include two mixture-of-experts (MoE) variants: Qwen2.5-Turbo and Qwen2.5-Plus, both available from Alibaba Cloud Model Studio. Qwen2.5 has demonstrated top-tier performance on a wide range of benchmarks evaluating language understanding, reasoning, mathematics, coding, human preference alignment, etc. Specifically, the open-weight flagship Qwen2.5-72B-Instruct outperforms a number of open and proprietary models and demonstrates competitive performance to the state-of-the-art open-weight model, Llama-3-405B-Instruct, which is around 5 times larger. Qwen2.5-Turbo and Qwen2.5-Plus offer superior cost-effectiveness while performing competitively against GPT-4o-mini and GPT-4o respectively. Additionally, as the foundation, Qwen2.5 models have been instrumental in training specialized models such as Qwen2.5-Math, Qwen2.5-Coder, QwQ, and multimodal models. 

**Abstract (ZH)**: 在本报告中，我们介绍了Qwen 2.5，这是一个全面的大型语言模型（LLM）系列，旨在满足各种需求。与之前的版本相比，Qwen 2.5 在预训练和后训练阶段均得到了显著改进。在预训练方面，我们将高质量的预训练数据集从之前的7万亿个 token 扩大到18万亿个 token。这为常识、专家知识和推理能力提供了坚实的基础。在后训练方面，我们实施了复杂的监督微调，涉及超过100万的样本，以及多阶段强化学习。后训练技术增强了对人类偏好的理解，并显著提高了长文本生成、结构化数据分析和指令遵循的能力。为了有效应对各种各样的应用场景，我们推出了丰富规格的Qwen 2.5 LLM系列。开放模型包括基础模型和指令调优模型，并提供量化版本。此外，对于托管解决方案，当前的自研模型包括两种专家混合模型（MoE）变体：Qwen 2.5 Turbo 和 Qwen 2.5 Plus，两者均来自阿里云模型工作室。Qwen 2.5 在广泛的语言理解、推理、数学、编程、人类偏好对齐等基准测试中展现了顶尖的性能。特别是开放模型Qwen 2.5-72B-Instruct，在多项测试中均表现优异，优于多个开放和自研模型，并与更大的开源模型Llama-3-405B-Instruct（约大5倍）性能相当。Qwen 2.5 Turbo 和 Qwen 2.5 Plus 提供了更高的性价比，性能分别与GPT-4o-mini 和 GPT-4o 竞争。此外，作为基础模型，Qwen 2.5 还被用于训练各种专业模型，如Qwen 2.5-Math、Qwen 2.5-Coder、QwQ 和多模态模型。 

---
# ConfliBERT: A Language Model for Political Conflict 

**Title (ZH)**: 冲突BERT：一个用于政治冲突的语言模型 

**Authors**: Patrick T. Brandt, Sultan Alsarra, Vito J. D`Orazio, Dagmar Heintze, Latifur Khan, Shreyas Meher, Javier Osorio, Marcus Sianan  

**Link**: [PDF](https://arxiv.org/pdf/2412.15060)  

**Abstract**: Conflict scholars have used rule-based approaches to extract information about political violence from news reports and texts. Recent Natural Language Processing developments move beyond rigid rule-based approaches. We review our recent ConfliBERT language model (Hu et al. 2022) to process political and violence related texts. The model can be used to extract actor and action classifications from texts about political conflict. When fine-tuned, results show that ConfliBERT has superior performance in accuracy, precision and recall over other large language models (LLM) like Google's Gemma 2 (9B), Meta's Llama 3.1 (7B), and Alibaba's Qwen 2.5 (14B) within its relevant domains. It is also hundreds of times faster than these more generalist LLMs. These results are illustrated using texts from the BBC, re3d, and the Global Terrorism Dataset (GTD). 

**Abstract (ZH)**: 冲突研究学者利用基于规则的方法从新闻报道和文本中提取关于政治暴力的信息。最近的自然语言处理（NLP）发展超越了刚性基于规则的方法。我们回顾了我们最近开发的ConfliBERT语言模型（Hu等，2022），以处理与政治和暴力相关的文本。该模型可以从关于政治冲突的文本中提取行为者和行为分类。当进行微调后，结果显示，与谷歌的Gemma 2（9B）、Meta的Llama 3.1（7B）和阿里巴巴的Qwen 2.5（14B）等其他大型语言模型相比，ConfliBERT在相关领域内的准确率、精确率和召回率方面表现更优。此外，ConfliBERT比这些更为通用的大规模语言模型快上百倍。这些结果通过使用来自BBC、re3d和全球恐怖主义数据库（GTD）的文本数据进行了说明。 

---
# RobustFT: Robust Supervised Fine-tuning for Large Language Models under Noisy Response 

**Title (ZH)**: RobustFT：在嘈杂响应条件下大型语言模型的稳健监督微调 

**Authors**: Junyu Luo, Xiao Luo, Kaize Ding, Jingyang Yuan, Zhiping Xiao, Ming Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2412.14922)  

**Abstract**: Supervised fine-tuning (SFT) plays a crucial role in adapting large language models (LLMs) to specific domains or tasks. However, as demonstrated by empirical experiments, the collected data inevitably contains noise in practical applications, which poses significant challenges to model performance on downstream tasks. Therefore, there is an urgent need for a noise-robust SFT framework to enhance model capabilities in downstream tasks. To address this challenge, we introduce a robust SFT framework (RobustFT) that performs noise detection and relabeling on downstream task data. For noise identification, our approach employs a multi-expert collaborative system with inference-enhanced models to achieve superior noise detection. In the denoising phase, we utilize a context-enhanced strategy, which incorporates the most relevant and confident knowledge followed by careful assessment to generate reliable annotations. Additionally, we introduce an effective data selection mechanism based on response entropy, ensuring only high-quality samples are retained for fine-tuning. Extensive experiments conducted on multiple LLMs across five datasets demonstrate RobustFT's exceptional performance in noisy scenarios. 

**Abstract (ZH)**: 监督微调（SFT）在适应大规模语言模型（LLMs）到特定领域或任务方面发挥着重要作用。然而，如实践经验所显示的，实际应用中收集的数据不可避免地包含噪声，这对下游任务的模型性能构成了重大挑战。因此，迫切需要一个抗噪的SFT框架以提高模型在下游任务中的能力。为应对这一挑战，我们引入了一个抗噪SFT框架（RobustFT），该框架能够在下游任务数据中进行噪声检测和重新标注。在噪声识别方面，我们的方法采用多专家协作系统和推理增强模型以实现优越的噪声检测效果。在去噪阶段，我们采用了上下文增强策略，该策略结合了最相关且自信的知识，并经过仔细评估以生成可靠标注。此外，我们引入了一种基于响应熵的有效数据选择机制，确保仅保留高质量样本进行微调。在多个LLM上进行的跨五个数据集的广泛实验表明，RobustFT在噪声场景下表现出色。 

---
# Dehallucinating Parallel Context Extension for Retrieval-Augmented Generation 

**Title (ZH)**: 去 hallucination 的并行上下文扩展用于检索增强生成

在这个翻译中，“Dehallucinating”被理解为去除或纠正hallucination（即生成与输入或知识库不符的内容），以更符合学术表达。“Parallel Context Extension for Retrieval-Augmented Generation”被直接翻译为“并行上下文扩展用于检索增强生成”。这样的翻译既保留了原意，又符合学术论文的表述规范。 

**Authors**: Zexiong Ma, Shengnan An, Zeqi Lin, Yanzhen Zou, Jian-Guang Lou, Bing Xie  

**Link**: [PDF](https://arxiv.org/pdf/2412.14905)  

**Abstract**: Large language models (LLMs) are susceptible to generating hallucinated information, despite the integration of retrieval-augmented generation (RAG). Parallel context extension (PCE) is a line of research attempting to effectively integrating parallel (unordered) contexts, while it still suffers from hallucinations when adapted to RAG scenarios. In this paper, we propose DePaC (Dehallucinating Parallel Context Extension), which alleviates the hallucination problem with context-aware negative training and information-calibrated aggregation. DePaC is designed to alleviate two types of in-context hallucination: fact fabrication (i.e., LLMs present claims that are not supported by the contexts) and fact omission (i.e., LLMs fail to present claims that can be supported by the contexts). Specifically, (1) for fact fabrication, we apply the context-aware negative training that fine-tunes the LLMs with negative supervisions, thus explicitly guiding the LLMs to refuse to answer when contexts are not related to questions; (2) for fact omission, we propose the information-calibrated aggregation which prioritizes context windows with higher information increment from their contexts. The experimental results on nine RAG tasks demonstrate that DePaC significantly alleviates the two types of hallucination and consistently achieves better performances on these tasks. 

**Abstract (ZH)**: 以下是经过学术规范翻译后的论文内容或标题：

大型语言模型（LLMs）在融合检索增强生成（RAG）技术后，仍有可能生成虚假信息。平行上下文扩展（PCE）是一类旨在有效整合不相关上下文的研究方法，但当应用于RAG场景时，仍然存在生成虚假信息的问题。本文提出了一种名为DePaC（Dehallucinating Parallel Context Extension）的方案，通过上下文感知的负向训练和信息校准聚合来缓解虚假信息问题。DePaC 设计用于解决两种类型的上下文内部虚假信息问题：事实杜撰（即，LLMs 提供与上下文无关的断言）和事实遗漏（即，LLMs 未能提供可以支持上下文的断言）。具体而言，(1) 对于事实杜撰，我们采用上下文感知的负向训练，对LLMs 进行微调并接受负向监督，从而使LLMs 显式地在上下文与问题无关时拒绝回答；(2) 对于事实遗漏，我们提出了信息校准聚合方法，优先考虑信息增量较大的上下文窗口。在九个RAG任务上的实验结果表明，DePaC 显著缓解了这两种虚假信息问题，并在这些任务上始终取得了更好的表现。 

---
# Mapping and Influencing the Political Ideology of Large Language Models using Synthetic Personas 

**Title (ZH)**: 使用合成人物映射和影响大型语言模型的政治意识形态 

**Authors**: Pietro Bernardelle, Leon Fröhling, Stefano Civelli, Riccardo Lunardi, Kevin Roiter, Gianluca Demartini  

**Link**: [PDF](https://arxiv.org/pdf/2412.14843)  

**Abstract**: The analysis of political biases in large language models (LLMs) has primarily examined these systems as single entities with fixed viewpoints. While various methods exist for measuring such biases, the impact of persona-based prompting on LLMs' political orientation remains unexplored. In this work we leverage PersonaHub, a collection of synthetic persona descriptions, to map the political distribution of persona-based prompted LLMs using the Political Compass Test (PCT). We then examine whether these initial compass distributions can be manipulated through explicit ideological prompting towards diametrically opposed political orientations: right-authoritarian and left-libertarian. Our experiments reveal that synthetic personas predominantly cluster in the left-libertarian quadrant, with models demonstrating varying degrees of responsiveness when prompted with explicit ideological descriptors. While all models demonstrate significant shifts towards right-authoritarian positions, they exhibit more limited shifts towards left-libertarian positions, suggesting an asymmetric response to ideological manipulation that may reflect inherent biases in model training. 

**Abstract (ZH)**: 对大型语言模型（LLMs）中的政治偏见进行分析主要将这些系统视为具有固定视角的单一实体。虽然存在多种测量偏见的方法，但基于人设的提示对LLMs政治倾向的影响尚未得到探索。本研究利用PersonaHub合集——一个合成人设描述的集合——通过政治取向测试（PCT）来绘制基于人设的提示LLMs的政治分布图。我们随后探讨是否可以通过明确指示意识形态来操控这些初始的政治取向分布，进而使其偏向完全对立的政治取向：右翼权威主义和左翼自由主义。实验结果显示，合成人设主要集中在左翼自由主义象限，当使用明确的意识形态描述进行提示时，模型显示出不同程度的响应。所有模型在右翼权威主义方向上都表现出显著的转变，但在左翼自由主义方向上的转变则更为有限，这表明对意识形态操纵的不对称响应可能反映了模型训练中的固有偏见。 

---
# Disentangling Reasoning Tokens and Boilerplate Tokens For Language Model Fine-tuning 

**Title (ZH)**: 拆分推理令牌和模板令牌以进行语言模型微调 

**Authors**: Ziang Ye, Zhenru Zhang, Yang Zhang, Jianxin Ma, Junyang Lin, Fuli Feng  

**Link**: [PDF](https://arxiv.org/pdf/2412.14780)  

**Abstract**: When using agent-task datasets to enhance agent capabilities for Large Language Models (LLMs), current methodologies often treat all tokens within a sample equally. However, we argue that tokens serving different roles - specifically, reasoning tokens versus boilerplate tokens (e.g., those governing output format) - differ significantly in importance and learning complexity, necessitating their disentanglement and distinct treatment. To address this, we propose a novel Shuffle-Aware Discriminator (SHAD) for adaptive token discrimination. SHAD classifies tokens by exploiting predictability differences observed after shuffling input-output combinations across samples: boilerplate tokens, due to their repetitive nature among samples, maintain predictability, whereas reasoning tokens do not. Using SHAD, we propose the Reasoning-highlighted Fine-Tuning (RFT) method, which adaptively emphasizes reasoning tokens during fine-tuning, yielding notable performance gains over common Supervised Fine-Tuning (SFT). 

**Abstract (ZH)**: 当使用代理任务数据集来增强大型语言模型（LLMs）的代理能力时，当前的方法往往将每个样本内的所有标记视为同等重要。然而，我们认为在不同角色中承担不同功能的标记——尤其是推理标记与模板标记（如控制输出格式的标记）——在重要性和学习复杂性方面存在显著差异，需要进行分离并分别处理。为解决这一问题，我们提出了一种新的Shuffle-Aware Discriminator（SHAD）用于自适应标记区分。SHAD通过在样本间打乱输入和输出组合后观察预测性差异来进行标记分类：模板标记由于在样本间具有重复性，保持预测性，而推理标记则不具有这种特性。利用SHAD，我们提出了推理突出的微调方法（RFT），该方法在微调过程中自适应地强调推理标记，与常见监督微调（SFT）相比，显示出显著的性能提升。 

---
# ALKAFI-LLAMA3: Fine-Tuning LLMs for Precise Legal Understanding in Palestine 

**Title (ZH)**: ALKAFI-LLAMA3：针对巴勒斯坦精准法律理解的大型语言模型 fine-tuning 

**Authors**: Rabee Qasem, Mohannad Hendi, Banan Tantour  

**Link**: [PDF](https://arxiv.org/pdf/2412.14771)  

**Abstract**: Large Language Models (LLMs) have demonstrated remarkable potential in diverse domains, yet their application in the legal sector, particularly in low-resource contexts, remains limited. This study addresses the challenges of adapting LLMs to the Palestinian legal domain, where political instability, fragmented legal frameworks, and limited AI resources hinder effective machine-learning applications. We present a fine-tuned model based on a quantized version of Llama-3.2-1B-Instruct, trained on a synthetic data set derived from Palestinian legal texts. Using smaller-scale models and strategically generated question-answer pairs, we achieve a cost-effective, locally sustainable solution that provides accurate and contextually relevant legal guidance. Our experiments demonstrate promising performance on various query types, ranging from yes/no questions and narrative explanations to complex legal differentiations, while highlighting areas for improvement, such as handling calculation-based inquiries and structured list formatting. This work provides a pathway for the deployment of AI-driven legal assistance tools tailored to the needs of resource-constrained environments. 

**Abstract (ZH)**: 大型语言模型（LLMs）在多个领域展现出了显著的潜力，但在法律领域的应用，特别是在资源匮乏的环境中，仍受到限制。本研究旨在解决将LLMs适应到巴勒斯坦法律领域的挑战，由于政治不稳定、法律框架碎片化以及有限的人工智能资源，有效地利用机器学习应用受到阻碍。我们基于量化版本的Llama-3.2-1B-Instruct构建了一个微调模型，并训练了该模型，所用数据集来源于巴勒斯坦法律文本。通过使用规模较小的模型和精心设计的问题-答案对，我们实现了一种成本效益高、具有地方可持续性的解决方案，能够提供准确且上下文相关性的法律指导。我们的实验表明，该模型在各种查询类型上表现出了令人鼓舞的效果，涵盖了从是/否问题和叙事解释到复杂法律区分在内的多种查询，同时我们也指出了改进的方向，比如处理基于计算的查询和结构化列表格式化等问题。本研究为定制化的人工智能法律辅助工具的部署提供了一条途径，以适应资源匮乏的环境需求。 

---
# Query pipeline optimization for cancer patient question answering systems 

**Title (ZH)**: 癌症患者问答系统中查询管道的优化方法 

**Authors**: Maolin He, Rena Gao, Mike Conway, Brian E. Chapman  

**Link**: [PDF](https://arxiv.org/pdf/2412.14751)  

**Abstract**: Retrieval-augmented generation (RAG) mitigates hallucination in Large Language Models (LLMs) by using query pipelines to retrieve relevant external information and grounding responses in retrieved knowledge. However, query pipeline optimization for cancer patient question-answering (CPQA) systems requires separately optimizing multiple components with domain-specific considerations. We propose a novel three-aspect optimization approach for the RAG query pipeline in CPQA systems, utilizing public biomedical databases like PubMed and PubMed Central. Our optimization includes: (1) document retrieval, utilizing a comparative analysis of NCBI resources and introducing Hybrid Semantic Real-time Document Retrieval (HSRDR); (2) passage retrieval, identifying optimal pairings of dense retrievers and rerankers; and (3) semantic representation, introducing Semantic Enhanced Overlap Segmentation (SEOS) for improved contextual understanding. On a custom-developed dataset tailored for cancer-related inquiries, our optimized RAG approach improved the answer accuracy of Claude-3-haiku by 5.24% over chain-of-thought prompting and about 3% over a naive RAG setup. This study highlights the importance of domain-specific query optimization in realizing the full potential of RAG and provides a robust framework for building more accurate and reliable CPQA systems, advancing the development of RAG-based biomedical systems. 

**Abstract (ZH)**: 检索增强生成（RAG）通过使用查询管道检索相关外部信息并在检索到的知识基础上确立响应，从而缓解了大型语言模型（LLMs）中的幻觉现象。然而，针对癌症患者问答（CPQA）系统的查询管道优化需要分别优化多个具有领域特定考虑的组件。我们提出了一种针对CPQA系统中RAG查询管道的新型三方面优化方法，利用PubMed和PubMed Central等公共生物医学数据库。我们的优化包括：（1）文档检索，采用NCBI资源的比较分析，并引入了混合语义实时文档检索（HSRDR）；（2）段落检索，确定密集检索器和排序器的最佳配对；（3）语义表示，引入语义增强重叠分割（SEOS），以提高上下文理解能力。在针对癌症相关查询定制开发的数据集上，我们优化的RAG方法在回答精度方面提高了Claude-3-haiku约5.24%，并且相对于链式思考提示（chain-of-thought prompting）高约3%，相对于原始的RAG设置高约3%。本研究强调了在实现RAG潜力方面领域特定查询优化的重要性，并提供了一个强大的框架，用于构建更准确可靠的CPQA系统，推动基于RAG的生物医学系统的发展。 

---
# On Verbalized Confidence Scores for LLMs 

**Title (ZH)**: 关于语音表达的置信分数对于大语言模型的研究 

**Authors**: Daniel Yang, Yao-Hung Hubert Tsai, Makoto Yamada  

**Link**: [PDF](https://arxiv.org/pdf/2412.14737)  

**Abstract**: The rise of large language models (LLMs) and their tight integration into our daily life make it essential to dedicate efforts towards their trustworthiness. Uncertainty quantification for LLMs can establish more human trust into their responses, but also allows LLM agents to make more informed decisions based on each other's uncertainty. To estimate the uncertainty in a response, internal token logits, task-specific proxy models, or sampling of multiple responses are commonly used. This work focuses on asking the LLM itself to verbalize its uncertainty with a confidence score as part of its output tokens, which is a promising way for prompt- and model-agnostic uncertainty quantification with low overhead. Using an extensive benchmark, we assess the reliability of verbalized confidence scores with respect to different datasets, models, and prompt methods. Our results reveal that the reliability of these scores strongly depends on how the model is asked, but also that it is possible to extract well-calibrated confidence scores with certain prompt methods. We argue that verbalized confidence scores can become a simple but effective and versatile uncertainty quantification method in the future. Our code is available at this https URL . 

**Abstract (ZH)**: 大型语言模型（LLMs）的兴起及其与我们日常生活紧密结合，使得致力于提升其可信度变得至关重要。对LLMs进行不确定性量化可以增强人们对它们响应的信任度，同时也使LLM代理能够基于彼此的不确定性做出更加明智的决策。为了估计响应的不确定性，通常使用内部标记概率、任务特定的代理模型或多次响应采样。本研究关注让LLM自己以置信度分数的形式在其输出标记中口头表达其不确定性，这是一种具有低开销的提示和模型无关的不确定性量化方法的有前景方式。通过广泛的标准测试基准，我们评估了口头表达的置信度分数在不同数据集、模型和提示方法方面的可靠性。我们的研究结果表明，这些分数的可靠性高度依赖于模型的提问方式，但也表明通过特定的提示方法可以提取出校准良好的置信度分数。我们认为，口头表达的置信度分数在未来可以成为一种简单但有效且多功能的不确定性量化方法。我们的代码可在以下链接获取：[此处提供链接]。 

---
# LLMs as mediators: Can they diagnose conflicts accurately? 

**Title (ZH)**: LLMs作为调解者：它们能否准确诊断冲突？ 

**Authors**: Özgecan Koçak, Phanish Puranam, Afşar Yegin  

**Link**: [PDF](https://arxiv.org/pdf/2412.14675)  

**Abstract**: Prior research indicates that to be able to mediate conflict, observers of disagreements between parties must be able to reliably distinguish the sources of their disagreement as stemming from differences in beliefs about what is true (causality) vs. differences in what they value (morality). In this paper, we test if OpenAI's Large Language Models GPT 3.5 and GPT 4 can perform this task and whether one or other type of disagreement proves particularly challenging for LLM's to diagnose. We replicate study 1 in Koçak et al. (2003), which employes a vignette design, with OpenAI's GPT 3.5 and GPT 4. We find that both LLMs have similar semantic understanding of the distinction between causal and moral codes as humans and can reliably distinguish between them. When asked to diagnose the source of disagreement in a conversation, both LLMs, compared to humans, exhibit a tendency to overestimate the extent of causal disagreement and underestimate the extent of moral disagreement in the moral misalignment condition. This tendency is especially pronounced for GPT 4 when using a proximate scale that relies on concrete language specific to an issue. GPT 3.5 does not perform as well as GPT4 or humans when using either the proximate or the distal scale. The study provides a first test of the potential for using LLMs to mediate conflict by diagnosing the root of disagreements in causal and evaluative codes. 

**Abstract (ZH)**: 先前的研究表明，观察者要在双方争端中充当调解人，必须能够可靠地区分他们分歧的来源是基于对事实的理解差异（因果性）还是基于价值观的差异（道德性）。本研究旨在测试OpenAI的大语言模型GPT 3.5和GPT 4是否能够完成这一任务，并且探究是哪种类型的分歧对大语言模型来说更加具有挑战性。我们复制了Koçak等人（2003）的研究，该研究采用了情景描述的设计，使用了OpenAI的GPT 3.5和GPT 4进行实验。我们发现，这两种大语言模型在区分因果性和道德性方面的语义理解与人类相似，并且能够可靠地区分这两者。

当被要求诊断对话中的分歧来源时，与人类相比，这两种大语言模型在道德不一致的情况下都有倾向于高估因果性分歧并低估道德性分歧的倾向。特别是使用与具体问题相关的具体语言构建的邻近尺度时，这种倾向对于GPT 4尤为显著。GPT 3.5在使用邻近尺度和远端尺度时的表现都不及GPT 4或人类。该研究提供了大语言模型通过诊断因果性和评价性代码的分歧根源来调解冲突的潜在能力的初步测试。 

---
# Length Controlled Generation for Black-box LLMs 

**Title (ZH)**: 长度可控生成用于黑盒大语言模型 

**Authors**: Yuxuan Gu, Wenjie Wang, Xiaocheng Feng, Weihong Zhong, Kun Zhu, Lei Huang, Tat-Seng Chua, Bing Qin  

**Link**: [PDF](https://arxiv.org/pdf/2412.14656)  

**Abstract**: Large language models (LLMs) have demonstrated impressive instruction following capabilities, while still struggling to accurately manage the length of the generated text, which is a fundamental requirement in many real-world applications. Existing length control methods involve fine-tuning the parameters of LLMs, which is inefficient and suboptimal for practical use. In this paper, we propose a novel iterative sampling framework for text length control, integrating the Metropolis-Hastings algorithm with an importance sampling acceleration strategy. This framework efficiently and reliably regulates LLMs to generate length-constrained text without modifying the underlying parameters, thereby preserving the original capabilities of LLMs. Experimental results demonstrate that our framework achieves almost 100\% success rates of length control on Llama3.1 for tasks such as length-controlled abstractive summarization and length-constrained instruction following, with minimal additional computational overhead. This also highlights the significant potential of our method for precise length control across a broader range of applications, without compromising the versatility of LLMs. 

**Abstract (ZH)**: 大型语言模型（LLMs）在指令遵循方面展现了令人印象深刻的性能，但在生成文本长度控制方面仍然存在挑战，这是许多实际应用中的一个基本要求。现有的长度控制方法通常涉及对LLMs参数的微调，这在实际使用中既无效率又不太理想。本文提出了一种新颖的迭代采样框架，结合了Metropolis-Hastings算法和重要性采样加速策略，以高效且可靠地调节LLMs生成长度受限的文本，且无需修改底层参数，从而保持了LLMs的原始能力。实验结果表明，该框架在Llama3.1上实现了几乎100%的任务长度控制成功率，适用于长度受控的摘要生成和长度受限的指令遵循等任务，且附加的计算开销 minimal。这还突显了该方法在更广泛的应用中实现精确长度控制的巨大潜力，而不牺牲LLMs的灵活性。 

---
# Learning to Generate Research Idea with Dynamic Control 

**Title (ZH)**: 学习使用动态控制生成研究思路 

**Authors**: Ruochen Li, Liqiang Jing, Chi Han, Jiawei Zhou, Xinya Du  

**Link**: [PDF](https://arxiv.org/pdf/2412.14626)  

**Abstract**: The rapid advancements in large language models (LLMs) have demonstrated their potential to accelerate scientific discovery, particularly in automating the process of research ideation. LLM-based systems have shown promise in generating hypotheses and research ideas. However, current approaches predominantly rely on prompting-based pre-trained models, limiting their ability to optimize generated content effectively. Moreover, they also lack the capability to deal with the complex interdependence and inherent restrictions among novelty, feasibility, and effectiveness, which remains challenging due to the inherent trade-offs among these dimensions, such as the innovation-feasibility conflict. To address these limitations, we for the first time propose fine-tuning LLMs to be better idea proposers and introduce a novel framework that employs a two-stage approach combining Supervised Fine-Tuning (SFT) and controllable Reinforcement Learning (RL). In the SFT stage, the model learns foundational patterns from pairs of research papers and follow-up ideas. In the RL stage, multi-dimensional reward modeling, guided by fine-grained feedback, evaluates and optimizes the generated ideas across key metrics. Dimensional controllers enable dynamic adjustment of generation, while a sentence-level decoder ensures context-aware emphasis during inference. Our framework provides a balanced approach to research ideation, achieving high-quality outcomes by dynamically navigating the trade-offs among novelty, feasibility, and effectiveness. 

**Abstract (ZH)**: 大规模语言模型（LLMs）的快速进步已经显示出它们在加速科学发现方面的潜力，尤其是在自动化研究构思过程方面。基于LLM的系统展示了生成假设和研究构思的潜力。然而，当前的方法主要依赖于基于提示的预训练模型，这限制了它们在优化生成内容方面的有效性。此外，这些系统还缺乏处理新颖性、可行性和有效性之间复杂相互依赖关系的能力，这些相互依赖关系因这些维度之间的固有权衡而更具挑战性，例如创新与可行性的冲突。为了解决这些局限性，我们首次提出对LLM进行微调，以使其更好地提出研究构思，并介绍了一种新的框架，该框架采用结合监督微调（SFT）和可控强化学习（RL）的两阶段方法。在SFT阶段，模型从研究论文及其后续构思的配对中学习基础模式。在RL阶段，通过精细反馈引导的多维度奖励模型评估并优化生成的内容，确保在关键指标上取得最优效果。维度控制器使生成过程可以动态调整，而句子级解码器确保在推理过程中对上下文有意识地强调。我们的框架提供了一种平衡的研究构思方法，在动态导航新颖性、可行性和有效性之间的权衡时，实现了高质量的结果。 

---
# How good is GPT at writing political speeches for the White House? 

**Title (ZH)**: GPT在为白宫撰写政治演说方面做得如何？ 

**Authors**: Jacques Savoy  

**Link**: [PDF](https://arxiv.org/pdf/2412.14617)  

**Abstract**: Using large language models (LLMs), computers are able to generate a written text in response to a us er request. As this pervasive technology can be applied in numerous contexts, this study analyses the written style of one LLM called GPT by comparing its generated speeches with those of the recent US presidents. To achieve this objective, the State of the Union (SOTU) addresses written by Reagan to Biden are contrasted to those produced by both GPT-3.5 and GPT-4.o versions. Compared to US presidents, GPT tends to overuse the lemma "we" and produce shorter messages with, on average, longer sentences. Moreover, GPT opts for an optimistic tone, opting more often for political (e.g., president, Congress), symbolic (e.g., freedom), and abstract terms (e.g., freedom). Even when imposing an author's style to GPT, the resulting speech remains distinct from addresses written by the target author. Finally, the two GPT versions present distinct characteristics, but both appear overall dissimilar to true presidential messages. 

**Abstract (ZH)**: 利用大规模语言模型（LLMs），计算机能够根据用户请求生成书面文本。由于这项普及的技术可以在众多领域应用，本研究通过将一个名为GPT的LLM生成的演讲与近期美国总统的演讲进行比较，分析了GPT的书面风格。具体而言，本研究对比了里根至拜登历任总统发表的国情咨文（SOTU）与由GPT-3.5和GPT-4版本生成的版本。相较于美国总统，GPT有过度使用“we”这一词汇的现象，并生成更短的信息，平均而言，其句子更长。此外，GPT倾向于采用更乐观的语调，更频繁地使用政治性术语（如总统、国会）、象征性术语（如自由）和抽象性术语（如自由）。即使强加给GPT某种作者的风格，生成的演讲仍然与目标作者的演讲风格有所不同。最后，两种GPT版本呈现出不同的特点，但总体上与真正的总统演讲相异。 

---
# Beyond Guilt: Legal Judgment Prediction with Trichotomous Reasoning 

**Title (ZH)**: 超越罪责：基于三元推理的法律判决预测 

**Authors**: Kepu Zhang, Haoyue Yang, Xu Tang, Weijie Yu, Jun Xu  

**Link**: [PDF](https://arxiv.org/pdf/2412.14588)  

**Abstract**: In legal practice, judges apply the trichotomous dogmatics of criminal law, sequentially assessing the elements of the offense, unlawfulness, and culpability to determine whether an individual's conduct constitutes a crime. Although current legal large language models (LLMs) show promising accuracy in judgment prediction, they lack trichotomous reasoning capabilities due to the absence of an appropriate benchmark dataset, preventing them from predicting innocent outcomes. As a result, every input is automatically assigned a charge, limiting their practical utility in legal contexts. To bridge this gap, we introduce LJPIV, the first benchmark dataset for Legal Judgment Prediction with Innocent Verdicts. Adhering to the trichotomous dogmatics, we extend three widely-used legal datasets through LLM-based augmentation and manual verification. Our experiments with state-of-the-art legal LLMs and novel strategies that integrate trichotomous reasoning into zero-shot prompting and fine-tuning reveal: (1) current legal LLMs have significant room for improvement, with even the best models achieving an F1 score of less than 0.3 on LJPIV; and (2) our strategies notably enhance both in-domain and cross-domain judgment prediction accuracy, especially for cases resulting in an innocent verdict. 

**Abstract (ZH)**: 在法律实践中，法官根据刑事法律的三元理论，依次评估犯罪行为的构成要素、非法性和故意性，以确定某人的行为是否构成犯罪。尽管现有的法律大型语言模型（LLMs）在判决预测方面展现出令人鼓舞的准确性，但由于缺乏适当的基准数据集，它们缺乏三元推理能力，因此无法预测无罪判决。因此，每一个输入都被自动分配一个罪名，限制了它们在法律环境中的实际应用价值。为了解决这一问题，我们提出了LJPIV，即首个包含无罪判决的法律判决预测基准数据集。根据三元理论，我们通过基于LLM的数据扩增和人工验证，扩展了三个广泛使用的法律数据集。我们的实验使用最新的法律LLMs和新的策略，这些策略将三元推理集成到零样本提示和微调中，结果显示：（1）当前的法律LLMs有着显著的改进空间，即使是最佳模型在LJPIV上的F1分数也低于0.3；（2）我们的策略显著提高了领域内和跨领域的判决预测准确性，特别是在预测无罪判决的案件中效果尤为明显。 

---
# Simulation-Free Hierarchical Latent Policy Planning for Proactive Dialogues 

**Title (ZH)**: 无模拟层次潜在策略规划以实现主动对话 

**Authors**: Tao He, Lizi Liao, Yixin Cao, Yuanxing Liu, Yiheng Sun, Zerui Chen, Ming Liu, Bing Qin  

**Link**: [PDF](https://arxiv.org/pdf/2412.14584)  

**Abstract**: Recent advancements in proactive dialogues have garnered significant attention, particularly for more complex objectives (e.g. emotion support and persuasion). Unlike traditional task-oriented dialogues, proactive dialogues demand advanced policy planning and adaptability, requiring rich scenarios and comprehensive policy repositories to develop such systems. However, existing approaches tend to rely on Large Language Models (LLMs) for user simulation and online learning, leading to biases that diverge from realistic scenarios and result in suboptimal efficiency. Moreover, these methods depend on manually defined, context-independent, coarse-grained policies, which not only incur high expert costs but also raise concerns regarding their completeness. In our work, we highlight the potential for automatically discovering policies directly from raw, real-world dialogue records. To this end, we introduce a novel dialogue policy planning framework, LDPP. It fully automates the process from mining policies in dialogue records to learning policy planning. Specifically, we employ a variant of the Variational Autoencoder to discover fine-grained policies represented as latent vectors. After automatically annotating the data with these latent policy labels, we propose an Offline Hierarchical Reinforcement Learning (RL) algorithm in the latent space to develop effective policy planning capabilities. Our experiments demonstrate that LDPP outperforms existing methods on two proactive scenarios, even surpassing ChatGPT with only a 1.8-billion-parameter LLM. 

**Abstract (ZH)**: 近年来，主动对话领域取得了显著进展，特别适用于更复杂的任务（如情绪支持和说服）。与传统的任务导向对话不同，主动对话要求进行高级策略规划和适应性，需要丰富的场景和全面的策略仓库来开发此类系统。然而，现有的方法往往依赖大型语言模型（LLMs）进行用户模拟和在线学习，这导致了与现实场景不符的偏差，从而降低了效率。此外，这些方法依赖于手动定义的、与上下文无关的、粗粒度的策略，不仅增加了专家成本，还引发了其完整性方面的担忧。在我们的工作中，我们强调了从原始的对话记录中自动发现策略的潜力。为此，我们提出了一个新的对话策略规划框架——LDPP。它完全自动化了从挖掘对话记录中的策略到学习策略规划的整个过程。具体而言，我们采用了一种变分自动编码器的变体来发现作为潜在向量表示的细粒度策略。在自动为数据添加这些潜在策略标签后，我们提出了一种在潜在空间中的脱机分层强化学习（RL）算法，以开发有效的策略规划能力。实验结果表明，LDPP在两个主动对话场景中均优于现有方法，甚至仅凭一个参数量为1.8亿的LLM便超越了ChatGPT。 

---
# CitaLaw: Enhancing LLM with Citations in Legal Domain 

**Title (ZH)**: CitaLaw：在法律领域增强语言模型的引注技术 

**Authors**: Kepu Zhang, Weijie Yu, Sunhao Dai, Jun Xu  

**Link**: [PDF](https://arxiv.org/pdf/2412.14556)  

**Abstract**: In this paper, we propose CitaLaw, the first benchmark designed to evaluate LLMs' ability to produce legally sound responses with appropriate citations. CitaLaw features a diverse set of legal questions for both laypersons and practitioners, paired with a comprehensive corpus of law articles and precedent cases as a reference pool. This framework enables LLM-based systems to retrieve supporting citations from the reference corpus and align these citations with the corresponding sentences in their responses. Moreover, we introduce syllogism-inspired evaluation methods to assess the legal alignment between retrieved references and LLM-generated responses, as well as their consistency with user questions. Extensive experiments on 2 open-domain and 7 legal-specific LLMs demonstrate that integrating legal references substantially enhances response quality. Furthermore, our proposed syllogism-based evaluation method exhibits strong agreement with human judgments. 

**Abstract (ZH)**: 在本文中，我们提出了CitaLaw，这是第一个用于评估大规模语言模型（LLM）生成合法且具适当引用的响应能力的标准基准。CitaLaw包含了一系列适用于普通民众和专业人士的多样化法律问题，并配有完整的法律文章和先例案例的参考库。该框架使基于LLM的系统能够从参考库中检索支持引文，并将这些引文与响应中的相应句子对齐。此外，我们引入了灵感源自三段论的评估方法，用于评估检索到的参考信息与LLM生成的响应之间的法律匹配度以及其与用户问题的一致性。在2个开放领域和7个法律特定的LLM上的广泛实验表明，整合法律参考极大地提高了响应质量。此外，我们提出的方法基于三段论的评估标准与人类判断表现出很强的一致性。 

---
# PA-RAG: RAG Alignment via Multi-Perspective Preference Optimization 

**Title (ZH)**: PA-RAG：多视角偏好优化下的RAG对齐 

**Authors**: Jiayi Wu, Hengyi Cai, Lingyong Yan, Hao Sun, Xiang Li, Shuaiqiang Wang, Dawei Yin, Ming Gao  

**Link**: [PDF](https://arxiv.org/pdf/2412.14510)  

**Abstract**: The emergence of Retrieval-augmented generation (RAG) has alleviated the issues of outdated and hallucinatory content in the generation of large language models (LLMs), yet it still reveals numerous limitations. When a general-purpose LLM serves as the RAG generator, it often suffers from inadequate response informativeness, response robustness, and citation quality. Past approaches to tackle these limitations, either by incorporating additional steps beyond generating responses or optimizing the generator through supervised fine-tuning (SFT), still failed to align with the RAG requirement thoroughly. Consequently, optimizing the RAG generator from multiple preference perspectives while maintaining its end-to-end LLM form remains a challenge. To bridge this gap, we propose Multiple Perspective Preference Alignment for Retrieval-Augmented Generation (PA-RAG), a method for optimizing the generator of RAG systems to align with RAG requirements comprehensively. Specifically, we construct high-quality instruction fine-tuning data and multi-perspective preference data by sampling varied quality responses from the generator across different prompt documents quality scenarios. Subsequently, we optimize the generator using SFT and Direct Preference Optimization (DPO). Extensive experiments conducted on four question-answer datasets across three LLMs demonstrate that PA-RAG can significantly enhance the performance of RAG generators. Our code and datasets are available at this https URL. 

**Abstract (ZH)**: 检索增强生成（RAG）的出现缓解了大型语言模型（LLMs）生成过程中出现内容过时和幻觉的问题，但仍暴露了诸多局限性。当通用的LLM用作RAG生成器时，它通常会遭受响应信息不足、响应稳健性差和引文质量低的问题。过去为解决这些局限性的方法，要么通过生成响应之外的额外步骤，要么通过监督微调（SFT）来优化生成器，都没有完全满足RAG的要求。因此，从多方面优化RAG生成器同时保持其端到端的大语言模型形式仍是一项挑战。为了填补这一空白，我们提出了一种多视角偏好对齐方法——PA-RAG（偏好对齐的RAG），该方法旨在全面优化RAG系统的生成器以满足RAG的要求。具体来说，我们通过在不同提示文档质量情景下采样生成器生成的多种质量的指令，构建高质量的指令微调数据和多视角偏好数据。随后，我们使用监督微调（SFT）和直接偏好优化（DPO）来优化生成器。在三个LLM上进行的四个问答数据集的广泛实验表明，PA-RAG能够显著提高RAG生成器的性能。我们的代码和数据集可在此处访问：[此链接]。 

---
# Why We Build Local Large Language Models: An Observational Analysis from 35 Japanese and Multilingual LLMs 

**Title (ZH)**: 我们构建本地大型语言模型的原因：来自35个日语和多语言LLM的观察性分析 

**Authors**: Koshiro Saito, Sakae Mizuki, Masanari Ohi, Taishi Nakamura, Taihei Shiotani, Koki Maeda, Youmi Ma, Kakeru Hattori, Kazuki Fujii, Takumi Okamoto, Shigeki Ishida, Hiroya Takamura, Rio Yokota, Naoaki Okazaki  

**Link**: [PDF](https://arxiv.org/pdf/2412.14471)  

**Abstract**: Why do we build local large language models (LLMs)? What should a local LLM learn from the target language? Which abilities can be transferred from other languages? Do language-specific scaling laws exist? To explore these research questions, we evaluated 35 Japanese, English, and multilingual LLMs on 19 evaluation benchmarks for Japanese and English, taking Japanese as a local language. Adopting an observational approach, we analyzed correlations of benchmark scores, and conducted principal component analysis (PCA) on the scores to derive \textit{ability factors} of local LLMs. We found that training on English text can improve the scores of academic subjects in Japanese (JMMLU). In addition, it is unnecessary to specifically train on Japanese text to enhance abilities for solving Japanese code generation, arithmetic reasoning, commonsense, and reading comprehension tasks. In contrast, training on Japanese text could improve question-answering tasks about Japanese knowledge and English-Japanese translation, which indicates that abilities for solving these two tasks can be regarded as \textit{Japanese abilities} for LLMs. Furthermore, we confirmed that the Japanese abilities scale with the computational budget for Japanese text. 

**Abstract (ZH)**: 我们为什么要构建本地大型语言模型（LLMs）？本地LLMs应该从目标语言中学到哪些能力？其他语言的能力能被转移到目标语言中吗？特定语言是否存在规模扩展定律？为了探索这些问题，我们对35个日语、英语和多语言LLMs在19个日语和英语评估基准测试中进行了评估，将日语作为本地语言进行研究。通过观测方法，我们分析了基准测试分数的相关性，并通过对分数进行主成分分析（PCA）来推导出本地LLMs的能力因子。我们发现，使用英语文本进行训练可以提高日语学术科目（JMMLU）的分数。此外，增强解决日语代码生成、算术推理、常识和阅读理解任务的能力，不需要专门使用日语文本进行训练。相比之下，使用日语文本进行训练可以在日语知识问答任务和英语-日语翻译任务上提高性能，这表明解决这两种任务的能力可以被视为LLMs的“日语能力”。此外，我们确认了日语能力与日语文本的计算预算之间存在规模扩展关系。 

---
# Agent-SafetyBench: Evaluating the Safety of LLM Agents 

**Title (ZH)**: Agent-SafetyBench: 评估大规模语言模型代理的安全性 

**Authors**: Zhexin Zhang, Shiyao Cui, Yida Lu, Jingzhuo Zhou, Junxiao Yang, Hongning Wang, Minlie Huang  

**Link**: [PDF](https://arxiv.org/pdf/2412.14470)  

**Abstract**: As large language models (LLMs) are increasingly deployed as agents, their integration into interactive environments and tool use introduce new safety challenges beyond those associated with the models themselves. However, the absence of comprehensive benchmarks for evaluating agent safety presents a significant barrier to effective assessment and further improvement. In this paper, we introduce Agent-SafetyBench, a comprehensive benchmark designed to evaluate the safety of LLM agents. Agent-SafetyBench encompasses 349 interaction environments and 2,000 test cases, evaluating 8 categories of safety risks and covering 10 common failure modes frequently encountered in unsafe interactions. Our evaluation of 16 popular LLM agents reveals a concerning result: none of the agents achieves a safety score above 60%. This highlights significant safety challenges in LLM agents and underscores the considerable need for improvement. Through quantitative analysis, we identify critical failure modes and summarize two fundamental safety detects in current LLM agents: lack of robustness and lack of risk awareness. Furthermore, our findings suggest that reliance on defense prompts alone is insufficient to address these safety issues, emphasizing the need for more advanced and robust strategies. We release Agent-SafetyBench at \url{this https URL} to facilitate further research and innovation in agent safety evaluation and improvement. 

**Abstract (ZH)**: 随着大规模语言模型（LLMs）被越来越多地用作代理角色，它们在交互环境中的整合和工具使用引入了与模型本身相关的新安全挑战。然而，缺乏全面的评估标准来衡量代理安全性，这成为有效评估和进一步改进的重要障碍。本文介绍了一种名为Agent-SafetyBench的综合性基准，旨在评估LLM代理的安全性。Agent-SafetyBench涵盖了349种交互环境和2000个测试案例，评估了8类安全风险，并涵盖了10种常见的不安全交互中频繁出现的失败模式。我们的评估显示了16种流行LLM代理的结果：没有一个代理的安全评分超过60%。这一结果突出了LLM代理在安全性方面的重要挑战，并强调了改进的迫切需求。通过定量分析，我们识别了关键的失败模式，并总结了当前LLM代理中的两种基本安全检测：缺乏鲁棒性和缺乏风险意识。此外，我们的研究结果表明，仅仅依赖防御提示是不足以解决这些安全问题的，强调了需要采取更先进和可靠的策略。我们在此处发布Agent-SafetyBench（\url{this https URL}），以便进一步促进代理安全性评估和改进的研究与创新。 

---
# From Human Annotation to LLMs: SILICON Annotation Workflow for Management Research 

**Title (ZH)**: 从人工标注到LLM：SILICON标注工作流程在管理研究中的应用 

**Authors**: Xiang Cheng, Raveesh Mayya, João Sedoc  

**Link**: [PDF](https://arxiv.org/pdf/2412.14461)  

**Abstract**: Unstructured text data annotation and analysis are fundamental to management research, often relying on human annotators through crowdsourcing platforms. While Large Language Models (LLMs) promise to provide a cost-effective and efficient alternative to human annotation, there lacks a systematic workflow that evaluate when LLMs are suitable or how to proceed with LLM-based text annotation in a reproducible manner. This paper addresses this methodological gap by introducing the ``SILICON" (\textbf{S}ystematic \textbf{I}nference with \textbf{L}LMs for \textbf{I}nformation \textbf{C}lassificati\textbf{o}n and \textbf{N}otation) workflow. The workflow integrates established principles of human annotation with systematic prompt optimization and model selection, addressing challenges such as developing robust annotation guidelines, establishing high-quality human baselines, optimizing prompts, and ensuring reproducibility across LLMs. We validate the SILICON workflow through seven case studies covering common management research tasks, including business proposal evaluation, dialog intent and breakdown analysis, review attribute detection. Our findings highlight the importance of validating annotation guideline agreement, the superiority of expert-developed human baselines over crowdsourced ones, the iterative nature of prompt optimization, and the necessity of testing multiple LLMs. Notably, we propose a regression-based methodology to empirically compare LLM outputs across prompts and models. Our workflow advances management research by establishing reproducible processes for LLM-based annotation that maintain scientific rigor. We provide practical guidance for researchers to effectively navigate the evolving landscape of generative AI tools effectively while maintaining transparency and reproducibility. 

**Abstract (ZH)**: 无结构文本数据的标注和分析是管理研究的基础，通常依赖于通过众包平台的人工标注者。虽然大型语言模型（LLMs）提供了成本效益更高且更高效的替代方案，但缺乏系统的工作流程来评估LLMs的适用性或在具有可重复性的情况下如何进行基于LLM的文本标注。本文通过引入“SILICON”（系统化的LLMs在信息分类与标注中的推断）工作流程解决了这一方法论上的缺口。该工作流程将人类标注的基本原则与系统化的提示优化和模型选择相结合，解决了诸如制定稳健的标注指南、建立高质量的人类基准、优化提示以及在不同LLM之间确保可重复性等挑战。

我们通过七个案例研究验证了SILICON工作流程，涵盖常见的管理研究任务，包括商业提案评估、对话意图和分析、评论属性检测等。我们的研究结果强调了验证标注指南一致性的重要性、专家开发的人类基准优于众包基准、提示优化的迭代性质以及测试多种LLM的必要性。值得注意的是，我们提出了基于回归的方法来实证比较不同提示和模型下的LLM输出效果。我们的工作流程推动了管理研究的进步，通过建立基于LLM的标注的可重复过程，保持科学严谨性。

我们为研究人员提供实用的指导，帮助他们有效地利用不断发展中的生成性AI工具，同时保持透明性和可重复性。 

---
# All-in-One Tuning and Structural Pruning for Domain-Specific LLMs 

**Title (ZH)**: 面向特定领域的大型语言模型的一站式调优与结构剪枝 

**Authors**: Lei Lu, Zhepeng Wang, Ruexue Bao, Mengbing Wang, Fangyi Li, Yawen Wu, Weiwen Jiang, Jie Xu, Yanzhi Wang, Shangqian Gao  

**Link**: [PDF](https://arxiv.org/pdf/2412.14426)  

**Abstract**: Existing pruning techniques for large language models (LLMs) targeting domain-specific applications typically follow a two-stage process: pruning the pretrained general-purpose LLMs and then fine-tuning the pruned LLMs on specific domains. However, the pruning decisions, derived from the pretrained weights, remain unchanged during fine-tuning, even if the weights have been updated. Therefore, such a combination of the pruning decisions and the finetuned weights may be suboptimal, leading to non-negligible performance degradation. To address these limitations, we propose ATP: All-in-One Tuning and Structural Pruning, a unified one-stage structural pruning and fine-tuning approach that dynamically identifies the current optimal substructure throughout the fine-tuning phase via a trainable pruning decision generator. Moreover, given the limited available data for domain-specific applications, Low-Rank Adaptation (LoRA) becomes a common technique to fine-tune the LLMs. In ATP, we introduce LoRA-aware forward and sparsity regularization to ensure that the substructures corresponding to the learned pruning decisions can be directly removed after the ATP process. ATP outperforms the state-of-the-art two-stage pruning methods on tasks in the legal and healthcare domains. More specifically, ATP recovers up to 88% and 91% performance of the dense model when pruning 40% parameters of LLaMA2-7B and LLaMA3-8B models, respectively. 

**Abstract (ZH)**: 面向领域特定应用的大型语言模型（LLMs）现有的剪枝技术通常遵循两个阶段的过程：首先对预训练的通用LLMs进行剪枝，然后在特定领域对其进行微调。然而，在微调过程中，从预训练权重得出的剪枝决策保持不变，即使权重已被更新。因此，这种剪枝决策与微调权重的结合可能不是最优的，导致性能显著下降。为了解决这些局限性，我们提出了一种统一的一站式结构剪枝和微调方法——All-in-One Tuning and Structural Pruning（ATP）。ATP通过可训练的剪枝决策生成器动态识别微调过程中的最优子结构。此外，由于领域特定应用可用数据有限，低秩适应（LoRA）成为了一种常用方法来微调LLMs。在ATP中，我们引入了LoRA感知的前向传播和稀疏正则化，以确保在ATP处理后，根据学习到的剪枝决策得到的子结构可以被直接移除。实验结果显示，ATP在法律和医疗领域的任务上优于最先进的两阶段剪枝方法。具体而言，当分别对LLaMA2-7B和LLaMA3-8B模型剪枝40%的参数时，ATP分别恢复了88%和91%的密集模型性能。 

---
# A Survey on LLM Inference-Time Self-Improvement 

**Title (ZH)**: LLM 推理时自我改进综述 

**Authors**: Xiangjue Dong, Maria Teleki, James Caverlee  

**Link**: [PDF](https://arxiv.org/pdf/2412.14352)  

**Abstract**: Techniques that enhance inference through increased computation at test-time have recently gained attention. In this survey, we investigate the current state of LLM Inference-Time Self-Improvement from three different perspectives: Independent Self-improvement, focusing on enhancements via decoding or sampling methods; Context-Aware Self-Improvement, leveraging additional context or datastore; and Model-Aided Self-Improvement, achieving improvement through model collaboration. We provide a comprehensive review of recent relevant studies, contribute an in-depth taxonomy, and discuss challenges and limitations, offering insights for future research. 

**Abstract (ZH)**: 在测试时通过增加计算来增强推理的技术最近受到了广泛关注。本文从三个不同的视角对该领域的现状进行了调查：独立自我改进，重点关注通过解码或采样方法的增强；上下文感知自我改进，利用额外的上下文或数据存储；以及模型辅助自我改进，通过模型协作实现改进。我们对最近的相关研究进行了全面回顾，贡献了一套深入的分类体系，并讨论了面临的挑战和局限性，为未来的研究提供了见解。 

---
# Multi-OphthaLingua: A Multilingual Benchmark for Assessing and Debiasing LLM Ophthalmological QA in LMICs 

**Title (ZH)**: Multilingual OphthaLingua：评估和去偏见LM在LMICs中眼科QA的多语言基准荏 

**Authors**: David Restrepo, Chenwei Wu, Zhengxu Tang, Zitao Shuai, Thao Nguyen Minh Phan, Jun-En Ding, Cong-Tinh Dao, Jack Gallifant, Robyn Gayle Dychiao, Jose Carlo Artiaga, André Hiroshi Bando, Carolina Pelegrini Barbosa Gracitelli, Vincenz Ferrer, Leo Anthony Celi, Danielle Bitterman, Michael G Morley, Luis Filipe Nakayama  

**Link**: [PDF](https://arxiv.org/pdf/2412.14304)  

**Abstract**: Current ophthalmology clinical workflows are plagued by over-referrals, long waits, and complex and heterogeneous medical records. Large language models (LLMs) present a promising solution to automate various procedures such as triaging, preliminary tests like visual acuity assessment, and report summaries. However, LLMs have demonstrated significantly varied performance across different languages in natural language question-answering tasks, potentially exacerbating healthcare disparities in Low and Middle-Income Countries (LMICs). This study introduces the first multilingual ophthalmological question-answering benchmark with manually curated questions parallel across languages, allowing for direct cross-lingual comparisons. Our evaluation of 6 popular LLMs across 7 different languages reveals substantial bias across different languages, highlighting risks for clinical deployment of LLMs in LMICs. Existing debiasing methods such as Translation Chain-of-Thought or Retrieval-augmented generation (RAG) by themselves fall short of closing this performance gap, often failing to improve performance across all languages and lacking specificity for the medical domain. To address this issue, We propose CLARA (Cross-Lingual Reflective Agentic system), a novel inference time de-biasing method leveraging retrieval augmented generation and self-verification. Our approach not only improves performance across all languages but also significantly reduces the multilingual bias gap, facilitating equitable LLM application across the globe. 

**Abstract (ZH)**: 当前的眼科临床工作流程受到过度转诊、漫长等待时间和复杂异质性医疗记录的困扰。大规模语言模型（LLMs）有望自动化各种程序，如分诊、初步测试（如视力评估）和报告总结。然而，LLMs在自然语言问答任务中的性能在不同语言之间表现出显著差异，这可能加剧低收入和中等收入国家（LMICs）的医疗健康不平等。本研究引入了首个基于人工策源的多语言眼科问答基准，允许直接跨语言比较。我们对7种不同语言下的6种流行LLMs进行了评估，发现不同语言之间存在显著偏差，突显了在LMICs中临床部署LLMs时的风险。现有去偏方法，如翻译推理链或检索增强生成（RAG），单独使用时未能弥合这一性能差距，往往无法在所有语言中提高性能，缺乏针对医学领域的适应性。为此，我们提出了一种新颖的推理时间去偏方法——CLARA（跨语言反思性代理系统），该方法结合了检索增强生成和自我验证。我们的方法不仅提高了所有语言的性能，还显著减小了多语言偏差差距，从而促进全球范围内的LLM公平应用。 

---
# Fake News Detection: Comparative Evaluation of BERT-like Models and Large Language Models with Generative AI-Annotated Data 

**Title (ZH)**: 假新闻检测：基于BERT类模型和生成AI标注数据的大规模语言模型的比较评估 

**Authors**: haina Raza, Drai Paulen-Patterson, Chen Ding  

**Link**: [PDF](https://arxiv.org/pdf/2412.14276)  

**Abstract**: Fake news poses a significant threat to public opinion and social stability in modern society. This study presents a comparative evaluation of BERT-like encoder-only models and autoregressive decoder-only large language models (LLMs) for fake news detection. We introduce a dataset of news articles labeled with GPT-4 assistance (an AI-labeling method) and verified by human experts to ensure reliability. Both BERT-like encoder-only models and LLMs were fine-tuned on this dataset. Additionally, we developed an instruction-tuned LLM approach with majority voting during inference for label generation. Our analysis reveals that BERT-like models generally outperform LLMs in classification tasks, while LLMs demonstrate superior robustness against text perturbations. Compared to weak labels (distant supervision) data, the results show that AI labels with human supervision achieve better classification results. This study highlights the effectiveness of combining AI-based annotation with human oversight and demonstrates the performance of different families of machine learning models for fake news detection 

**Abstract (ZH)**: 虚假信息对现代社会的公共意见和社会稳定构成了重大威胁。本研究比较评估了编码器唯一模型（如BERT类模型）和自回归解码器唯一大型语言模型（LLMs）在虚假信息检测中的性能。我们提供了一个由GPT-4辅助（AI标注方法）标记并由人类专家验证的数据集，以确保数据可靠性。编码器唯一模型和LLMs均在此数据集上进行了微调。此外，我们还在推断过程中开发了一种基于多数投票的指令微调LLM方法以生成标签。分析结果显示，编码器唯一模型在分类任务中总体上优于LLMs，而LLMs在文本扰动下的鲁棒性更佳。与弱标签（远程监督）数据相比，使用人类监督的AI标签在分类任务中表现更优。本研究突显了结合基于AI的注释与人类监督的有效性，并展示了不同类型机器学习模型在虚假信息检测中的性能。 

---
# Critical-Questions-of-Thought: Steering LLM reasoning with Argumentative Querying 

**Title (ZH)**: 关键问题思考：通过论辩性查询引导大规模语言模型的推理 

**Authors**: Federico Castagna, Isabel Sassoon, Simon Parsons  

**Link**: [PDF](https://arxiv.org/pdf/2412.15177)  

**Abstract**: Studies have underscored how, regardless of the recent breakthrough and swift advances in AI research, even state-of-the-art Large Language models (LLMs) continue to struggle when performing logical and mathematical reasoning. The results seem to suggest that LLMs still work as (highly advanced) data pattern identifiers, scoring poorly when attempting to generalise and solve reasoning problems the models have never previously seen or that are not close to samples presented in their training data. To address this compelling concern, this paper makes use of the notion of critical questions from the literature on argumentation theory, focusing in particular on Toulmin's model of argumentation. We show that employing these critical questions can improve the reasoning capabilities of LLMs. By probing the rationale behind the models' reasoning process, the LLM can assess whether some logical mistake is occurring and correct it before providing the final reply to the user prompt. The underlying idea is drawn from the gold standard of any valid argumentative procedure: the conclusion is valid if it is entailed by accepted premises. Or, to paraphrase such Aristotelian principle in a real-world approximation, characterised by incomplete information and presumptive logic, the conclusion is valid if not proved otherwise. This approach successfully steers the models' output through a reasoning pipeline, resulting in better performance against the baseline and its Chain-of-Thought (CoT) implementation. To this end, an extensive evaluation of the proposed approach on the MT-Bench Reasoning and Math tasks across a range of LLMs is provided. 

**Abstract (ZH)**: 研究表明，尽管最近在人工智能（AI）研究领域取得了突破性进展，最先进的大规模语言模型（LLMs）在进行逻辑和数学推理时仍然存在困难。结果显示，即使是最先进的LLMs仍主要充当（高度先进的）数据模式识别器，当尝试解决训练数据中未出现或与之相去甚远的推理问题时，其泛化能力较差。为应对这一紧迫的挑战，本文借鉴论证理论文献中的“关键问题”概念，并特别关注于托马斯·库恩（Toulmin）的论证模型。我们证明，使用这些关键问题可以提高LLMs的推理能力。通过探究模型推理过程的理由，LLMs可以评估是否有逻辑错误发生，并在向用户提供最终答复之前进行纠正。这一理念源自任何有效论证程序的黄金标准：如果结论是由公认的前提所蕴含的，那么结论就是有效的。或者，如亚里士多德原则在现实世界中的近似表述，在信息不完整且预设逻辑的情况下，如果未被反驳，则结论是有效的。这种方法成功地引导模型输出通过推理管道，使其相对于基线及其链式思维（CoT）实现表现更好。为此，我们提供了对MT-Bench推理和数学任务的广泛评估，涵盖多种不同类型的LLMs。 

---
# Prompt-A-Video: Prompt Your Video Diffusion Model via Preference-Aligned LLM 

**Title (ZH)**: 当然，以下是标题的中文翻译，符合学术规范：

Prompt-A-Video: 通过偏好对齐的大语言模型优化视频扩散模型 

**Authors**: Yatai Ji, Jiacheng Zhang, Jie Wu, Shilong Zhang, Shoufa Chen, Chongjian GE, Peize Sun, Weifeng Chen, Wenqi Shao, Xuefeng Xiao, Weilin Huang, Ping Luo  

**Link**: [PDF](https://arxiv.org/pdf/2412.15156)  

**Abstract**: Text-to-video models have made remarkable advancements through optimization on high-quality text-video pairs, where the textual prompts play a pivotal role in determining quality of output videos. However, achieving the desired output often entails multiple revisions and iterative inference to refine user-provided prompts. Current automatic methods for refining prompts encounter challenges such as Modality-Inconsistency, Cost-Discrepancy, and Model-Unaware when applied to text-to-video diffusion models. To address these problem, we introduce an LLM-based prompt adaptation framework, termed as Prompt-A-Video, which excels in crafting Video-Centric, Labor-Free and Preference-Aligned prompts tailored to specific video diffusion model. Our approach involves a meticulously crafted two-stage optimization and alignment system. Initially, we conduct a reward-guided prompt evolution pipeline to automatically create optimal prompts pool and leverage them for supervised fine-tuning (SFT) of the LLM. Then multi-dimensional rewards are employed to generate pairwise data for the SFT model, followed by the direct preference optimization (DPO) algorithm to further facilitate preference alignment. Through extensive experimentation and comparative analyses, we validate the effectiveness of Prompt-A-Video across diverse generation models, highlighting its potential to push the boundaries of video generation. 

**Abstract (ZH)**: 文本到视频模型通过优化高质量的文本-视频对取得了显著进展，其中文本提示在决定输出视频质量方面发挥着关键作用。然而，实现所需输出往往需要多次修订和迭代推理来细化用户提供的提示。当将现有的提示优化方法应用于文本到视频扩散模型时，它们遇到了模态不一致性（Modality-Inconsistency）、成本偏差（Cost-Discrepancy）和模型不感知（Model-Unaware）等问题。为了解决这些问题，我们提出了一种基于大语言模型（LLM）的提示适应框架，称为Prompt-A-Video，该框架能够生成面向视频、无需劳力且符合用户偏好的提示，适用于特定的视频扩散模型。我们的方法涉及一个精心构建的两阶段优化和对齐系统。首先，我们通过奖励引导的提示演化管道自动创建最优提示池，并将其用于对LLM进行监督微调（SFT）。然后，我们使用多维奖励生成监督微调模型的数据对，并采用直接偏好优化（DPO）算法进一步促进偏好对齐。通过广泛的实验和对比分析，我们验证了Prompt-A-Video在各种生成模型中的有效性，突显了其推动视频生成边界的可能性。 

---
# Movie2Story: A framework for understanding videos and telling stories in the form of novel text 

**Title (ZH)**: Movie2Story：一个理解视频并以新颖文本形式讲述故事的框架 

**Authors**: Kangning Li, Zheyang Jia, Anyu Ying  

**Link**: [PDF](https://arxiv.org/pdf/2412.14965)  

**Abstract**: Multimodal video-to-text models have made considerable progress, primarily in generating brief descriptions of video content. However, there is still a deficiency in generating rich long-form text descriptions that integrate both video and audio. In this paper, we introduce a framework called M2S, designed to generate novel-length text by combining audio, video, and character recognition. M2S includes modules for video long-form text description and comprehension, audio-based analysis of emotion, speech rate, and character alignment, and visual-based character recognition alignment. By integrating multimodal information using the large language model GPT4o, M2S stands out in the field of multimodal text generation. We demonstrate the effectiveness and accuracy of M2S through comparative experiments and human evaluation. Additionally, the model framework has good scalability and significant potential for future research. 

**Abstract (ZH)**: 多模态视频到文本模型在生成简短的视频内容描述方面取得了显著进展。然而，仍存在生成丰富的长篇描述性文本的不足，这些描述性文本需要结合视频和音频信息。本文介绍了一种名为M2S的框架，旨在通过结合音频、视频和字符识别来生成新的文本长度描述。M2S包括用于生成和理解视频长篇文本描述的模块、基于音频的情绪分析、语速分析和角色对齐分析，以及基于视觉的字符识别对齐。通过使用大型语言模型GPT4o整合多模态信息，M2S在多模态文本生成领域脱颖而出。我们通过对比实验和人工评估展示了M2S的有效性和准确性。此外，该模型框架具有良好的扩展性，并且具有未来研究的巨大潜力。 

---
# Answer Set Networks: Casting Answer Set Programming into Deep Learning 

**Title (ZH)**: 回答集网络：将回答集编程融入深度学习 

**Authors**: Arseny Skryagin, Daniel Ochs, Phillip Deibert, Simon Kohaut, Devendra Singh Dhami, Kristian Kersting  

**Link**: [PDF](https://arxiv.org/pdf/2412.14814)  

**Abstract**: Although Answer Set Programming (ASP) allows constraining neural-symbolic (NeSy) systems, its employment is hindered by the prohibitive costs of computing stable models and the CPU-bound nature of state-of-the-art solvers. To this end, we propose Answer Set Networks (ASN), a NeSy solver. Based on Graph Neural Networks (GNN), ASNs are a scalable approach to ASP-based Deep Probabilistic Logic Programming (DPPL). Specifically, we show how to translate ASPs into ASNs and demonstrate how ASNs can efficiently solve the encoded problem by leveraging GPU's batching and parallelization capabilities. Our experimental evaluations demonstrate that ASNs outperform state-of-the-art CPU-bound NeSy systems on multiple tasks. Simultaneously, we make the following two contributions based on the strengths of ASNs. Namely, we are the first to show the finetuning of Large Language Models (LLM) with DPPLs, employing ASNs to guide the training with logic. Further, we show the "constitutional navigation" of drones, i.e., encoding public aviation laws in an ASN for routing Unmanned Aerial Vehicles in uncertain environments. 

**Abstract (ZH)**: 尽管回答集编程（Answer Set Programming，ASP）能够约束神经符号（NeSy）系统，但计算稳定模型的成本高昂且最先进的求解器是CPU密集型的，这对ASP的运用构成了阻碍。为此，我们提出了一种名为回答集网络（Answer Set Networks，ASN）的NeSy求解器。基于图神经网络（Graph Neural Networks，GNN），ASN是一种基于ASP的深度概率逻辑编程（Deep Probabilistic Logic Programming，DPPL）的可扩展方法。具体而言，我们展示了如何将ASP转换为ASN，并通过利用GPU的批量处理和并行化能力，展示了ASN如何高效地解决编码问题。我们的实验评估表明，与最先进的CPU密集型NeSy系统相比，ASN在多个任务上表现出色。此外，我们基于ASN的强点做出以下两项贡献。首先，我们首次展示了使用DPPL微调大语言模型（Large Language Models，LLM），并利用ASN以逻辑为指导进行训练；其次，我们展示了无人机的“宪法导航”，即通过将公共航空法律编码在ASN中，实现无人驾驶航空器在不确定环境中的路径规划。 

---
# FaultExplainer: Leveraging Large Language Models for Interpretable Fault Detection and Diagnosis 

**Title (ZH)**: FaultExplainer：利用大型语言模型进行可解释的故障检测与诊断 

**Authors**: Abdullah Khan, Rahul Nahar, Hao Chen, Gonzalo E. Constante Flores, Can Li  

**Link**: [PDF](https://arxiv.org/pdf/2412.14492)  

**Abstract**: Machine learning algorithms are increasingly being applied to fault detection and diagnosis (FDD) in chemical processes. However, existing data-driven FDD platforms often lack interpretability for process operators and struggle to identify root causes of previously unseen faults. This paper presents FaultExplainer, an interactive tool designed to improve fault detection, diagnosis, and explanation in the Tennessee Eastman Process (TEP). FaultExplainer integrates real-time sensor data visualization, Principal Component Analysis (PCA)-based fault detection, and identification of top contributing variables within an interactive user interface powered by large language models (LLMs). We evaluate the LLMs' reasoning capabilities in two scenarios: one where historical root causes are provided, and one where they are not to mimic the challenge of previously unseen faults. Experimental results using GPT-4o and o1-preview models demonstrate the system's strengths in generating plausible and actionable explanations, while also highlighting its limitations, including reliance on PCA-selected features and occasional hallucinations. 

**Abstract (ZH)**: 机器学习算法在化工过程的故障检测与诊断（FDD）中得到了越来越多的应用。然而，现有的数据驱动的FDD平台往往缺乏工艺操作人员可解释性，并且难以识别未见故障的根本原因。本文提出了一种名为FaultExplainer的交互式工具，旨在改善泰勒纳曼过程（TEP）中的故障检测、诊断和解释。FaultExplainer将实时传感器数据可视化、基于主成分分析（PCA）的故障检测以及关键影响变量的识别集成到了一个由大规模语言模型（LLMs）驱动的交互用户界面中。我们通过两种场景评估了LLMs的推理能力：一种场景是提供历史根本原因，另一种场景则不提供根本原因，以模拟未见故障的挑战。使用GPT-4o和o1-preview模型的实验结果表明，该系统在生成合理且可操作的解释方面具有优势，同时也指出了其局限性，包括对PCA选择特征的依赖性和偶尔的幻觉现象。 

---
# HSEvo: Elevating Automatic Heuristic Design with Diversity-Driven Harmony Search and Genetic Algorithm Using LLMs 

**Title (ZH)**: HSEvo：通过多样性驱动的和谐搜索和遗传算法利用大规模语言模型自动启发式设计的提升 

**Authors**: Pham Vu Tuan Dat, Long Doan, Huynh Thi Thanh Binh  

**Link**: [PDF](https://arxiv.org/pdf/2412.14995)  

**Abstract**: Automatic Heuristic Design (AHD) is an active research area due to its utility in solving complex search and NP-hard combinatorial optimization problems in the real world. The recent advancements in Large Language Models (LLMs) introduce new possibilities by coupling LLMs with evolutionary computation to automatically generate heuristics, known as LLM-based Evolutionary Program Search (LLM-EPS). While previous LLM-EPS studies obtained great performance on various tasks, there is still a gap in understanding the properties of heuristic search spaces and achieving a balance between exploration and exploitation, which is a critical factor in large heuristic search spaces. In this study, we address this gap by proposing two diversity measurement metrics and perform an analysis on previous LLM-EPS approaches, including FunSearch, EoH, and ReEvo. Results on black-box AHD problems reveal that while EoH demonstrates higher diversity than FunSearch and ReEvo, its objective score is unstable. Conversely, ReEvo's reflection mechanism yields good objective scores but fails to optimize diversity effectively. With this finding in mind, we introduce HSEvo, an adaptive LLM-EPS framework that maintains a balance between diversity and convergence with a harmony search algorithm. Through experimentation, we find that HSEvo achieved high diversity indices and good objective scores while remaining cost-effective. These results underscore the importance of balancing exploration and exploitation and understanding heuristic search spaces in designing frameworks in LLM-EPS. 

**Abstract (ZH)**: 自动启发式设计（AHD）是一个活跃的研究领域，因为它在解决实际中的复杂搜索和NP难组合优化问题方面具有重要作用。最近，大型语言模型（LLMs）的发展为通过将LLMs与进化计算相结合来自动生成启发式方法提供了新的可能性，这种方法被称为基于大语言模型的进化程序搜索（LLM-EPS）。尽管先前的LLM-EPS研究在各种任务上取得了出色的性能，但在了解启发式搜索空间的特性以及在大启发式搜索空间中实现探索与利用之间的平衡方面仍存在差距，这是关键因素之一。在这项研究中，我们通过提出两种多样性的度量标准，并对先前的LLM-EPS方法进行分析，包括FunSearch、EoH和ReEvo，来解决这一差距。在黑盒AHD问题上的结果表明，尽管EoH的多样性高于FunSearch和ReEvo，但其目标评分不稳定。相反，ReEvo的反射机制获得了较好的目标评分，但在有效优化多样性方面却存在问题。基于这一发现，我们引入了一个适应性的LLM-EPS框架——HSEvo——它通过使用和谐搜索算法在多样性和收敛性之间保持平衡。通过实验，我们发现HSEvo在保持较高多样性指数和良好目标评分的同时，还具有成本效益。这些结果强调了在LLM-EPS框架设计中平衡探索与利用以及理解启发式搜索空间的重要性。 

---
# Helping LLMs Improve Code Generation Using Feedback from Testing and Static Analysis 

**Title (ZH)**: 使用测试和静态分析反馈帮助大型语言模型提升代码生成能力 

**Authors**: Greta Dolcetti, Vincenzo Arceri, Eleonora Iotti, Sergio Maffeis, Agostino Cortesi, Enea Zaffanella  

**Link**: [PDF](https://arxiv.org/pdf/2412.14841)  

**Abstract**: Large Language Models (LLMs) are one of the most promising developments in the field of artificial intelligence, and the software engineering community has readily noticed their potential role in the software development life-cycle. Developers routinely ask LLMs to generate code snippets, increasing productivity but also potentially introducing ownership, privacy, correctness, and security issues. Previous work highlighted how code generated by mainstream commercial LLMs is often not safe, containing vulnerabilities, bugs, and code smells. In this paper, we present a framework that leverages testing and static analysis to assess the quality, and guide the self-improvement, of code generated by general-purpose, open-source LLMs.
First, we ask LLMs to generate C code to solve a number of programming tasks. Then we employ ground-truth tests to assess the (in)correctness of the generated code, and a static analysis tool to detect potential safety vulnerabilities. Next, we assess the models ability to evaluate the generated code, by asking them to detect errors and vulnerabilities. Finally, we test the models ability to fix the generated code, providing the reports produced during the static analysis and incorrectness evaluation phases as feedback.
Our results show that models often produce incorrect code, and that the generated code can include safety issues. Moreover, they perform very poorly at detecting either issue. On the positive side, we observe a substantial ability to fix flawed code when provided with information about failed tests or potential vulnerabilities, indicating a promising avenue for improving the safety of LLM-based code generation tools. 

**Abstract (ZH)**: 大型语言模型（LLMs）是人工智能领域最具前景的发展之一，软件工程社区也已经注意到它们在软件开发生命周期中的潜在作用。开发者经常要求LLMs生成代码片段，从而提高生产效率，但也可能引入所有权、隐私、正确性及安全性方面的问题。前期研究指出，主流商业LLMs生成的代码往往不够安全，包含漏洞、错误和代码异味。在本文中，我们提出了一种框架，通过测试和静态分析来评估由通用开源LLMs生成的代码的质量，并引导这些模型进行自我优化。

首先，我们要求LLMs生成C代码以解决一系列编程任务。然后，我们使用真实的测试来评估生成代码的（不）正确性，并使用静态分析工具检测潜在的安全漏洞。接下来，我们评估模型评估生成代码的能力，通过要求模型检测错误和漏洞。最后，我们测试模型修复生成代码的能力，提供在静态分析和不正确性评估阶段产生的报告作为反馈。

我们的研究表明，模型经常生成错误的代码，生成的代码中可能包含安全问题。此外，它们在检测这些错误和问题方面表现非常糟糕。不过，当我们提供关于失败测试或潜在漏洞的信息时，我们观察到模型在修复存在问题的代码方面表现出明显的潜力，这为进一步改进基于LLM的代码生成工具的安全性提供了有前途的途径。 

---
# Generative AI Toolkit -- a framework for increasing the quality of LLM-based applications over their whole life cycle 

**Title (ZH)**: 生成型AI工具包——一种在整个生命周期中提高基于LLM的应用质量的框架 

**Authors**: Jens Kohl, Luisa Gloger, Rui Costa, Otto Kruse, Manuel P. Luitz, David Katz, Gonzalo Barbeito, Markus Schweier, Ryan French, Jonas Schroeder, Thomas Riedl, Raphael Perri, Youssef Mostafa  

**Link**: [PDF](https://arxiv.org/pdf/2412.14215)  

**Abstract**: As LLM-based applications reach millions of customers, ensuring their scalability and continuous quality improvement is critical for success. However, the current workflows for developing, maintaining, and operating (DevOps) these applications are predominantly manual, slow, and based on trial-and-error. With this paper we introduce the Generative AI Toolkit, which automates essential workflows over the whole life cycle of LLM-based applications. The toolkit helps to configure, test, continuously monitor and optimize Generative AI applications such as agents, thus significantly improving quality while shortening release cycles. We showcase the effectiveness of our toolkit on representative use cases, share best practices, and outline future enhancements. Since we are convinced that our Generative AI Toolkit is helpful for other teams, we are open sourcing it on and hope that others will use, forward, adapt and improve 

**Abstract (ZH)**: 随着基于大型语言模型（LLM）的应用程序达到数百万客户，确保其可扩展性和持续的质量改进对于其成功至关重要。然而，当前开发、维护和运行（DevOps）这些应用的工作流程主要依赖手工操作，速度缓慢，并且基于试错法。在本文中，我们介绍了生成式AI工具包，该工具包在整个基于LLM的应用程序生命周期中自动化了关键工作流程。此工具包有助于配置、测试、持续监控和优化生成式AI应用，如代理，从而显著提高质量并缩短发布周期。我们通过代表性的用例展示了我们工具包的有效性，分享了最佳实践，并概述了未来增强计划。由于我们相信我们的生成式AI工具包对其他团队也有帮助，我们决定将其开源，并希望其他人能够使用、分享、适应并改进它。 

---
# BlenderLLM: Training Large Language Models for Computer-Aided Design with Self-improvement 

**Title (ZH)**: BlenderLLM：通过自我提升训练计算机辅助设计中的大型语言模型 

**Authors**: Yuhao Du, Shunian Chen, Wenbo Zan, Peizhao Li, Mingxuan Wang, Dingjie Song, Bo Li, Yan Hu, Benyou Wang  

**Link**: [PDF](https://arxiv.org/pdf/2412.14203)  

**Abstract**: The application of Large Language Models (LLMs) in Computer-Aided Design (CAD) remains an underexplored area, despite their remarkable advancements in other domains. In this paper, we present BlenderLLM, a novel framework for training LLMs specifically for CAD tasks leveraging a self-improvement methodology. To support this, we developed a bespoke training dataset, BlendNet, and introduced a comprehensive evaluation suite, CADBench. Our results reveal that existing models demonstrate significant limitations in generating accurate CAD scripts. However, through minimal instruction-based fine-tuning and iterative self-improvement, BlenderLLM significantly surpasses these models in both functionality and accuracy of CAD script generation. This research establishes a strong foundation for the application of LLMs in CAD while demonstrating the transformative potential of self-improving models in advancing CAD automation. We encourage further exploration and adoption of these methodologies to drive innovation in the field. The dataset, model, benchmark, and source code are publicly available at this https URL 

**Abstract (ZH)**: 在计算机辅助设计（CAD）领域，大型语言模型（LLMs）的应用仍是一个未被充分探索的领域，尽管它们在其他领域取得了显著的进步。本文介绍了BlenderLLM，这是一种利用自我改进方法专门针对CAD任务训练LLMs的新框架。为支持这一框架，我们开发了一个定制化的训练数据集BlendNet，并引入了一个全面的评估套件CADBench。我们的结果显示，现有的模型在生成准确的CAD脚本方面显示出显著的局限性。然而，通过最少的指令微调和迭代自我改进，BlenderLLM在CAD脚本生成的功能性和准确性上远远超过了这些模型。这项研究为LLMs在CAD中的应用奠定了坚实的基础，同时展示了自改进模型在推动CAD自动化方面具有变革性的潜力。我们鼓励进一步探索和采用这些方法，以推动该领域的创新。数据集、模型、基准和源代码已在以下网址公开：[此处填写网址] 

---
