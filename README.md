<div align="center">

# Academic-DDL

跨学科学术会议、期刊专刊、基金申请与科研项目截止日追踪。

[![GitHub Pages](https://img.shields.io/badge/Pages-live-F43F5E?style=for-the-badge)](https://just-agent.github.io/academic-ddl/)
[![Just-DDL](https://img.shields.io/badge/Just--DDL-network-101626?style=for-the-badge)](https://just-agent.github.io/just-ddl/)
[![Status](https://img.shields.io/badge/Demo-completed-059669?style=for-the-badge)](https://just-agent.github.io/academic-ddl/)

[专题页面](https://just-agent.github.io/academic-ddl/) · [Just-DDL Hub](https://just-agent.github.io/just-ddl/#/topic/academic-ddl) · [GitHub 仓库](https://github.com/Just-Agent/academic-ddl)

</div>

## Demo 已完善

这个仓库不再只是空 Pages 骨架。当前已经包含完整 demo DDL 列表、搜索筛选、状态统计、来源说明和统一 Just-DDL Network 导航。数据风格参考 AllConfs 的会议列表结构，以及 SinoConf 的国内会议/预告/回顾入口。

## Demo DDL Seed

| DDL | 阶段 | 截止日 | 地点 | 来源类型 |
| --- | --- | --- | --- | --- |
| NeurIPS 2026 Full Paper | Paper | 2026-05-28 | Online | AllConfs-style seed |
| ICML 2027 Abstract | Abstract | 2027-01-23 | Online | Demo seed |
| ICLR 2027 Submission | OpenReview | 2026-10-01 | Online | OpenReview-style seed |
| AAAI 2027 Abstract | Abstract | 2026-08-12 | Online | Demo seed |
| KDD 2027 Research Track | Research | 2027-02-04 | Online | Demo seed |
| SIGIR 2027 Full Paper | Paper | 2027-01-30 | Online | Demo seed |
| CHI 2027 Papers | Paper | 2026-09-18 | Online | Demo seed |
| Global AI Summer School Application | Application | 2026-06-30 | Hybrid | AllConfs-style seed |

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