# RAG-Star: Enhancing Deliberative Reasoning with Retrieval Augmented Verification and Refinement 

**Title (ZH)**: RAG-Star: 基于检索增强验证与精炼的 deliberative reasoning 提升方法 

**Authors**: Jinhao Jiang, Jiayi Chen, Junyi Li, Ruiyang Ren, Shijie Wang, Wayne Xin Zhao, Yang Song, Tao Zhang  

**Link**: [PDF](https://arxiv.org/pdf/2412.12881)  

**Abstract**: Existing large language models (LLMs) show exceptional problem-solving capabilities but might struggle with complex reasoning tasks. Despite the successes of chain-of-thought and tree-based search methods, they mainly depend on the internal knowledge of LLMs to search over intermediate reasoning steps, limited to dealing with simple tasks involving fewer reasoning steps. In this paper, we propose \textbf{RAG-Star}, a novel RAG approach that integrates the retrieved information to guide the tree-based deliberative reasoning process that relies on the inherent knowledge of LLMs. By leveraging Monte Carlo Tree Search, RAG-Star iteratively plans intermediate sub-queries and answers for reasoning based on the LLM itself. To consolidate internal and external knowledge, we propose an retrieval-augmented verification that utilizes query- and answer-aware reward modeling to provide feedback for the inherent reasoning of LLMs. Our experiments involving Llama-3.1-8B-Instruct and GPT-4o demonstrate that RAG-Star significantly outperforms previous RAG and reasoning methods. 

**Abstract (ZH)**: 现有的大型语言模型（LLMs）显示出卓越的问题解决能力，但在处理复杂的推理任务时可能会遇到困难。尽管链式思考和树状搜索方法取得了成功，但它们主要依赖于LLMs的内部知识来进行中间推理步骤的搜索，局限在处理涉及较少推理步骤的简单任务上。在本文中，我们提出了一种新的RAG方法——\textbf{RAG-Star}，该方法将检索到的信息用于指导依赖于LLMs内部知识的树状讨论性推理过程。通过利用蒙特卡洛树搜索（MCTS），RAG-Star迭代地规划基于LLMs本身的中间子查询和答案来进行推理。为了整合内部和外部知识，我们提出了一种检索增强验证方法，利用查询和答案感知的奖励建模为LLMs的内在推理提供反馈。我们的实验涉及Llama-3.1-8B-Instruct和GPT-4o表明，RAG-Star在之前的RAG和推理方法上表现出显著的优越性。 

---
# PERC: Plan-As-Query Example Retrieval for Underrepresented Code Generation 

**Title (ZH)**: PERC：计划作为查询的稀有代码生成示例检索 

**Authors**: Jaeseok Yoo, Hojae Han, Youngwon Lee, Jaejin Kim, Seung-won Hwang  

**Link**: [PDF](https://arxiv.org/pdf/2412.12447)  

**Abstract**: Code generation with large language models has shown significant promise, especially when employing retrieval-augmented generation (RAG) with few-shot examples. However, selecting effective examples that enhance generation quality remains a challenging task, particularly when the target programming language (PL) is underrepresented. In this study, we present two key findings: (1) retrieving examples whose presented algorithmic plans can be referenced for generating the desired behavior significantly improves generation accuracy, and (2) converting code into pseudocode effectively captures such algorithmic plans, enhancing retrieval quality even when the source and the target PLs are different. Based on these findings, we propose Plan-as-query Example Retrieval for few-shot prompting in Code generation (PERC), a novel framework that utilizes algorithmic plans to identify and retrieve effective examples. We validate the effectiveness of PERC through extensive experiments on the CodeContests, HumanEval and MultiPL-E benchmarks: PERC consistently outperforms the state-of-the-art RAG methods in code generation, both when the source and target programming languages match or differ, highlighting its adaptability and robustness in diverse coding environments. 

**Abstract (ZH)**: 大规模语言模型在代码生成方面展现了显著的潜力，尤其是在结合检索增强生成（RAG）和少量示例的情况下。然而，选择能够提升生成质量的有效示例仍是一项具有挑战性的任务，特别是在目标编程语言（PL）不占优势的情况下。在本研究中，我们提出两项关键发现：(1) 获取可以参考以生成所需行为的算法计划的示例，显著提高了生成准确性；(2) 将代码转换为伪代码能够有效捕捉这些算法计划，即使源编程语言与目标编程语言不同，也能提升检索质量。基于以上发现，我们提出了一种新的框架——代码生成中的少量示例提示计划查询示例检索（PERC），该框架利用算法计划来识别和检索有效示例。我们通过在CodeContests、HumanEval和MultiPL-E基准上的广泛实验验证了PERC的有效性：无论源编程语言与目标编程语言是否匹配，PERC始终优于现有的RAG方法，在多种编程环境中都展示了其适应性和鲁棒性。 

---
# BioRAGent: A Retrieval-Augmented Generation System for Showcasing Generative Query Expansion and Domain-Specific Search for Scientific Q&A 

**Title (ZH)**: BioRAGent：一种用于展示生成型查询扩展和领域特定搜索的检索增强生成系统 

**Authors**: Samy Ateia, Udo Kruschwitz  

**Link**: [PDF](https://arxiv.org/pdf/2412.12358)  

**Abstract**: We present BioRAGent, an interactive web-based retrieval-augmented generation (RAG) system for biomedical question answering. The system uses large language models (LLMs) for query expansion, snippet extraction, and answer generation while maintaining transparency through citation links to the source documents and displaying generated queries for further editing. Building on our successful participation in the BioASQ 2024 challenge, we demonstrate how few-shot learning with LLMs can be effectively applied for a professional search setting. The system supports both direct short paragraph style responses and responses with inline citations. Our demo is available online, and the source code is publicly accessible through GitHub. 

**Abstract (ZH)**: 我们介绍了BioRAGent，这是一个基于网页的交互式检索增强生成（RAG）系统，用于生物医学问题解答。该系统使用大型语言模型（LLMs）进行查询扩展、片段提取和答案生成，同时通过引用链接展示源文档，并显示生成的查询以供进一步编辑，从而保持透明性。在我们成功参与BioASQ 2024 挑战的基础上，我们展示了在专业搜索环境中如何有效应用少样本学习。该系统支持直接简短段落式的回答和带有 inline 引用的参考文献回答。我们的演示版本已在线提供，源代码也通过 GitHub 公开 accessible。 

---
# RAG Playground: A Framework for Systematic Evaluation of Retrieval Strategies and Prompt Engineering in RAG Systems 

**Title (ZH)**: RAG游乐场：一种评估RAG系统中检索策略和提示工程系统的框架 

**Authors**: Ioannis Papadimitriou, Ilias Gialampoukidis, Stefanos Vrochidis, Ioannis, Kompatsiaris  

**Link**: [PDF](https://arxiv.org/pdf/2412.12322)  

**Abstract**: We present RAG Playground, an open-source framework for systematic evaluation of Retrieval-Augmented Generation (RAG) systems. The framework implements and compares three retrieval approaches: naive vector search, reranking, and hybrid vector-keyword search, combined with ReAct agents using different prompting strategies. We introduce a comprehensive evaluation framework with novel metrics and provide empirical results comparing different language models (Llama 3.1 and Qwen 2.5) across various retrieval configurations. Our experiments demonstrate significant performance improvements through hybrid search methods and structured self-evaluation prompting, achieving up to 72.7% pass rate on our multi-metric evaluation framework. The results also highlight the importance of prompt engineering in RAG systems, with our custom-prompted agents showing consistent improvements in retrieval accuracy and response quality. 

**Abstract (ZH)**: 我们介绍了一种开源框架RAG Playground，用于系统评估检索增强生成（RAG）系统。该框架实现了并对比了三种检索方法：朴素向量搜索、再排序和混合向量-关键词搜索，并结合使用了不同的ReAct代理和提示策略。我们引入了一个全面的评估框架，并提供了新的评估指标，比较了不同语言模型（Llama 3.1和Qwen 2.5）在各种检索配置下的性能。实验结果表明，通过混合检索方法和结构化自我评估提示，能够取得显著的性能提升，在我们的多指标评估框架中，混合搜索方法的通过率达到了72.7%。结果还强调了在RAG系统中提示工程的重要性，我们自定义提示的代理在检索准确性和响应质量方面表现出持续的改进。 

---
# OmniEval: An Omnidirectional and Automatic RAG Evaluation Benchmark in Financial Domain 

**Title (ZH)**: OmniEval：金融领域全方位自动RAG评估基准 

**Authors**: Shuting Wang, Jiejun Tan, Zhicheng Dou, Ji-Rong Wen  

**Link**: [PDF](https://arxiv.org/pdf/2412.13018)  

**Abstract**: As a typical and practical application of Large Language Models (LLMs), Retrieval-Augmented Generation (RAG) techniques have gained extensive attention, particularly in vertical domains where LLMs may lack domain-specific knowledge. In this paper, we introduce an omnidirectional and automatic RAG benchmark, OmniEval, in the financial domain. Our benchmark is characterized by its multi-dimensional evaluation framework, including (1) a matrix-based RAG scenario evaluation system that categorizes queries into five task classes and 16 financial topics, leading to a structured assessment of diverse query scenarios; (2) a multi-dimensional evaluation data generation approach, which combines GPT-4-based automatic generation and human annotation, achieving an 87.47\% acceptance ratio in human evaluations on generated instances; (3) a multi-stage evaluation system that evaluates both retrieval and generation performance, result in a comprehensive evaluation on the RAG pipeline; and (4) robust evaluation metrics derived from rule-based and LLM-based ones, enhancing the reliability of assessments through manual annotations and supervised fine-tuning of an LLM evaluator. Our experiments demonstrate the comprehensiveness of OmniEval, which includes extensive test datasets and highlights the performance variations of RAG systems across diverse topics and tasks, revealing significant opportunities for RAG models to improve their capabilities in vertical domains. We open source the code of our benchmark in \href{this https URL}{this https URL}. 

**Abstract (ZH)**: 作为大型语言模型（LLMs）的一种典型且实用的应用，检索增强生成（RAG）技术引起了广泛关注，特别是在LLMs可能缺乏领域特定知识的垂直领域。本文介绍了一个应用于金融领域的全方位自动RAG基准——OmniEval。我们的基准具有多维度的评估框架，包括以下几点：

1. **矩阵式的RAG场景评估系统**：该系统将查询分为五大任务类别和16个金融主题，从而对各种查询场景进行结构化的评估；
2. **多维度的评估数据生成方法**：该方法结合基于GPT-4的自动生成和人工注释，生成的样本在人类评估中获得了87.47%的接受率；
3. **多阶段评估系统**：该系统评估检索和生成性能，从而对RAG管道进行全面评估；
4. **稳健的评估指标**：这些指标来源于基于规则的和基于LLM的指标，通过人工注释和监督微调LLM评估器，增强了评估的可靠性。

我们的实验表明，OmniEval的全面性体现在其丰富的测试数据集上，突显了RAG系统在不同主题和任务上的性能差异，揭示了RAG模型在垂直领域提高其能力的巨大潜力。我们已在 \href{this https URL}{这个链接} 开放了该基准代码。 

---
# SynthCypher: A Fully Synthetic Data Generation Framework for Text-to-Cypher Querying in Knowledge Graphs 

**Title (ZH)**: SynthCypher：一种用于知识图中文本到密文查询的完全合成数据生成框架 

**Authors**: Aman Tiwari, Shiva Krishna Reddy Malay, Vikas Yadav, Masoud Hashemi, Sathwik Tejaswi Madhusudhan  

**Link**: [PDF](https://arxiv.org/pdf/2412.12612)  

**Abstract**: Cypher, the query language for Neo4j graph databases, plays a critical role in enabling graph-based analytics and data exploration. While substantial research has been dedicated to natural language to SQL query generation (Text2SQL), the analogous problem for graph databases referred to as Text2Cypher remains underexplored. In this work, we introduce SynthCypher, a fully synthetic and automated data generation pipeline designed to address this gap. SynthCypher employs a novel LLMSupervised Generation-Verification framework, ensuring syntactically and semantically correct Cypher queries across diverse domains and query complexities. Using this pipeline, we create SynthCypher Dataset, a large-scale benchmark containing 29.8k Text2Cypher instances. Fine-tuning open-source large language models (LLMs), including LLaMa-3.1- 8B, Mistral-7B, and QWEN-7B, on SynthCypher yields significant performance improvements of up to 40% on the Text2Cypher test set and 30% on the SPIDER benchmark adapted for graph databases. This work demonstrates that high-quality synthetic data can effectively advance the state-of-the-art in Text2Cypher tasks. 

**Abstract (ZH)**: Cypher 是 Neo4j 图数据库的查询语言，在基于图的分析和数据探索中起着关键作用。虽然大量研究致力于自然语言到 SQL 查询生成（Text2SQL）的问题，但针对图数据库的相应问题，即 Text2Cypher，仍然缺乏相关研究。在本文中，我们介绍了一种新的全合成和自动化的数据生成管道——SynthCypher，旨在解决这一问题。SynthCypher 使用了一种新颖的LLM 监督生成-验证框架，确保在不同领域和查询复杂度下生成语法和语义正确的 Cypher 查询。使用该管道，我们创建了包含 29,800 个 Text2Cypher 实例的 SynthCypher 数据集，这是一个大规模基准。通过对 SynthCypher 进行微调的开源大型语言模型（LLM），包括 LLaMa-3.1-8B、Mistral-7B 和 QWEN-7B，在 Text2Cypher 测试集上取得了高达 40% 的性能提升，在适应图数据库的 SPIDER 基准上则取得了 30% 的性能提升。本工作证明，高质量的合成数据可以有效推进 Text2Cypher 任务的发展。 

---
# Unanswerability Evaluation for Retreival Augmented Generation 

**Title (ZH)**: 检索增强生成中的不可答性评估 

**Authors**: Xiangyu Peng, Prafulla Kumar Choubey, Caiming Xiong, Chien-Sheng Wu  

**Link**: [PDF](https://arxiv.org/pdf/2412.12300)  

**Abstract**: Existing evaluation frameworks for retrieval-augmented generation (RAG) systems focus on answerable queries, but they overlook the importance of appropriately rejecting unanswerable requests. In this paper, we introduce UAEval4RAG, a framework designed to evaluate whether RAG systems can handle unanswerable queries effectively. We define a taxonomy with six unanswerable categories, and UAEval4RAG automatically synthesizes diverse and challenging queries for any given knowledge base with unanswered ratio and acceptable ratio metrics. We conduct experiments with various RAG components, including retrieval models, rewriting methods, rerankers, language models, and prompting strategies, and reveal hidden trade-offs in performance of RAG systems. Our findings highlight the critical role of component selection and prompt design in optimizing RAG systems to balance the accuracy of answerable queries with high rejection rates of unanswerable ones. UAEval4RAG provides valuable insights and tools for developing more robust and reliable RAG systems. 

**Abstract (ZH)**: 现有的检索增强生成（RAG）系统评估框架主要关注可回答的查询，但忽略了适当拒绝不可回答请求的重要性。本文介绍了UAEval4RAG，一种旨在评估RAG系统处理不可回答查询能力的框架。我们定义了一个包含六个不可回答类别（unanswerable categories）的分类系统，并且UAEval4RAG能够自动为任何给定的知识库合成多样化且具有挑战性的查询，并使用未回答比例和可接受比例指标。我们对各种RAG组件，包括检索模型、重写方法、重排器、语言模型和提示策略进行了实验，揭示了RAG系统的性能中隐藏的权衡关系。研究发现强调了组件选择和提示设计在优化RAG系统方面的关键作用，以便在保证可回答查询精度的同时，提高对不可回答查询的拒绝率。UAEval4RAG为开发更为稳健和可靠的RAG系统提供了宝贵的见解和工具。 

---
# RemoteRAG: A Privacy-Preserving LLM Cloud RAG Service 

**Title (ZH)**: RemoteRAG：一种隐私保护的大规模语言模型云检索增强服务 

**Authors**: Yihang Cheng, Lan Zhang, Junyang Wang, Mu Yuan, Yunhao Yao  

**Link**: [PDF](https://arxiv.org/pdf/2412.12775)  

**Abstract**: Retrieval-augmented generation (RAG) improves the service quality of large language models by retrieving relevant documents from credible literature and integrating them into the context of the user query. Recently, the rise of the cloud RAG service has made it possible for users to query relevant documents conveniently. However, directly sending queries to the cloud brings potential privacy leakage. In this paper, we are the first to formally define the privacy-preserving cloud RAG service to protect the user query and propose RemoteRAG as a solution regarding privacy, efficiency, and accuracy. For privacy, we introduce $(n,\epsilon)$-DistanceDP to characterize privacy leakage of the user query and the leakage inferred from relevant documents. For efficiency, we limit the search range from the total documents to a small number of selected documents related to a perturbed embedding generated from $(n,\epsilon)$-DistanceDP, so that computation and communication costs required for privacy protection significantly decrease. For accuracy, we ensure that the small range includes target documents related to the user query with detailed theoretical analysis. Experimental results also demonstrate that RemoteRAG can resist existing embedding inversion attack methods while achieving no loss in retrieval under various settings. Moreover, RemoteRAG is efficient, incurring only $0.67$ seconds and $46.66$KB of data transmission ($2.72$ hours and $1.43$ GB with the non-optimized privacy-preserving scheme) when retrieving from a total of $10^6$ documents. 

**Abstract (ZH)**: 检索增强生成（RAG）通过从可靠文献中检索相关文档并将这些文档整合到用户查询的上下文中，从而提高了大型语言模型的服务质量。最近，云RAG服务的兴起使得用户能够方便地查询相关文档。然而，直接将查询发送到云中可能会带来潜在的隐私泄露问题。本文首次正式定义了保护用户查询隐私的云RAG服务，并提出了RemoteRAG作为针对隐私、效率和准确性问题的解决方案。为了保护隐私，我们引入了$(n,\epsilon)$-DistanceDP来表征用户查询及其从相关文档推断出的隐私泄露。为了提高效率，我们将搜索范围限制在由$(n,\epsilon)$-DistanceDP生成的扰动嵌入相关的少量选定文档之中，从而显著降低用于隐私保护的计算和通信成本。为了确保准确性，我们通过详细的理论分析确保少量文档范围内包含与用户查询相关的目标文档。实验结果还证实，RemoteRAG在多种设置下能够抵御现有嵌入反转攻击方法的同时，无需在检索性能上有所损失。此外，当从总共$10^6$个文档中检索时，RemoteRAG的效率仅为0.67秒和46.66KB的数据传输量（在未优化的隐私保护方案中，这一数据传输量分别为2.72小时和1.43GB）。 

---
# C-FedRAG: A Confidential Federated Retrieval-Augmented Generation System 

**Title (ZH)**: C-FedRAG：一种保密联邦检索增强生成系统 

**Authors**: Parker Addison, Minh-Tuan H. Nguyen, Tomislav Medan, Mohammad T. Manzari, Brendan McElrone, Laksh Lalwani, Aboli More, Smita Sharma, Holger R. Roth, Isaac Yang, Chester Chen, Daguang Xu, Yan Cheng, Andrew Feng, Ziyue Xu  

**Link**: [PDF](https://arxiv.org/pdf/2412.13163)  

**Abstract**: Organizations seeking to utilize Large Language Models (LLMs) for knowledge querying and analysis often encounter challenges in maintaining an LLM fine-tuned on targeted, up-to-date information that keeps answers relevant and grounded. Retrieval Augmented Generation (RAG) has quickly become a feasible solution for organizations looking to overcome the challenges of maintaining proprietary models and to help reduce LLM hallucinations in their query responses. However, RAG comes with its own issues regarding scaling data pipelines across tiered-access and disparate data sources. In many scenarios, it is necessary to query beyond a single data silo to provide richer and more relevant context for an LLM. Analyzing data sources within and across organizational trust boundaries is often limited by complex data-sharing policies that prohibit centralized data storage, therefore, inhibit the fast and effective setup and scaling of RAG solutions. In this paper, we introduce Confidential Computing (CC) techniques as a solution for secure Federated Retrieval Augmented Generation (FedRAG). Our proposed Confidential FedRAG system (C-FedRAG) enables secure connection and scaling of a RAG workflows across a decentralized network of data providers by ensuring context confidentiality. We also demonstrate how to implement a C-FedRAG system using the NVIDIA FLARE SDK and assess its performance using the MedRAG toolkit and MIRAGE benchmarking dataset. 

**Abstract (ZH)**: 致力于利用大规模语言模型（LLMs）进行知识查询和分析的组织可能会面临在保持模型对准最新信息方面的问题，从而确保答案的相关性和现实性。检索增强生成（RAG）已成为一种可行的解决方案，用于克服维护专有模型的挑战，并帮助减少LLM在查询响应中的幻觉。然而，RAG在其数据管道的分级访问和异质数据源之间扩展方面也存在自身的问题。在许多情况下，为了提供更丰富和相关的信息上下文，需要跨多个数据孤岛进行查询。在组织信任边界内分析数据源通常受限于复杂的数据共享政策，这些政策禁止集中存储数据，因此妨碍了RAG解决方案的快速有效设置和扩展。本文介绍加密计算（CC）技术作为安全联邦检索增强生成（FedRAG）的解决方案。我们提出的安全联邦RAG系统（C-FedRAG）通过确保上下文的机密性，使RAG工作流在去中心化的数据提供者网络中安全连接和扩展。我们还展示了如何使用NVIDIA FLARE SDK实现C-FedRAG系统，并使用MedRAG工具包和MIRAGE基准测试数据集对其性能进行了评估。 

---