# 这个检验用于检验两个样本的分布是否一致
# 函数用法：

ks.test(x, "pnorm", mean = μ, sd = σ)# 单样本和某个标准的分布
ks_test_result <- ks.test(x, y)# 进行两样本KS检验


# 文章中的实列
https://www.sciencedirect.com/science/article/pii/S1074761324000839?via%3Dihub#sec2.1
![Uploading 微信图片_20240327165319.png…]()

# 简介：作者使用slingshot给cd4+和cd8+细胞进行pesudo分析，然后给pesudotime末端的细胞群之间使用ks检验计算是否有差异，这样的作法可以观察看患者经过不同处理之后的细胞分化演变情况是否有差异。

# 原文：(E) Density plots showing the distribution of T cells (upper panels) or expanded T cells (middle and lower panels) along the CD4+ Th1, CD8+ Tex, and Trm trajectories, as calculated by Slingshot, while stratifying for treatment arm (upper panels) or sample type (middle and lower panels). The overlapping area between treatment arms is gray. Differences in distributions were calculated by the KS.test (see STAR Methods). Tn/cm, naive/central-memory T cell; Tem, effector/memory T cell; Th1, T helper 1 cell; Th17, T helper 17 cell; Tfh, follicular helper T cell; Treg, regulatory T cell; Temra, effector-memory re-expressing CD45RA T cell; Tex, exhausted T cell; Trm, tissue-resident memory T cell; NKinfla, inflammatory natural killer cell; NKcyto, cytotoxic natural killer cell.
