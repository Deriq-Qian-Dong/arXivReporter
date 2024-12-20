# VISA: Retrieval Augmented Generation with Visual Source Attribution 

**Title (ZH)**: VISA：带有视觉来源归因的检索增强生成 

**Authors**: Xueguang Ma, Shengyao Zhuang, Bevan Koopman, Guido Zuccon, Wenhu Chen, Jimmy Lin  

**Link**: [PDF](https://arxiv.org/pdf/2412.14457)  

**Abstract**: Generation with source attribution is important for enhancing the verifiability of retrieval-augmented generation (RAG) systems. However, existing approaches in RAG primarily link generated content to document-level references, making it challenging for users to locate evidence among multiple content-rich retrieved documents. To address this challenge, we propose Retrieval-Augmented Generation with Visual Source Attribution (VISA), a novel approach that combines answer generation with visual source attribution. Leveraging large vision-language models (VLMs), VISA identifies the evidence and highlights the exact regions that support the generated answers with bounding boxes in the retrieved document screenshots. To evaluate its effectiveness, we curated two datasets: Wiki-VISA, based on crawled Wikipedia webpage screenshots, and Paper-VISA, derived from PubLayNet and tailored to the medical domain. Experimental results demonstrate the effectiveness of VISA for visual source attribution on documents' original look, as well as highlighting the challenges for improvement. Code, data, and model checkpoints will be released. 

**Abstract (ZH)**: 生成并配以来源归属性的方法对于增强检索增强生成（RAG）系统的可验证性至关重要。然而，现有的RAG方法主要将生成的内容与文档级别的引用关联起来，使得用户在多个内容丰富的检索文档中难以定位证据。为了解决这一挑战，我们提出了结合回答生成与视觉来源归属性的检索增强生成方法（Retrieval-Augmented Generation with Visual Source Attribution, VISA）。VISA 利用大规模的视觉语言模型（VLMs），通过在检索文档的屏幕截图中使用边界框突出显示支持生成答案的具体证据和区域，实现了视觉来源归属性。为了评估其有效性，我们精心制作了两个数据集：基于爬取的Wikipedia网页屏幕截图构建的Wiki-VISA，以及基于PubLayNet并针对医学领域定制的Paper-VISA。实验结果表明，VISA 在保留文档原始外观的同时，能够有效地进行视觉来源归属性，同时也指出了改进的挑战。我们将发布代码、数据和模型检查点。 

---
# Face the Facts! Evaluating RAG-based Fact-checking Pipelines in Realistic Settings 

**Title (ZH)**: 正视现实！在实际场景中评估基于RAG的事实核查管道 

**Authors**: Daniel Russo, Stefano Menini, Jacopo Staiano, Marco Guerini  

**Link**: [PDF](https://arxiv.org/pdf/2412.15189)  

**Abstract**: Natural Language Processing and Generation systems have recently shown the potential to complement and streamline the costly and time-consuming job of professional fact-checkers. In this work, we lift several constraints of current state-of-the-art pipelines for automated fact-checking based on the Retrieval-Augmented Generation (RAG) paradigm. Our goal is to benchmark, under more realistic scenarios, RAG-based methods for the generation of verdicts - i.e., short texts discussing the veracity of a claim - evaluating them on stylistically complex claims and heterogeneous, yet reliable, knowledge bases. Our findings show a complex landscape, where, for example, LLM-based retrievers outperform other retrieval techniques, though they still struggle with heterogeneous knowledge bases; larger models excel in verdict faithfulness, while smaller models provide better context adherence, with human evaluations favouring zero-shot and one-shot approaches for informativeness, and fine-tuned models for emotional alignment. 

**Abstract (ZH)**: 自然语言处理（NLP）和生成系统在最近显示出有望补充和简化专业事实核查人员繁重且耗时的工作。在本文中，我们基于检索增强生成（RAG）范式，改进了现有最先进的自动事实核查流程中的多项约束。我们的目标是在更现实的情景下对基于RAG的方法进行基准测试，这些方法用于生成裁定——即讨论声明真伪的简短文本——并通过风格复杂且多样的知识库对其进行评估。我们的研究发现了一个复杂的情景，例如，基于大型语言模型（LLM）的检索器在检索性能上优于其他检索技术，尽管它们仍然难以处理异质性知识库；较大的模型在裁定的可信度方面表现出色，而较小的模型在保持上下文一致性方面表现更好。从人类评价来看，零样本和单样本方法在信息丰富性方面受到青睐，而微调模型在情感一致性方面表现更好。 

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
# Query pipeline optimization for cancer patient question answering systems 

**Title (ZH)**: 癌症患者问答系统中查询管道的优化方法 

**Authors**: Maolin He, Rena Gao, Mike Conway, Brian E. Chapman  

**Link**: [PDF](https://arxiv.org/pdf/2412.14751)  

**Abstract**: Retrieval-augmented generation (RAG) mitigates hallucination in Large Language Models (LLMs) by using query pipelines to retrieve relevant external information and grounding responses in retrieved knowledge. However, query pipeline optimization for cancer patient question-answering (CPQA) systems requires separately optimizing multiple components with domain-specific considerations. We propose a novel three-aspect optimization approach for the RAG query pipeline in CPQA systems, utilizing public biomedical databases like PubMed and PubMed Central. Our optimization includes: (1) document retrieval, utilizing a comparative analysis of NCBI resources and introducing Hybrid Semantic Real-time Document Retrieval (HSRDR); (2) passage retrieval, identifying optimal pairings of dense retrievers and rerankers; and (3) semantic representation, introducing Semantic Enhanced Overlap Segmentation (SEOS) for improved contextual understanding. On a custom-developed dataset tailored for cancer-related inquiries, our optimized RAG approach improved the answer accuracy of Claude-3-haiku by 5.24% over chain-of-thought prompting and about 3% over a naive RAG setup. This study highlights the importance of domain-specific query optimization in realizing the full potential of RAG and provides a robust framework for building more accurate and reliable CPQA systems, advancing the development of RAG-based biomedical systems. 

**Abstract (ZH)**: 检索增强生成（RAG）通过使用查询管道检索相关外部信息并在检索到的知识基础上确立响应，从而缓解了大型语言模型（LLMs）中的幻觉现象。然而，针对癌症患者问答（CPQA）系统的查询管道优化需要分别优化多个具有领域特定考虑的组件。我们提出了一种针对CPQA系统中RAG查询管道的新型三方面优化方法，利用PubMed和PubMed Central等公共生物医学数据库。我们的优化包括：（1）文档检索，采用NCBI资源的比较分析，并引入了混合语义实时文档检索（HSRDR）；（2）段落检索，确定密集检索器和排序器的最佳配对；（3）语义表示，引入语义增强重叠分割（SEOS），以提高上下文理解能力。在针对癌症相关查询定制开发的数据集上，我们优化的RAG方法在回答精度方面提高了Claude-3-haiku约5.24%，并且相对于链式思考提示（chain-of-thought prompting）高约3%，相对于原始的RAG设置高约3%。本研究强调了在实现RAG潜力方面领域特定查询优化的重要性，并提供了一个强大的框架，用于构建更准确可靠的CPQA系统，推动基于RAG的生物医学系统的发展。 

---
# CORD: Balancing COnsistency and Rank Distillation for Robust Retrieval-Augmented Generation 

**Title (ZH)**: CORD: 平衡一致性与排名蒸馏以实现稳健的检索增强生成 

**Authors**: Youngwon Lee, Seung-won Hwang, Daniel Campos, Filip Graliński, Zhewei Yao, Yuxiong He  

**Link**: [PDF](https://arxiv.org/pdf/2412.14581)  

**Abstract**: With the adoption of retrieval-augmented generation (RAG), large language models (LLMs) are expected to ground their generation to the retrieved contexts. Yet, this is hindered by position bias of LLMs, failing to evenly attend to all contexts. Previous work has addressed this by synthesizing contexts with perturbed positions of gold segment, creating a position-diversified train set. We extend this intuition to propose consistency regularization with augmentation and distillation. First, we augment each training instance with its position perturbation to encourage consistent predictions, regardless of ordering. We also distill behaviors of this pair, although it can be counterproductive in certain RAG scenarios where the given order from the retriever is crucial for generation quality. We thus propose CORD, balancing COnsistency and Rank Distillation. CORD adaptively samples noise-controlled perturbations from an interpolation space, ensuring both consistency and respect for the rank prior. Empirical results show this balance enables CORD to outperform consistently in diverse RAG benchmarks. 

**Abstract (ZH)**: 随着检索增强生成（RAG）技术的应用，大规模语言模型（LLMs）被期望将其生成内容与检索到的上下文联系起来。然而，这一目标受到LLMs位置偏见的阻碍，使其难以平等地关注所有上下文。此前的研究通过合成具有扰动位置的黄金片段，创建一个位置多样化的数据集，来解决这一问题。我们借鉴这一思路，提出了包含增强和蒸馏的一致性正则化方法。首先是增强每个训练实例的每种位置扰动，以促进一致预测，而不考虑顺序问题。同时，我们对这一对的行为进行蒸馏，尽管在某些RAG场景中，检索器给出的顺序对于生成质量至关重要，这可能会适得其反。因此，我们提出了CORD（Consistency and Rank Distillation），该方法在保持一致性和尊重排名先验的同时，实现了二者的平衡。实验证明，这种平衡使CORD在各种RAG基准测试中表现出色。 

---
# PA-RAG: RAG Alignment via Multi-Perspective Preference Optimization 

**Title (ZH)**: PA-RAG：基于多视角偏好优化的RAG对齐 

**Authors**: Jiayi Wu, Hengyi Cai, Lingyong Yan, Hao Sun, Xiang Li, Shuaiqiang Wang, Dawei Yin, Ming Gao  

**Link**: [PDF](https://arxiv.org/pdf/2412.14510)  

**Abstract**: The emergence of Retrieval-augmented generation (RAG) has alleviated the issues of outdated and hallucinatory content in the generation of large language models (LLMs), yet it still reveals numerous limitations. When a general-purpose LLM serves as the RAG generator, it often suffers from inadequate response informativeness, response robustness, and citation quality. Past approaches to tackle these limitations, either by incorporating additional steps beyond generating responses or optimizing the generator through supervised fine-tuning (SFT), still failed to align with the RAG requirement thoroughly. Consequently, optimizing the RAG generator from multiple preference perspectives while maintaining its end-to-end LLM form remains a challenge. To bridge this gap, we propose Multiple Perspective Preference Alignment for Retrieval-Augmented Generation (PA-RAG), a method for optimizing the generator of RAG systems to align with RAG requirements comprehensively. Specifically, we construct high-quality instruction fine-tuning data and multi-perspective preference data by sampling varied quality responses from the generator across different prompt documents quality scenarios. Subsequently, we optimize the generator using SFT and Direct Preference Optimization (DPO). Extensive experiments conducted on four question-answer datasets across three LLMs demonstrate that PA-RAG can significantly enhance the performance of RAG generators. Our code and datasets are available at this https URL. 

**Abstract (ZH)**: 检索增强生成（RAG）的出现缓解了大型语言模型（LLMs）生成过程中内容过时和幻觉的问题，但仍揭示出许多局限性。当通用型LLM作为RAG生成器时，它往往在响应信息丰富性、响应稳健性和引证质量方面存在不足。过去解决这些问题的方法要么通过生成响应之外的额外步骤，要么通过监督微调（SFT）优化生成器，这些方法仍未充分满足RAG的要求。因此，如何从多个偏好角度优化RAG生成器并保持其端到端的LLM形式仍是一个挑战。为解决这一问题，我们提出了一种综合性优化方法——多角度偏好对齐的检索增强生成（PA-RAG），用于全面优化RAG系统中的生成器。具体而言，我们通过在不同提示文档质量场景中采样多质量级别的响应来构建高质量的指令微调数据和多角度偏好数据。随后，我们使用监督微调（SFT）和直接偏好优化（DPO）对生成器进行优化。我们在三个LLM的四个问答数据集上进行了广泛的实验，结果表明PA-RAG可以显著提升RAG生成器的性能。我们的代码和数据集可在以下链接获得：[此 https URL]。 

---
# Multi-OphthaLingua: A Multilingual Benchmark for Assessing and Debiasing LLM Ophthalmological QA in LMICs 

**Title (ZH)**: Multilingual OphthaLingua：评估和去偏见LM在LMICs中眼科QA的多语言基准荏 

**Authors**: David Restrepo, Chenwei Wu, Zhengxu Tang, Zitao Shuai, Thao Nguyen Minh Phan, Jun-En Ding, Cong-Tinh Dao, Jack Gallifant, Robyn Gayle Dychiao, Jose Carlo Artiaga, André Hiroshi Bando, Carolina Pelegrini Barbosa Gracitelli, Vincenz Ferrer, Leo Anthony Celi, Danielle Bitterman, Michael G Morley, Luis Filipe Nakayama  

**Link**: [PDF](https://arxiv.org/pdf/2412.14304)  

**Abstract**: Current ophthalmology clinical workflows are plagued by over-referrals, long waits, and complex and heterogeneous medical records. Large language models (LLMs) present a promising solution to automate various procedures such as triaging, preliminary tests like visual acuity assessment, and report summaries. However, LLMs have demonstrated significantly varied performance across different languages in natural language question-answering tasks, potentially exacerbating healthcare disparities in Low and Middle-Income Countries (LMICs). This study introduces the first multilingual ophthalmological question-answering benchmark with manually curated questions parallel across languages, allowing for direct cross-lingual comparisons. Our evaluation of 6 popular LLMs across 7 different languages reveals substantial bias across different languages, highlighting risks for clinical deployment of LLMs in LMICs. Existing debiasing methods such as Translation Chain-of-Thought or Retrieval-augmented generation (RAG) by themselves fall short of closing this performance gap, often failing to improve performance across all languages and lacking specificity for the medical domain. To address this issue, We propose CLARA (Cross-Lingual Reflective Agentic system), a novel inference time de-biasing method leveraging retrieval augmented generation and self-verification. Our approach not only improves performance across all languages but also significantly reduces the multilingual bias gap, facilitating equitable LLM application across the globe. 

**Abstract (ZH)**: 当前的眼科临床工作流程受到过度转诊、漫长等待时间和复杂异质性医疗记录的困扰。大规模语言模型（LLMs）有望自动化各种程序，如分诊、初步测试（如视力评估）和报告总结。然而，LLMs在自然语言问答任务中的性能在不同语言之间表现出显著差异，这可能加剧低收入和中等收入国家（LMICs）的医疗健康不平等。本研究引入了首个基于人工策源的多语言眼科问答基准，允许直接跨语言比较。我们对7种不同语言下的6种流行LLMs进行了评估，发现不同语言之间存在显著偏差，突显了在LMICs中临床部署LLMs时的风险。现有去偏方法，如翻译推理链或检索增强生成（RAG），单独使用时未能弥合这一性能差距，往往无法在所有语言中提高性能，缺乏针对医学领域的适应性。为此，我们提出了一种新颖的推理时间去偏方法——CLARA（跨语言反思性代理系统），该方法结合了检索增强生成和自我验证。我们的方法不仅提高了所有语言的性能，还显著减小了多语言偏差差距，从而促进全球范围内的LLM公平应用。 

---
# Ontology-Aware RAG for Improved Question-Answering in Cybersecurity Education 

**Title (ZH)**: 面向本体的知识增强检索生成（RAG）方法以改进网络安全教育中的问答交互 

**Authors**: Chengshuai Zhao, Garima Agrawal, Tharindu Kumarage, Zhen Tan, Yuli Deng, Ying-Chih Chen, Huan Liu  

**Link**: [PDF](https://arxiv.org/pdf/2412.14191)  

**Abstract**: Integrating AI into education has the potential to transform the teaching of science and technology courses, particularly in the field of cybersecurity. AI-driven question-answering (QA) systems can actively manage uncertainty in cybersecurity problem-solving, offering interactive, inquiry-based learning experiences. Large language models (LLMs) have gained prominence in AI-driven QA systems, offering advanced language understanding and user engagement. However, they face challenges like hallucinations and limited domain-specific knowledge, which reduce their reliability in educational settings. To address these challenges, we propose CyberRAG, an ontology-aware retrieval-augmented generation (RAG) approach for developing a reliable and safe QA system in cybersecurity education. CyberRAG employs a two-step approach: first, it augments the domain-specific knowledge by retrieving validated cybersecurity documents from a knowledge base to enhance the relevance and accuracy of the response. Second, it mitigates hallucinations and misuse by integrating a knowledge graph ontology to validate the final answer. Experiments on publicly available cybersecurity datasets show that CyberRAG delivers accurate, reliable responses aligned with domain knowledge, demonstrating the potential of AI tools to enhance education. 

**Abstract (ZH)**: 将人工智能集成到教育中，有可能重塑科学和技术课程的教学，尤其是在网络安全领域。基于人工智能的问答（QA）系统可以通过主动管理网络安全问题解决中的不确定性，提供互动式的研究性学习体验。大型语言模型（LLMs）在基于人工智能的QA系统中受到重视，提供先进的语言理解和用户交互能力。然而，它们面临幻觉和限定制领域知识等挑战，这在教育环境中降低了其可靠性。为了解决这些挑战，我们提出了一种名为CyberRAG的方法，这是一种基于本体的检索增强生成（RAG）方法，旨在开发网络安全教育中可靠且安全的QA系统。CyberRAG采用两步方法：首先，通过从知识库中检索验证过的网络安全文档来增强领域的专业性，从而提高回复的相关性和准确性；其次，通过整合知识图谱本体来验证最终答案，以减少幻觉和滥用的风险。公开可用的网络安全数据集上的实验显示，CyberRAG能够提供与专业知识相一致的准确且可靠的回答，展示了人工智能工具在教育中的潜在价值。 

---
