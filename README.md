# 小說創作項目 - novel-yuzhe2

## 📁 文件夾結構

```
novel-yuzhe2/
├── chapters/        # 章節文件
│   └── ch_001.md    # 命名格式：ch_XXX.md
├── reports/         # 審核結果
│   ├── verify_*.md  # Verify Agent 審核報告
│   └── final_*.md   # Final Reviewer 審核報告
├── outlines/        # 大綱與創意
│   ├── idea_*.md    # Idea Agent 創意大綱
│   └── plot_*.md    # Plot Agent 情節設計
├── reference/       # 參考資料
│   └── reader_*.md  # Reader Agent 風格分析
└── README.md        # 本文件
```

## 📝 命名規範

### 章節文件 (chapters/)
- 格式：`ch_001.md`, `ch_002.md`, `ch_003.md`...
- 三位數字編號，不足補零

### 審核報告 (reports/)
- Verify 報告：`verify_ch_001.md`, `verify_ch_002.md`...
- Final 報告：`final_ch_001.md`, `final_ch_002.md`...

### 大綱文件 (outlines/)
- Idea 大綱：`idea_main.md`, `idea_arc_01.md`...
- Plot 設計：`plot_main.md`, `plot_arc_01.md`...

### 參考資料 (reference/)
- 風格分析：`reader_style_analysis.md`
- 爽點爆點：`reader_highlights.md`

## 🔄 工作流程

1. **Reader Agent** → `reference/` 存放風格分析
2. **Idea Agent** → `outlines/` 存放創意大綱
3. **Plot Agent** → `outlines/` 存放情節設計
4. **Writer Agent** → `chapters/` 存放章節初稿
5. **Verify Agent** → `reports/` 存放審核報告
6. **Final Reviewer** → `reports/` 存放最終審核

---

*此文件夾結構由 Ri 於 2026-03-17 創建*
