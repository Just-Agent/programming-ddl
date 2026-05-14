<div align="center">

# Programming-DDL

编程竞赛、算法训练营与开发者挑战截止日追踪。

Just-DDL Network 的独立专题仓库。当前先提供统一 README、GitHub Pages 骨架和后续 Actions 接入位置，后续再补充真实数据源、爬虫和小程序页面。

[![GitHub Pages](https://img.shields.io/badge/Pages-live-3B82F6?style=for-the-badge)](https://just-agent.github.io/programming-ddl/)
[![Network](https://img.shields.io/badge/Just--DDL-network-101626?style=for-the-badge)](https://just-agent.github.io/just-ddl/)
[![Status](https://img.shields.io/badge/Status-topic%20scaffold-64748B?style=for-the-badge)](https://github.com/Just-Agent/programming-ddl)

[专题页面](https://just-agent.github.io/programming-ddl/) · [Just-DDL 总入口](https://just-agent.github.io/just-ddl/) · [GitHub 仓库](https://github.com/Just-Agent/programming-ddl) · [提交数据](https://github.com/Just-Agent/programming-ddl/issues)

</div>

## 项目定位

Programming-DDL 负责 ICPC / Codeforces / AtCoder / LeetCode / 蓝桥杯等编程赛事、训练营和开发者挑战 deadline。它会作为独立仓库维护，拥有自己的 Pages 页面、数据 schema、Actions 更新流程和未来小程序专题入口。

## 产品入口

| 入口 | 地址 | 用途 |
| --- | --- | --- |
| GitHub Pages | https://just-agent.github.io/programming-ddl/ | 专题独立页面 |
| Just-DDL Hub | https://just-agent.github.io/just-ddl/ | 全部 DDL 专题总入口 |
| Repository | https://github.com/Just-Agent/programming-ddl | 代码、数据、工作流与贡献入口 |
| Issues | https://github.com/Just-Agent/programming-ddl/issues | 补充截止日、修正链接、申请数据源 |

## Just-DDL Network

| 专题 | 仓库 | Pages | 阶段 |
| --- | --- | --- | --- |
| Hackathon-DDL | [Just-Agent/hackathon-ddl](https://github.com/Just-Agent/hackathon-ddl) | [访问](https://just-agent.github.io/hackathon-ddl/) | 已发布 |
| Agent-DDL | [Just-Agent/agent-ddl](https://github.com/Just-Agent/agent-ddl) | [访问](https://just-agent.github.io/agent-ddl/) | 已发布 |
| Just-DDL Hub | [Just-Agent/just-ddl](https://github.com/Just-Agent/just-ddl) | [访问](https://just-agent.github.io/just-ddl/) | 已发布 |
| Programming-DDL | [Just-Agent/programming-ddl](https://github.com/Just-Agent/programming-ddl) | [访问](https://just-agent.github.io/programming-ddl/) | 专题骨架 |

## 收录范围

| 类别 | 示例 | 当前处理方式 |
| --- | --- | --- |
| 算法竞赛 | ICPC / AtCoder / Codeforces | 维护报名、比赛、区域赛节点 |
| 平台赛 | LeetCode / Kaggle code / HackerRank | 记录赛程和排行榜冻结时间 |
| 训练营 | summer camp / bootcamp / course | 记录报名与作品提交截止 |

## 部署与自动化

| 模块 | 当前状态 | 后续动作 |
| --- | --- | --- |
| README | 已统一 Just-DDL Network 风格 | 持续补充真实数据说明 |
| GitHub Pages | 已提供静态专题页骨架 | 后续替换为专题应用或数据看板 |
| deploy-pages workflow | 已加入 GitHub Actions | push main 和手动触发均可发布 |
| 数据抓取 workflow | 待接入 | 按专题数据源独立设计 |
| 小程序专题页 | 待接入 | 复用同一专题 schema |

## 数据 schema 草案

| 字段 | 含义 |
| --- | --- |
| id | 稳定唯一 ID |
| title | 截止日标题 |
| source | 官方来源或平台 |
| url | 官方链接 |
| deadline | ISO 8601 截止时间 |
| timezone | 原始时区 |
| tags | 主题、会议、平台或类型标签 |
| status | upcoming / active / ended |

## 路线图

| 阶段 | 事项 | 状态 |
| --- | --- | --- |
| 1 | 创建独立仓库、README、Pages 骨架 | 完成 |
| 2 | 接入 Just-DDL Hub 专题卡片和详情页 | 完成 |
| 3 | 梳理真实数据源和字段 schema | 计划中 |
| 4 | 增加独立 Actions 抓取与校验 | 计划中 |
| 5 | 输出微信小程序专题页数据 | 计划中 |

## 贡献

欢迎用 Issue 提供新的截止日来源。请尽量附上官网、截止时间、时区、所属分类、是否有报名与提交两个阶段。

## License

当前仓库处于产品孵化阶段。正式开源协议会在发布稳定版本前补齐。