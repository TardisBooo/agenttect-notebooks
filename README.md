# AgentTect Public Course Notebooks & Student Labs
## 现代 AI 与 Agent 系统 · 学生实验与在线 Notebook 分发仓库

[![Course Site](https://img.shields.io/badge/Course%20Site-academy.viewatom.com-blue?style=for-the-badge)](https://academy.viewatom.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

本仓库是「现代 AI 与 Agent 系统」（AgentTect）课程的**官方公开学生代码与 Notebook 分发仓库**。学生可通过点击下表中的 **Open in Colab** 官方彩色徽标，一键在 Google Colab 云端打开交互式实验环境，直接运行带单元测试与自测打分器的课程作业。

---

## 📚 课程作业与云端实验室一览表 (Syllabus & Colab Direct Links)

| 课次 | 核心主题 | 学生实验 Notebook (点击直接打开) | 独立离线包 / Starter Pack |
| :---: | :--- | :--- | :---: |
| **01** | Agent 运行时与基础循环 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TardisBooo/agenttect-notebooks/blob/main/notebooks/student/lessons/01_agent_runtime.ipynb) | 内置 |
| **02** | 上下文管理、记忆与 RAG | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TardisBooo/agenttect-notebooks/blob/main/notebooks/student/lessons/02_context_memory_rag.ipynb) | 内置 |
| **03** | 推理规划与深度研究 Agent | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TardisBooo/agenttect-notebooks/blob/main/notebooks/student/lessons/03_reasoning_research_agent.ipynb) | 内置 |
| **3.5** | Agent 第一性原理与综合系统实验 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TardisBooo/agenttect-notebooks/blob/main/notebooks/student/lessons/03_5_agent_rag_research_synthesis.ipynb) | 内置 |
| **04** | 数字环境与 Coding Agent 快照 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TardisBooo/agenttect-notebooks/blob/main/notebooks/student/lessons/04_digital_environments_code_agent.ipynb) | [ZIP](starter_packs/lesson_04_starter.zip) |
| **05** | 工作流编排、路由、并行与技能门禁 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TardisBooo/agenttect-notebooks/blob/main/notebooks/student/lessons/lesson_05_workflow_skills.ipynb) | [ZIP](starter_packs/lesson_05_starter.zip) |
| **06** | 持久化状态机与断点恢复图 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TardisBooo/agenttect-notebooks/blob/main/notebooks/student/lessons/lesson_06_durable_state_graph.ipynb) | [ZIP](starter_packs/lesson_06_starter.zip) |
| **07** | 上下文持久化与记忆回放梦境 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TardisBooo/agenttect-notebooks/blob/main/notebooks/student/lessons/lesson_07_context_memory_dreaming.ipynb) | 内置 |
| **08** | 高性能多 Agent 协作网络与工具调用 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TardisBooo/agenttect-notebooks/blob/main/notebooks/student/lessons/lesson_08_multi_agent_collaboration.ipynb) | [ZIP](starter_packs/lesson_08_starter.zip) |
| **09** | 架构实战：权限门禁与执行手册演进 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TardisBooo/agenttect-notebooks/blob/main/notebooks/student/lessons/lesson_09_multi_agent_permissions_playbook.ipynb) | 内置 |
| **10** | 专用语言 (DSL) 与机器人动作安全校验 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TardisBooo/agenttect-notebooks/blob/main/notebooks/student/lessons/10_robot_safety.ipynb) | 内置 |
| **11** | 企业级事务与可靠状态一致性 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TardisBooo/agenttect-notebooks/blob/main/notebooks/student/lessons/11_enterprise_transactions.ipynb) | [ZIP](starter_packs/lesson_11_starter.zip) |
| **12** | 商业服务运维与 Token 效率精细化压榨 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TardisBooo/agenttect-notebooks/blob/main/notebooks/student/lessons/12_australian_service_ops.ipynb) | 内置 |
| **13** | 现代高可靠 Agent 系统的评测、发布与护栏 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TardisBooo/agenttect-notebooks/blob/main/notebooks/student/lessons/13_evaluation_release.ipynb) | 内置 |

---

## 🛠️ 本地运行指南 (Run Locally)

如果你偏好在本地通过 VSCode 或 JupyterLab 运行，可克隆本仓库：

```bash
git clone https://github.com/TardisBooo/agenttect-notebooks.git
cd agenttect-notebooks
pip install jupyterlab pytest
jupyter lab
```
