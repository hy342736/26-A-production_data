# 26 A production data

GitHub 网页单文件限制为 25 MB，因此数据分为两个文件。下载 `production_data.npz.part1` 和 `production_data.npz.part2` 后放在同一目录。

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
