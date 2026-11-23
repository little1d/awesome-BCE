# awesome-BCE

B 细胞表位预测的代表方法与评测文献。代码列中的「—」表示本表尚未收录源码链接。

## 数据集与评测资源

| 资源 | 类型 | 用途 |
|---|---|---|
| [IEDB](https://www.iedb.org/) | 免疫测定数据库 | 按 B 细胞实验类型查找表位与抗体结合记录 |
| [RCSB PDB](https://www.rcsb.org/) | 结构数据库 | 获取实验复合物坐标，核对结构条目与链 |
| [SAbDab2](https://sabdab.opig.stats.ox.ac.uk/) | 抗体结构数据库 | 检索抗体与抗原配对，获取机器学习数据集 |
| [ANABAG](https://zenodo.org/records/17065788) | 注释复合物数据集 | 按复合物和残基层面的结构特征筛选样本 |
| [AsEP](https://github.com/biochunan/AsEP-dataset) | 抗体特异性表位基准 | 使用表位组划分测试未见表位组的定位能力 |
| [EAg / EAg_rep](https://github.com/3BioCompBio/BCellEpitope) | 构象表位基准 | 比较单个复合物与汇总已知表位的代表抗原标注 |
| [ABAG-docking](https://github.com/Zhaonan99/Antibody-antigen-complex-structure-benchmark-dataset) | 对接基准 | 评估配对抗体与抗原的复合物姿态 |
| [Yu et al.](https://zenodo.org/records/20710876) | 界面评测集 | 对照整体对接质量、表位残基与精细界面接触的恢复 |

## 序列输入

| 论文 | 年份和会议 / 期刊 | 代码 |
|---|---|---|
| [Improved method for predicting linear B-cell epitopes](https://doi.org/10.1186/1745-7580-2-2) | 2006 · Immunome Res | — |
| [Predicting linear B-cell epitopes using string kernels](https://doi.org/10.1002/jmr.893) | 2008 · J Mol Recognit | — |
| [BepiPred-2.0: improving sequence-based B-cell epitope prediction using conformational epitopes](https://doi.org/10.1093/nar/gkx346) | 2017 · Nucleic Acids Res | — |
| [BepiPred-3.0: Improved B-cell epitope prediction using protein language models](https://doi.org/10.1002/pro.4497) | 2022 · Protein Sci | — |

## 结构输入

| 论文 | 年份和会议 / 期刊 | 代码 |
|---|---|---|
| [CEP: a conformational epitope prediction server](https://doi.org/10.1093/nar/gki460) | 2005 · Nucleic Acids Research | — |
| [Prediction of residues in discontinuous B-cell epitopes using protein 3D structures](https://doi.org/10.1110/ps.062405906) | 2006 · Protein Sci | — |
| [Reliable B Cell Epitope Predictions: Impacts of Method Development and Improved Benchmarking](https://doi.org/10.1371/journal.pcbi.1002829) | 2012 · PLoS Comput Biol | — |
| [Identifying B-cell epitopes using AlphaFold2 predicted structures and pretrained language model](https://doi.org/10.1093/bioinformatics/btad187) | 2023 · Bioinformatics | [GitHub](https://github.com/biomed-AI/GraphBepi) |
| [DiscoTope-3.0: improved B-cell epitope prediction using inverse folding latent representations](https://doi.org/10.3389/fimmu.2024.1322712) | 2024 · Front Immunol | — |
| [PatchEpi: patch-aware equivariant learning improves structure-based epitope prediction](https://doi.org/10.1093/bioinformatics/btag678) | 2026 · Bioinformatics | [GitHub](https://github.com/wsicheng739/PatchEpi) |

## 抗体条件预测

| 论文 | 年份和会议 / 期刊 | 代码 |
|---|---|---|
| [Improving B-cell epitope prediction and its application to global antibody-antigen docking](https://doi.org/10.1093/bioinformatics/btu190) | 2014 · Bioinformatics | — |
| [Learning context-aware structural representations to predict antigen and antibody binding interfaces](https://doi.org/10.1093/bioinformatics/btaa263) | 2020 · Bioinformatics | [GitHub](https://github.com/vamships/PECAN) |
| [EpiScan: accurate high-throughput mapping of antibody-specific epitopes using sequence information](https://doi.org/10.1038/s41540-024-00432-7) | 2024 · NPJ Syst Biol Appl | [GitHub](https://github.com/gzBiomedical/EpiScan) |
| [Deciphering Fingerprints of 3D Molecular Surfaces for Accurate Epitope Prediction](https://doi.org/10.1145/3770855.3818825) | 2026 · KDD | — |

## 基准与独立评测

| 论文 | 年份和会议 / 期刊 | 代码 |
|---|---|---|
| [Benchmarking B cell epitope prediction: underperformance of existing methods](https://doi.org/10.1110/ps.041059505) | 2005 · Protein Science | — |
| [Towards a consensus on datasets and evaluation metrics for developing B-cell epitope prediction tools](https://doi.org/10.1002/jmr.815) | 2007 · J Mol Recognit | — |
| [Antibody-protein interactions: benchmark datasets and prediction tools evaluation](https://doi.org/10.1186/1472-6807-7-64) | 2007 · BMC Struct Biol | — |
| [Inadequate Reference Datasets Biased toward Short Non-epitopes Confound B-cell Epitope Prediction](https://doi.org/10.1074/jbc.M116.729020) | 2016 · Journal of Biological Chemistry | — |
| [Critical review of conformational B-cell epitope prediction methods](https://doi.org/10.1093/bib/bbac567) | 2023 · Brief Bioinform | [GitHub](https://github.com/3BioCompBio/BCellEpitope) |
| [AsEP: Benchmarking Deep Learning Methods for Antibody-specific Epitope Prediction](https://doi.org/10.52202/079017-0373) | 2024 · NeurIPS | [GitHub](https://github.com/biochunan/AsEP-dataset) |
| [ABAG-docking benchmark: a non-redundant structure benchmark dataset for antibody-antigen computational docking](https://doi.org/10.1093/bib/bbae048) | 2024 · Brief Bioinform | [GitHub](https://github.com/Zhaonan99/Antibody-antigen-complex-structure-benchmark-dataset) |
| [Benchmarking antibody modeling tools across structure prediction, docking, and paratope-epitope interface analysis](https://doi.org/10.1093/bioadv/vbag223) | 2026 · Bioinform Adv | [Zenodo](https://zenodo.org/records/20710876) |
