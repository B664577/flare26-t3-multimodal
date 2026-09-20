# FLARE 2026 Task 3 — Multimodal Medical Image Understanding (QLoRA on MedGemma)

**Team longkongmedai / AI4Viaevum** · MICCAI 2026 FLARE Challenge

> 队长/一作：胡敏莉 · 队员：崔瑾、刘婉婉、赖龙 · 通讯：张丽萍

## Method (summary)

QLoRA fine-tuning of MedGemma inside the official baseline container; CPU-only
end-to-end inference verified. Online validation **0.4222**（官方未微调基线 0.4027，
当前榜首 0.48）。176 个私有模态问题无图像可推理、如实占位计 0（约占 9%）。

## Results (online validation)

| Version | Score |
|---|---|
| Official MedGemma1 unfused baseline | 0.4027 |
| **Ours QLoRA v3** | **0.4222** |
| Current leader | 0.48 |

## Environment & reproduction

随论文定稿补齐。

## Reproducibility checklist

- [x] 结果表（真实线上数字）
- [x] 方法描述（论文正文）
- [ ] 环境锁定 + 一键脚本 + LoRA 权重
