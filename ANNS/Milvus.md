# Milvus

## System Design

![](./milvus.png)

### Entry

Each entity in Milvus is described as one or more **vectors** and optionally some numerical **attributes** (non-vector data).

### Three primitive query types

- Vector query
- Attribute filtering
- Multi-vector query

###  Indexing

- **Quantization-based indexes**: IVF_FLAT, IVF_SQ8, and IVF_PQ
- **Graph-based indexes**: HNSW, NSG

### Dynamic Data Management

Milvus supports efficient **insertions** and **deletions** by adopting the idea of **LSM-tree**.

##  Heterogeneous Computing

### **CPU-oriented Optimizations**

- Cache-aware optimizations
- SIMD-aware optimizations
  - Supporting AVX512
  - Automatic SIMD-instruction selection

### GPU-oriented Optimizations