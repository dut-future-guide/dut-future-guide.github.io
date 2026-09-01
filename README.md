# DUT-Future-Guide
DUT 未来技术学院生存指南


1. 创建 Conda 环境

```bash
conda create -n dut-guide python=3.11 -y
conda activate dut-guide
```

安装 MkDocs Material：

```bash
python -m pip install mkdocs-material
```

2. 本地预览

执行：

```bash
mkdocs serve
```

3. 更新

写完后：

```bash
mkdocs build
git add .
git commit -m "update story content"
git push
```