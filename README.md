# UKB Conformal Survival Band · 演示版 (Demo)

基于 [Sesia & Svetnik (2025) *Conformal Survival Bands*](https://arxiv.org/abs/2410.05045) 的个体生存带可视化工具**演示版**。

- 使用**合成数据**（Cox 模拟），**不含任何 UK Biobank 数据或模型权重**，可自由下载使用。
- 双击即可运行，无需安装 Python / PyTorch / 任何依赖。
- 完整流水线：Cox 拟合 → IPCW 删失加权 → 保形生存带（双稳健端点）→ 低/高风险标记 → 绘图，导出 PNG/SVG/PDF。

## 下载

见右侧 **Releases** → 下载 `UKB_SurvivalBand_demo.exe`，双击运行。

## 校验

```
SHA256  33bd5d0117dd405a1c01bdca9e02ca3440b34069fc06a23cf4a2ecb013b28227
Size    73,884,191 bytes
```

> 完整版（含 M2 五/六模态模型权重与 UK Biobank 校准数据）仅供已获 UKB 数据使用授权的合作者获取，位于私有仓库 `ukb-survival-band-full`。
