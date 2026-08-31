# AIC 2026 修正版原始数据集 (赛方 2026-08-31 校准)

**内容**: 训练集 2000 张三模态 + 赛方校准标签 new_labels_2000 (382文件改动, 总框 14417→15195, class_6/8 各 +378/+380) + 测试集 1000 张三模态。

**目录**:
- 训练集/AIC2026_Train_2000/{visible, infrared, depth, labels} — labels 与旧版完全相同
- 训练集/new_labels_2000/ — ⚠️ 校准后的标签, 训练必须用它
- 测试集/AIC2026_PHASE_1_1000/{visible, infrared, depth}

**深度图**: PNG 为 16-bit uint16 毫米值 [0,19999]; 小图 JPG 为 8-bit 灰度 (线性编码 v*19999/255)。
