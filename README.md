![image-20250531190327094](./imgs/pipline.png)
# HASH-RAG
Bridging Deep Hashing with Retriever for Efficient, Fine Retrieval and Augmented Generation

## Abstract
Retrieval-Augmented Generation (RAG) encounters efficiency challenges when scaling to massive knowledge bases while preserving contextual relevance. We propose Hash-RAG, a framework that integrates deep hashing techniques with systematic optimizations to address these limitations. Our queries directly learn binary hash codes from knowledgebase code, eliminating intermediate feature extraction steps, and significantly reducing storage and computational overhead. Building upon this hash-based efficient retrieval framework, we establish the foundation for fine-grained chunking. Consequently, we design a Prompt-Guided Chunk-to-Context (PGCC) module that leverages retrieved hash-indexed propositions and their original document segments through prompt engineering to enhance the LLM's contextual awareness. Experimental evaluations on NQ, TriviaQA, and HotpotQA datasets demonstrate that our approach achieves a 90\% reduction in retrieval time compared to conventional methods while maintaining considerate recall performance. Additionally, the proposed system outperforms retrieval/non-retrieval baselines by 1.4-4.3\% in EM scores.

## Code
coming soon
