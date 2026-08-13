# 国规教材 · 智能体工作流实训项目集

[![Author](https://img.shields.io/badge/作者-管乙聲-0B6E4F)](https://lunan.cloud/)
[![Rights](https://img.shields.io/badge/权利-All%20Rights%20Reserved-b91c1c)](./LICENSE)
[![Certificate](https://img.shields.io/badge/证书-CERTIFICATE.md-1d4ed8)](./CERTIFICATE.md)
[![Site](https://img.shields.io/badge/官网-lunan.cloud-2563eb)](https://lunan.cloud/)

> **作者：管乙聲**　|　电话：13518764518　|　**制作侵权必究**  
> 官网：https://lunan.cloud/  
> GitHub：https://github.com/guanyisheng/National-Standard-Textbook-Smart-Agent-Workflow-Training-Project-Collection/

本仓库为作者独立完成/整理的**国规教材配套智能体工作流实训项目**（扣子编程 / Coze Vibe Coding 导出），含 **8 套可运行工作流**、流程图、节点说明与扣子导入包，用于教学演示与实训。

**请勿冒名使用。** 权属见 [`LICENSE`](./LICENSE)，证书见 [`CERTIFICATE.md`](./CERTIFICATE.md)，校验见 [`SHA256SUMS.txt`](./SHA256SUMS.txt)。

---

## 仓库结构

```text
.
├── README.md                 # 本说明（GitHub 首页）
├── CERTIFICATE.md            # 著作权声明证书
├── LICENSE                   # 保留所有权利
├── AUTHORS                   # 作者署名
├── SHA256SUMS.txt            # SHA-256 校验清单
├── docs/                     # 发布清单、作品声明、教材相关文档
├── 工作流图片/                # 项目1–8 流程图合集（推荐先看）
├── 扣子导入包/                # project1.zip … project8.zip
├── 项目1：学习规划工作流/
├── 项目2：智能任务规划与模块协作智能体项目/
├── 项目3：客户服务工作流管理平台/
├── 项目4 心理情感支持智能体/
├── 项目5：企业知识库增强（RAG）数智员工项目/
├── 项目6：智能学习助手单智能体应用开发项目/
├── 项目7：多智能体企业运营助手/
└── 项目8：AI数字员工综合应用平台/
```

> 本地另有 `release/`（发布 zip）与 `_私密/`（无水印备份），默认不入库。

---

## 项目一览

| # | 目录 | 流程图 |
|---|------|--------|
| 1 | [`项目1：学习规划工作流`](./项目1：学习规划工作流) | [`工作流图片/01-…`](./工作流图片/01-学习规划工作流.png) |
| 2 | [`项目2：智能任务规划与模块协作智能体项目`](./项目2：智能任务规划与模块协作智能体项目) | [`工作流图片/02-…`](./工作流图片/02-智能任务规划与模块协作.png) |
| 3 | [`项目3：客户服务工作流管理平台`](./项目3：客户服务工作流管理平台) | [`工作流图片/03-…`](./工作流图片/03-客户服务工作流管理平台.png) |
| 4 | [`项目4 心理情感支持智能体`](./项目4%20心理情感支持智能体) | [`工作流图片/04-…`](./工作流图片/04-心理情感支持智能体.png) |
| 5 | [`项目5：企业知识库增强（RAG）数智员工项目`](./项目5：企业知识库增强（RAG）数智员工项目) | [`工作流图片/05-…`](./工作流图片/05-企业知识库增强RAG.png) |
| 6 | [`项目6：智能学习助手单智能体应用开发项目`](./项目6：智能学习助手单智能体应用开发项目) | [`工作流图片/06-…`](./工作流图片/06-智能学习助手单智能体.png) |
| 7 | [`项目7：多智能体企业运营助手`](./项目7：多智能体企业运营助手) | [`工作流图片/07-…`](./工作流图片/07-多智能体企业运营助手.png) |
| 8 | [`项目8：AI数字员工综合应用平台`](./项目8：AI数字员工综合应用平台) | [`工作流图片/08-…`](./工作流图片/08-AI数字员工综合应用平台.png) |

每个项目通常包含：

- `工作流.png` — 流程图  
- `AGENTS.md` — 节点说明  
- `src/graphs/graph.py` — 工作流编排  
- `src/graphs/nodes/` — 节点实现  
- `config/` — 大模型节点配置  
- `scripts/local_run.sh` — 本地运行入口  

---

## 怎么用

1. **看全套流程图** → [`工作流图片/`](./工作流图片/)  
2. **看节点逻辑** → 进入对应项目，打开 `AGENTS.md`  
3. **导入扣子编程** → [`扣子导入包/`](./扣子导入包/) 上传对应 `projectN.zip`  
4. **本地跑源码** → 进入项目目录，按该项目 `README.md` / `scripts/` 执行  

---

## 权属与核验

| 文件 | 作用 |
|------|------|
| [`CERTIFICATE.md`](./CERTIFICATE.md) | 著作权声明证书（编号 `GG-AW-20260814-V100`） |
| [`LICENSE`](./LICENSE) | 保留所有权利 · 禁止冒名 |
| [`AUTHORS`](./AUTHORS) | 作者署名 |
| [`SHA256SUMS.txt`](./SHA256SUMS.txt) | 文件指纹 |
| [`docs/作品声明与校验哈希.md`](./docs/作品声明与校验哈希.md) | 详细校验说明 |
| [`docs/公开发布操作清单.md`](./docs/公开发布操作清单.md) | 公开发布步骤 |

公开核验入口：

- 本仓库：https://github.com/guanyisheng/National-Standard-Textbook-Smart-Agent-Workflow-Training-Project-Collection/  
- 官网：https://lunan.cloud/  

---

## 声明

```text
作者：管乙聲
电话：13518764518
官网：https://lunan.cloud/
GitHub：https://github.com/guanyisheng/National-Standard-Textbook-Smart-Agent-Workflow-Training-Project-Collection/
作品：国规教材 · 智能体工作流实训项目集（项目1–8）
态度：制作侵权必究；禁止未授权署名为他人
```

如需授权合作，请联系作者本人。
