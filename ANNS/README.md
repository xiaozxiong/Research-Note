# Approximate Nearest Neighbor Search

## Paper List

### Graph Index

- Monotonic Search Networks For Computer Vision Databases
- [Approximate Nearest Neighbor Queries in Fixed Dimensions](https://www.cs.umd.edu/~mount/Papers/soda93-ann.pdf)
- [Efficient and robust approximate nearest neighbor search using Hierarchical Navigable Small World graphs](https://arxiv.org/abs/1603.09320), [hnswlib](https://github.com/nmslib/hnswlib.git)
- [Fast Approximate Nearest Neighbor Search With The Navigating Spreading-out Graph](https://arxiv.org/abs/1707.00143), [NSG](https://github.com/ZJULearning/nsg.git)
- [High Dimensional Similarity Search With Satellite System Graph: Efficiency, Scalability, and Unindexed Query Compatibility (TPAMI)](https://ieeexplore.ieee.org/document/9383170), [code](https://github.com/ZJULearning/SSG.git)
- [Improving Approximate Nearest Neighbor Search through Learned Adaptive Early Termination (SIGMOD 2020)](https://dl.acm.org/doi/pdf/10.1145/3318464.3380600), [code](https://github.com/efficient/faiss-learned-termination.git)
- [A Comprehensive Survey and Experimental Comparison of Graph-Based Approximate Nearest Neighbor Search (VLDB 2021)](https://www.vldb.org/pvldb/vol14/p1964-wang.pdf), [code](https://github.com/Lsyhprum/WEAVESS.git)
- [Graph Reordering for Cache-Efficient Near Neighbor Search (NeurIPS 2022)](https://papers.nips.cc/paper_files/paper/2022/hash/fb44a668c2d4bc984e9d6ca261262cbb-Abstract-Conference.html)
- [GraSP: Optimizing Graph-based Nearest Neighbor Search with Subgraph Sampling and Pruning (WSDM 2022)](https://dl.acm.org/doi/pdf/10.1145/3488560.3498425)
- ELPIS: Graph-Based Similarity Search for Scalable Data Science (VLDB 2023)
- Relative NN-Descent: A Fast Index Construction for Graph-Based Approximate Nearest Neighbor Search (MM 2023), [code](https://github.com/mti-lab/rnn-descent.git)
- [iQAN: Fast and Accurate Vector Search with Efficient Intra-Query Parallelism on Multi-Core Architectures (PPoPP 2023)](https://dl.acm.org/doi/pdf/10.1145/3572848.3577527)
- [ParlayANN: Scalable and Deterministic Parallel Graph-Based Approximate Nearest Neighbor Search Algorithms (PPoPP 2024)](https://dl.acm.org/doi/pdf/10.1145/3627535.3638475), [code](https://github.com/cmuparlay/ParlayANN.git)

### Hybrid Index

- Routing-Guided Learned Product Quantization for Graph-Based Approximate Nearest Neighbor Search (ICDE 2024), [code](https://github.com/Lsyhprum/BREWESS.git)
- Efficient Reverse k Approximate Nearest Neighbor Search over High-Dimensional Vectors (ICDE 2024)

### Optimization

- High-Dimensional Approximate Nearest Neighbor Search: with Reliable and Efficient Distance Comparison Operations (SIGMOD 2023), [code](https://github.com/gaoj0017/ADSampling.git)
- FINGER: Fast Inference for Graph-based Approximate Nearest Neighbor Search (WWW 2023)

### Analysis

- Approximate Nearest Neighbor Search on High Dimensional Data — Experiments, Analyses, and Improvement (TKDE), [code](https://github.com/DBAIWangGroup/nns_benchmark.git)

- Worst-case Performance of Popular Approximate Nearest Neighbor Search Implementations: Guarantees and Limitations (NeurIPS 2023)

### Billion-scale ANNS

- Billion-scale similarity search with GPUs, [Faiss](https://github.com/facebookresearch/faiss.git)
- DiskANN: Fast Accurate Billion-point Nearest Neighbor Search on a Single Node (NeurIPS 2019), [DiskANN](https://github.com/microsoft/DiskANN.git)
- HM-ANN: Efficient Billion-Point Nearest Neighbor Search on Heterogeneous Memory (NeurIPS 2020)
- [SPANN: Highly-efficient Billion-scale Approximate Nearest Neighbor Search (NeurIPS 2021)](https://proceedings.neurips.cc/paper/2021/file/299dc35e747eb77177d9cea10a802da2-Paper.pdf), [code](https://github.com/microsoft/SPTAG.git)
- [FreshDiskANN: A Fast and Accurate Graph-Based ANN Index for Streaming Similarity Search](https://arxiv.org/pdf/2105.09613.pdf)
- [Starling: An I/O-Efficient Disk-Resident Graph Index Framework for High-Dimensional Vector Similarity Search on Data Segment (SIGMOD 2024)](https://dl.acm.org/doi/pdf/10.1145/3639269), [code](https://github.com/zilliztech/starling.git)

### Graph Index on GPU

- SONG: Approximate Nearest Neighbor Search on GPU (ICDE 2020), [code](https://github.com/sunbelbd/song.git)
- GPU-accelerated Proximity Graph Approximate Nearest Neighbor Search and Construction (ICDE 2022), [code](https://github.com/yuyuanhang/GANNS.git)
- CAGRA: Highly Parallel Graph Construction and Approximate Nearest Neighbor Search for GPUs (ICDE 2024), [code](https://github.com/rapidsai/raft.git)
- GGNN: Graph-based GPU Nearest Neighbor Search, [code](https://github.com/cgtuebingen/ggnn.git)

### ANNS with Attribute Constraint

- AnalyticDB-V: a hybrid analytical engine towards query fusion for structured and unstructured data (VLDB 2019)

- [Constrained Approximate Similarity Search on Proximity Graph](https://arxiv.org/abs/2210.14958)
- [Navigable Proximity Graph-Driven Native Hybrid Queries with Structured and Unstructured Constraints](https://arxiv.org/abs/2203.13601)
- [CAPS: A Practical Partition Index for Filtered Similarity Search](https://arxiv.org/abs/2308.15014)
- [Milvus: A Purpose-Built Vector Data Management System (SIGMOD 2021)](https://dl.acm.org/doi/10.1145/3448016.3457550)
- [HQANN: Efficient and Robust Similarity Search for Hybrid Queries with Structured and Unstructured Constraints (CIKM 2022)](https://dl.acm.org/doi/pdf/10.1145/3511808.3557610)
- [VBase: Unifying Online Vector Similarity Search and Relational Queries via Relaxed Monotonicity (OSDI 2023)](https://www.usenix.org/system/files/osdi23-zhang-qianxi_1.pdf), [code](https://github.com/microsoft/MSVBASE.git)
- [ARKGraph: All-Range Approximate K-Nearest-Neighbor Graph (VLDB 2023)](https://dl.acm.org/doi/pdf/10.14778/3603581.3603601), [code](https://github.com/rutgers-db/ARKGraph.git)
- [Filtered−DiskANN: Graph Algorithms for Approximate Nearest Neighbor Search with Filters (WWW 2023)](https://harsha-simhadri.org/pubs/Filtered-DiskANN23.pdf)
- [An Efficient and Robust Framework for Approximate Nearest Neighbor Search with Attribute Constraint (NeurIPS 2023)](https://papers.nips.cc/paper_files/paper/2023/hash/32e41d6b0a51a63a9a90697da19d235d-Abstract-Conference.html)
- [SeRF: Segment Graph for Range-Filtering Approximate Nearest Neighbor Search (SIGMOD 2024)](https://dl.acm.org/doi/pdf/10.1145/3639324), [code](https://github.com/rutgers-db/SeRF.git)
- [Approximate Nearest Neighbor Search with Window Filters](https://arxiv.org/abs/2402.00943)

## Others

### Billion-Scale Approximate Nearest Neighbor Search Challenge

- [NeurIPS'21 competition track](https://big-ann-benchmarks.com/neurips21.html)
- [NeurIPS'23 Competition Track: Big-ANN](https://big-ann-benchmarks.com/neurips23.html)

### ANN Benchmarks

- [ANN-Benchmarks](https://ann-benchmarks.com/)

## Dataset

### fbin & ibin

All embedding data (base, query, learning) is stored in `.fbin` format. And all ground truth is strored in `.ibin` format.

```python
# .fbin format:
[num_vectors (uint32), vector_dim (uint32), vector_array (float32)]
# .ibin format:
[num_vectors (uint32), vector_dim (uint32), vector_array (int32)]
```

### fvecs & ivecs

The vector files are stored in `.fvecs` or `.bvecs` format, and the ground truth file is `.ivecs` format. The only difference between `.bvecs`, `.fvecs` and `.ivecs` files is the base type for the vector components, which is **unsigned char**, **float** or **int**, respectively. 

```python
# Each vector takes (4+d*4) bytes for .fvecs and .ivecs formats, d is dimension.
# .fvecs format and .ivecs format:
[(dim, vector), (dim, vector), ...]
```

### Billion-scale

|                           Dataset                            | DataType | Dimensions | Base Data | Query Data | Top-K |   Distance    |
| :----------------------------------------------------------: | :------: | :--------: | :-------: | :--------: | :---: | :-----------: |
|           [SIFT1B](http://corpus-texmex.irisa.fr/)           |  uint8   |    128     |    1B     |    10K     |  100  |      L2       |
| [DEEP1B](https://research.yandex.com/blog/benchmarks-for-billion-scale-similarity-search) | float32  |     96     |    1B     |    10K     |  100  |      L2       |
| [Text-to-Image-1B](https://research.yandex.com/blog/benchmarks-for-billion-scale-similarity-search) | float32  |    200     |    1B     |    100K    |       | inner-product |
| [Microsoft Turing-ANNS](https://learning2hash.github.io/publications/microsoftturinganns1B/) | float32  |    100     |    1B     |    100K    |       |      L2       |
| [Microsoft SPACEV-1B](https://github.com/microsoft/SPTAG/tree/main/datasets/SPACEV1B) |   int8   |    100     |    1B     |   29.3K    |  100  |      L2       |

The ground truth for deep1M, deep10M, and deep100M datasets can be download from [here](https://github.com/matsui528/deep1b_gt.git).

### Million-scale

|  Dataset  | Dimensions | Base Size | Query Size |  k   |
| :-------: | :--------: | :-------: | :--------: | :--: |
|   MNIST   |    784     |  60,000   |   10,000   | 100  |
| GloVe-100 |    100     | 1,183,514 |   10,000   | 100  |
| GloVe-200 |    200     | 1,183,514 |   10,000   | 100  |
|  GIST1M   |    960     | 1,000,000 |   1,000    | 100  |
|  SIFT1M   |    128     | 1,000,000 |   10,000   | 100  |
|  NYTimes  |    256     |  290,000  |   10,000   | 100  |

