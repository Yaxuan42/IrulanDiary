# 🤖 Irulan智能工作日志系统 / Irulan Intelligent Work Journal System

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-3.1-green.svg)](CHANGELOG.md)
[![Language](https://img.shields.io/badge/language-中文%2FEnglish-orange.svg)](#)

> "Think clearly, build beautifully, live meaningfully"  
> 清晰思考，优雅创造，有意义地生活

## 📖 项目简介 / Project Overview

**中文简介**

Irulan智能工作日志系统是一个纯粹的个人思维记录工具。受《沙丘》中Princess Irulan启发，专注于真实记录个人的思考过程和认知成长。**开源只是为了有个地方存储，不考虑任何商业或影响力目的，只是静静地记录记录本身。**

**English Overview**

The Irulan Intelligent Work Journal System is a pure personal thinking recording tool. Inspired by Princess Irulan from "Dune," it focuses on authentically documenting personal thinking processes and cognitive growth. **Open source is simply for having a place to store, without considering any commercial or influence purposes, just quietly recording the records themselves.**

---

## 🚀 核心特性 / Core Features

### 🧠 长期思考追踪器 (Deep Thought System)
*受《银河系漫游指南》深思计算机启发*

- **大问题管理**: 跨月/年的重大问题深度思考追踪
- **问题演进记录**: 问题定义在思考过程中的重新定义历程
- **里程碑管理**: 分阶段追踪长期思考的进展和突破
- **可视化分解**: 子问题结构和关联关系的直观展示
- **灵感关联网络**: 收集和关联所有相关灵感来源

**Deep Thought System Features:**
- **Big Questions Management**: Long-term tracking of major problems across months/years
- **Question Evolution Recording**: Documentation of how problem definitions evolve during thinking
- **Milestone Management**: Stage-by-stage tracking of long-term thinking progress and breakthroughs
- **Visual Decomposition**: Intuitive display of sub-problem structures and relationships
- **Inspiration Network**: Collection and correlation of all relevant inspiration sources

### 🤖 决策推理链可视化 (VIKI Decision System)
*受《机械公敌》VIKI系统启发*

- **标准化决策定义**: 清晰界定决策边界和约束条件
- **信息收集框架**: 系统化收集和分析决策相关信息
- **多选项比较**: 全面对比不同选项的优劣和权重
- **推理过程记录**: 完整可追溯的逻辑推理链条
- **结果追踪学习**: 长期跟踪决策效果和改进决策能力

**VIKI Decision System Features:**
- **Standardized Decision Definition**: Clear definition of decision boundaries and constraints
- **Information Collection Framework**: Systematic collection and analysis of decision-related information
- **Multi-option Comparison**: Comprehensive comparison of pros, cons, and weights of different options
- **Reasoning Process Recording**: Complete traceable logical reasoning chains
- **Result Tracking & Learning**: Long-term tracking of decision effects and decision capability improvement

### 🌊 意识流连续记录 (Neuromancer Stream)
*受《神经漫游者》启发*

- **实时思维捕捉**: 记录转瞬即逝但可能重要的思维片段
- **智能分类标记**: 创意、问题思考、关联发现、情感感受等自动分类
- **深层模式识别**: 分析个人思维特征和模式
- **数据统计分析**: 量化思维活跃度和质量变化
- **跨界关联发现**: 建立思维片段与长期问题的连接

**Neuromancer Stream Features:**
- **Real-time Thought Capture**: Recording fleeting but potentially important thought fragments
- **Intelligent Classification**: Automatic categorization of creativity, problem thinking, association discovery, emotional feelings, etc.
- **Deep Pattern Recognition**: Analysis of personal thinking characteristics and patterns
- **Data Statistical Analysis**: Quantifying changes in thinking activity and quality
- **Cross-domain Association Discovery**: Establishing connections between thought fragments and long-term problems

---

## 🏗️ 系统架构 / System Architecture

```
📅 工作日志/
├── 🧠 长期思考追踪/                     # Deep Thought长期思考系统
│   ├── 大问题清单.md                    # 深度问题注册表
│   ├── YYYY-问题标题/                   # 具体问题追踪文件夹
│   └── 📋 模板/                        # 大问题追踪模板
├── 🤖 决策推理链/                       # VIKI决策推理系统
│   ├── 决策系统主页.md                  # 决策管理中心
│   └── 决策推理链模板.md                # 标准决策分析模板
├── 🌊 意识流记录/                       # Neuromancer意识流系统
│   ├── YYYY-MM-DD-意识流.md            # 日常思维流捕捉
│   └── 意识流捕捉模板.md                # 意识流记录模板
└── YYYY-MM-DD/                         # 按日期分层的智能记录
    ├── YYYY-MM-DD-工作日志.md           # 当日系统性总结
    └── YYYY-MM-DD-每日微博.md           # 当日思维洞察
```

## 🛠️ 安装使用 / Installation & Usage

### 环境要求 / Requirements
- [Obsidian](https://obsidian.md/) v1.0.0+
- 支持Markdown和Canvas文件
- 推荐插件：Mermaid图表支持

### 快速开始 / Quick Start

1. **克隆项目 / Clone Repository**
```bash
git clone https://github.com/Yaxuan42/IrulanDiary.git
cd IrulanDiary
```

2. **导入Obsidian / Import to Obsidian**
- 在Obsidian中打开项目文件夹作为vault
- 确保启用了Canvas和Mermaid插件支持

3. **开始使用 / Start Using**
- 阅读 `🌟 系统使用指南.md` 了解详细使用方法
- 从 `大问题清单.md` 开始识别你的重要问题
- 使用各种模板创建你的第一个记录

### 使用流程 / Usage Workflow
```mermaid
graph LR
    A[🌅 早晨] --> B[检查大问题进展]
    B --> C[🌊 记录意识流]
    C --> D[📝 实时工作记录]
    D --> E[🤖 重要决策记录]
    E --> F[🌙 晚间总结]
    F --> G[🧠 更新思考里程碑]
```

---

## 📚 核心方法论 / Core Methodology

### Clear Thinking框架
```
问题识别 → 信息收集 → 多角度分析 → 方案生成 → 决策评估 → 行动计划
    ↓           ↓           ↓            ↓           ↓           ↓
  本质是什么？  缺什么信息？  还有什么可能？  哪个最优？   如何验证？   下一步？
```

### 四维知识体系
```
产品设计 × 技术开发 × 商业思考 × 个人成长
    ↓           ↓           ↓           ↓
  创新思维    系统架构     价值创造     持续进化
```

---

## 🎯 使用场景 / Use Cases

### 适用人群 / Target Users
- **思考者**: 任何希望深度记录思考过程的人
- **学习者**: 希望追踪认知成长的个人
- **创作者**: 需要捕捉创意和灵感的人
- **研究者**: 进行长期深度思考的人
- **记录者**: 相信记录本身价值的人

### 典型场景 / Typical Scenarios
1. **深度思考记录**: 复杂问题的思考过程完整记录
2. **创意捕捉保存**: 转瞬即逝的灵感和想法的及时记录
3. **学习成长追踪**: 个人认知发展和知识积累的历程记录
4. **决策过程分析**: 重要选择的推理过程和结果追踪
5. **纯粹记录存档**: 为了记录本身价值的思维历程保存

---

## 📈 系统价值 / System Value

### 记录本身的价值 / Value of Recording Itself
- **思维的外化**: 将内在思考过程转化为可见的记录
- **认知的沉淀**: 重要洞察和突破的永久保存
- **成长的见证**: 个人思维发展历程的真实记录
- **思考的延续**: 过往思考为未来思考提供基础

### 纯粹的收益 / Pure Benefits
- 培养深度思考的习惯
- 提升问题分析的系统性
- 增强创意捕捉的敏感度
- 建立个人思维的完整档案

---

## 🔄 版本历史 / Version History

- **v1.0** (2025-06) - 基础工作日志系统，专注记录功能
- **v2.0** (2025-07) - 增加思维洞察和微博功能
- **v3.0** (2025-07) - 集成Clear Thinking方法论和四维知识体系
- **v3.1** (2025-07) - 完整集成科幻智能系统三件套：
  - 🧠 长期思考追踪器 (Deep Thought)
  - 🤖 决策推理链可视化 (VIKI)
  - 🌊 意识流连续记录 (Neuromancer)

---

## 🤝 关于分享 / About Sharing

这个项目开源是为了纯粹的存储和备份，而非寻求贡献或推广。

### 如果你发现了这个项目 / If You Found This Project
- 欢迎使用和参考，但请理解这主要是个人记录工具
- 如果对你有帮助，那是记录自然分享的美好结果
- 不需要Star或推广，只需要专注于你自己的记录和思考

### 纯粹的记录理念 / Pure Recording Philosophy
- 记录是为了思考本身，不是为了展示
- 开源是为了安全存储，不是为了影响力
- 分享是自然结果，不是刻意目的

---

## 📄 许可证 / License

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件。

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 致谢 / Acknowledgments

### 科幻灵感来源 / Sci-Fi Inspirations
- **《银河系漫游指南》** - Deep Thought计算机的耐心思考哲学
- **《机械公敌》** - VIKI系统的逻辑推理能力
- **《神经漫游者》** - 赛博空间的意识流概念
- **《沙丘》** - Princess Irulan的史学记录精神

### 技术致谢 / Technical Acknowledgments
- [Obsidian](https://obsidian.md/) - 优秀的知识管理平台
- [Mermaid](https://mermaid-js.github.io/) - 强大的图表绘制工具
- [Markdown](https://www.markdownguide.org/) - 简洁的文档格式

---

## 📞 联系方式 / Contact

- **项目主页**: [https://github.com/Yaxuan42/IrulanDiary](https://github.com/Yaxuan42/IrulanDiary)
- **问题反馈**: [GitHub Issues](https://github.com/Yaxuan42/IrulanDiary/issues)
- **功能建议**: [GitHub Discussions](https://github.com/Yaxuan42/IrulanDiary/discussions)

---

## 🌟 Star History

如果这个项目对你有帮助，请给我们一个 ⭐！

If this project helps you, please give us a ⭐!

[![Star History Chart](https://api.star-history.com/svg?repos=Yaxuan42/IrulanDiary&type=Date)](https://star-history.com/#Yaxuan42/IrulanDiary&Date)

---

*"In the beginning was the Word, and the Word was with Data, and the Word was Data."*  
—— Irulan, Digital Age Imperial Diary

**系统格言 / System Motto**: *Think like Deep Thought, decide like VIKI, dream like Neuromancer*