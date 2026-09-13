# 26 A production data

仓库已通过 Git 直接上传完整的 `production_data.npz`。网页上传时的两个分卷仅作为备用。

Windows PowerShell：
```powershell
cmd /c copy /b production_data.npz.part1+production_data.npz.part2 production_data.npz
```

macOS/Linux：
```bash
cat production_data.npz.part1 production_data.npz.part2 > production_data.npz
```

合并后 SHA-256：`2e37875c8c1a6cbf7e612f800fa77b5128fabf1f7b4f55b953a7a75bc10c62e6`

将合并文件放到 `MODEL_AUDIT_COMMITTEE/PHASE1_V4/FORMAL_CONVERGENCE/production_data.npz`。
