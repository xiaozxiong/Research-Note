# LLM 

## Accelerating Inference on GPU

- Torpor: GPU-Enabled Serverless Computing for Low-Latency, Resource-Efficient Inference (ATC 25)
- SpInfer: Leveraging Low-Level Sparsity for Efficient Large Language Model Inference on GPUs (EuroSys 25)
- WaferLLM: Large Language Model Inference at Wafer Scale (OSDI 25)

## Attention

### FlashAttention

- FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness
- FlashAttention-2: Faster Attention with Better Parallelism and Work Partitioning
- FlashAttention-3: Fast and Accurate Attention with Asynchrony and Low-precision

### Others

- Fast Transformer Decoding: One Write-Head is All You Need (MQA)
- GQA: Training Generalized Multi-Query Transformer Models from Multi-Head Checkpoints
- Efficient Memory Management for Large Language Model Serving with PagedAttention (SOSP '23)
- WEAVER: Efficient Multi-LLM Serving with Attention Offloading (ATC 25)

## Speculative Decoding

- SpecInfer: Accelerating Large Language Model Serving with Tree-based Speculative Inference and Verification (ASPLOS '24)

## Library

- [FlashInfer](https://github.com/flashinfer-ai/flashinfer.git)

## KV Cache 

- SGLang: Efficient Execution of Structured Language Model Programs
- RAGCache: Efficient Knowledge Caching for Retrieval-Augmented Generation
- KVFlow: Efficient Prefix Caching for Accelerating LLM-Based Multi-Agent Workflows
- KVCache Cache in the Wild: Characterizing and Optimizing KVCache Cache at a Large Cloud Provider (ATC 25)
- MOONCAKE: Trading More Storage for Less Computation – A KVCache-centric Architecture for Serving LLM Chatbot (FAST 25)
- CacheBlend: Fast Large Language Model Serving for RAG with Cached Knowledge Fusion (EuroSys 25)
- Fast State Restoration in LLM Serving with HCache (EuroSys 25)
- Stateful Large Language Model Serving with Pensieve (EuroSys 25)