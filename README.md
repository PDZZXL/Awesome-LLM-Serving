# Awesome LLM Serving Papers
A curated list that categorizes the existing Large Language Model (LLM) Serving works. Star this repository, and you may gain some inspiration and contribute to the advancement of this research field.
## LLM Serving
### Scheduling
- [Orca](https://www.usenix.org/conference/osdi22/presentation/yu): A Distributed Serving System for Transformer-Based Generative Models | OSDI 22
- [SpotServe](https://arxiv.org/abs/2311.15566): Serving Generative Large Language Models on Preemptible Instances | CMU
- [ExeGPT:](https://arxiv.org/html/2404.07947v1) Constraint-Aware Resource Scheduling for LLM Inference| ASPLOS' 24
- [SuperServe:](https://arxiv.org/pdf/2312.16733.pdf) Fine-Grained Inference Serving for Unpredictable Workloads
- [Fairness in Serving Large Language Models](https://arxiv.org/abs/2401.00588) | OSDI' 24
- [Llumnix:](https://arxiv.org/abs/2406.03243) Dynamic Scheduling for Large Language Model Serving| OSDI' 24
### Memory/KVCache
- [FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness](https://arxiv.org/pdf/2205.14135.pdf)
- [vLLM](https://vllm.ai/): Easy, Fast, and Cheap LLM Serving with PagedAttention | SOSP' 23
- [vAttention:](https://arxiv.org/abs/2405.04437) Dynamic Memory Management for Serving LLMs without PagedAttention
- [DéjàVu](https://arxiv.org/abs/2403.01876): KV-cache Streaming for Fast, Fault-tolerant Generative LLM Serving
### Disaggregated
- [DistServe](https://arxiv.org/abs/2401.09670): Disaggregating Prefill and Decoding for Goodput-optimized Large Language Model Serving
- [Inference without Interference](https://arxiv.org/abs/2401.11181): Disaggregate LLM Inference for Mixed Downstream Workloads
- [Mooncake:](https://github.com/kvcache-ai/Mooncake/tree/main?tab=readme-ov-file) A KVCache-centric Disaggregated Architecture for LLM Serving | Moonshot
- [MemServe:](https://arxiv.org/abs/2406.17565) Context Caching for Disaggregated LLM Serving with Elastic Memory Pool | Huawei
### Resource-Constrained
- [FlexGen](https://arxiv.org/abs/2303.06865): High-throughput Generative Inference of Large Language Models with a Single GPU | ICML' 23
- [LLM in a flash: Efficient Large Language Model Inference with Limited Memory](https://arxiv.org/abs/2312.11514) | Apple
- [PowerInfer-2:](https://arxiv.org/abs/2406.06282) Fast Large Language Model Inference on a Smartphone | SJTU
- [LLMCad](https://arxiv.org/abs/2309.04255): Fast and Scalable On-device Large Language Model Inference
- [CaraServe](https://arxiv.org/abs/2401.11240): CPU-Assisted and Rank-Aware LoRA Serving for Generative LLM Inference
- [STI](https://arxiv.org/abs/2207.05022): Turbocharge NLP Inference at the Edge via Elastic Pipelining | ASPLOS 23 
### Heterogeneous
- [NeuPIMs:](https://arxiv.org/abs/2403.00579) NPU-PIM Heterogeneous Acceleration for Batched LLM Inferencing | ASPLOS'24
- [AttAcc!](https://github.com/scale-snu/attacc_simulator) Unleashing the Power of PIM for Batched Transformer-based Generative Model Inference | ASPLOS'24
- IANUS: Integrated Accelerator based on NPU-PIM Unified Memory System | ASPLOS'24
- [Helix:](https://arxiv.org/abs/2407.02490) Accelerating Pre-filling for Long-Context LLMs via Dynamic Sparse Attention | CMU
### Sparsity
- [Flash-LLM](https://arxiv.org/pdf/2309.10285v1.pdf): Enabling Cost-Effective and Highly-Efficient Large Generative Model Inference with Unstructured Sparsity | VLDB' 24
- [Deja Vu](https://proceedings.mlr.press/v202/liu23am.html): Contextual Sparsity for Efficient LLMs at Inference Time | ICML' 23
- [MInference 1.0](https://proceedings.mlr.press/v202/liu23am.html): Accelerating Pre-filling for Long-Context LLMs via Dynamic Sparse Attention | Microsoft
- [QServe:](https://github.com/mit-han-lab/qserve) W4A8KV4 Quantization and System Co-design for Efficient LLM Serving | MIT
### Speculative
- [SpecInfer](https://www.cs.cmu.edu/~zhihaoj2/papers/specinfer.pdf): Accelerating Generative LLM Serving with Speculative Inference and Token Tree Verification | CMU
- [Optimizing Speculative Decoding for Serving Large Language Models Using Goodput](https://arxiv.org/abs/2406.14066v1) | UCB
### Multiple LLM
- [MuxServe:](https://arxiv.org/abs/2404.02015) Flexible Multiplexing for Efficient Multiple LLM Serving
- [BlockLLM:](https://arxiv.org/abs/2404.18322) Multi-tenant Finer-grained Serving for Large Language Models
- [Punica](https://arxiv.org/abs/2310.18547): Multi-Tenant LoRA Serving

### Agent
- [AutoGen](https://arxiv.org/abs/2308.08155): Enabling Next-Gen LLM Applications via Multi-Agent Conversation | Microsoft

## Misc
- [Efficiently Scaling Transformer Inference](https://arxiv.org/pdf/2211.05102.pdf) | MLSys' 23
- [DeepSpeed Inference](https://arxiv.org/abs/2207.00032) : Enabling Efficient Inference of Transformer Models at Unprecedented Scale.  
- [SARATHI](https://arxiv.org/abs/2308.16369): Efficient LLM Inference by Piggybacking Decodes with Chunked Prefills | Microsoft 
- [Tabi](https://dl.acm.org/doi/pdf/10.1145/3552326.3587438): An Efficient Multi-Level Inference System for Large Language Models | EuroSys' 23 
- [FlashDecoding++](https://arxiv.org/pdf/2311.01282.pdf): Faster Large Language Model Inference on GPUs | Tsinghua
- [DeepSpeed-MII](https://github.com/microsoft/DeepSpeed-MII): Model Implementations for Inference (MII) ｜ Microsoft
- [S-LoRA](https://arxiv.org/abs/2311.03285): Serving Thousands of Concurrent LoRA Adapters
- [Infinite-LLM](https://arxiv.org/abs/2401.02669): Efficient LLM Service for Long Context with DistAttention and Distributed KVCache
- [APIServe](https://arxiv.org/pdf/2402.01869.pdf): Efficient API Support for Large-Language Model Inferencing
- [FlexLLM](https://arxiv.org/abs/2402.18789): A System for Co-Serving Large Language Model Inference and Parameter-Efficient Finetuning
- [AttentionStore:](https://arxiv.org/pdf/2403.19708.pdf) Cost-effective Attention Reuse across Multi-turn Conversations in Large Language Model Serving | NUS
- [LoongServe:](https://arxiv.org/pdf/2404.09526.pdf) Efficiently Serving Long-context Large Language Models with Elastic Sequence Parallelism | PKU
- [Andes:](https://arxiv.org/abs/2404.16283) Defining and Enhancing Quality-of-Experience in LLM-Based Text Streaming Services | Umich


## Other list
- [LLM systems paper list](https://github.com/AmberLJC/LLMSys-PaperList)
- [A curated list of LLM inference](https://github.com/DefTruth/Awesome-LLM-Inference)
- [A curated list of Large Language Model](https://github.com/Hannibal046/Awesome-LLM)
- [AI systems paper list](https://github.com/lambda7xx/awesome-AI-system)
- [A baseline repository of Auto-Parallelism in Training Neural Networks](https://github.com/ConnollyLeon/awesome-Auto-Parallelism)
- [Numbers every LLM Developer should know](https://github.com/ray-project/llm-numbers)

