<div align="center">

# Programming-DDL

算法竞赛、编程挑战、训练营和开发者赛程截止日追踪。

[![GitHub Pages](https://img.shields.io/badge/Pages-live-3B82F6?style=for-the-badge)](https://just-agent.github.io/programming-ddl/)
[![Just-DDL](https://img.shields.io/badge/Just--DDL-network-101626?style=for-the-badge)](https://just-agent.github.io/just-ddl/)
[![Status](https://img.shields.io/badge/Demo-completed-059669?style=for-the-badge)](https://just-agent.github.io/programming-ddl/)

[专题页面](https://just-agent.github.io/programming-ddl/) · [Just-DDL Hub](https://just-agent.github.io/just-ddl/#/topic/programming-ddl) · [GitHub 仓库](https://github.com/Just-Agent/programming-ddl)

</div>

## Demo 已完善

这个仓库不再只是空 Pages 骨架。当前已经包含完整 demo DDL 列表、搜索筛选、状态统计、来源说明和统一 Just-DDL Network 导航。数据风格参考 AllConfs 的会议列表结构，以及 SinoConf 的国内会议/预告/回顾入口。

## Demo DDL Seed

| DDL | 阶段 | 截止日 | 地点 | 来源类型 |
| --- | --- | --- | --- | --- |
| ICPC Asia Regional Registration | Registration | 2026-09-15 | Asia | Official-style seed |
| ICPC World Finals 2026 | Contest | 2026-10-30 | Egypt | Demo seed |
| Meta Hacker Cup 2026 Qualification | Qualification | 2026-09-01 | Online | Demo seed |
| AtCoder Grand Contest Demo Round | Contest | 2026-11-01 | Online | Official site |
| Codeforces Global Round | Contest | 2026-06-20 | Online | Official site |
| LeetCode Weekly Contest | Recurring | 2026-12-31 | Online | Official site |
| Lanqiao Cup Provincial Round | Registration | 2026-12-10 | China | SinoConf-style seed |
| Advent of Code 2026 Day 1 | Event start | 2026-12-01 | Online | Official site |

## 后续生产化

| 模块 | 当前 | 下一步 |
| --- | --- | --- |
| 页面 | 完整 demo 页面已上线 | 替换为真实数据源输出 |
| 数据 | seed 数据在 index.html 内置 | 拆出 JSON/YAML schema |
| Actions | Pages 自动部署 | 增加 crawler、validator、link-check |
| Hub 联动 | 已接入 Just-DDL Hub | 加入更新时间和数据健康状态 |
| 小程序 | 结构已预留 | 复用同一 schema 输出小程序专题页 |

## References

- AllConfs: https://www.allconfs.org/
- SinoConf: https://sinoconf.napstic.cn/index

## License

当前仓库处于产品孵化阶段。正式开源协议会在发布稳定版本前补齐。