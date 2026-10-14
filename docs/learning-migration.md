# Learning 名称与先修入口迁移

本切片基于 `98f7a319e7f40fe7557a55d4423e82a03e1d4fd1`。当前展示名称统一为 Robot Learning，仓库地址为 `huangkiki/robot-learning`，物理引擎系列入口改为 `huangkiki/sim-learning`。中英文首页同时加入 Physics-Based Simulation 的总仓伴读入口。

本次只修改品牌、导航和文档交付约定；上游源码 pin、课程示例和既有证据保持不变。维护者已取消默认 Obsidian 归档/同步，因此工程入口改为仅明确要求时执行。E5 原生运行与短训练、E6 未完成部分继续保留原状态。

验证沿用本仓 `scripts/check_docs.py`、`compileall`、`learning/examples/rollout_math.py` 和 `git diff --check`。标量 GAE 示例执行属于课程数学检查，不能记作原生仿真或策略训练。

关联 [Sim Learning 迁移任务](https://github.com/huangkiki/sim-learning/issues/1)。新教材伴读链接依赖总仓对应内容合入；本地检查与实际 PR/CI/合入状态分别报告。

## English summary

Current branding and links now use Robot Learning and Sim Learning. Both homepages link to the prerequisite Physics-Based Simulation study route. Source pins, native examples and previous evidence are unchanged. Deferred native execution and remaining course work are not resumed by this rename.
