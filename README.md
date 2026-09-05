# 访谈资料分析 Skill

对原始半结构式或深度访谈逐字稿做逐份、可定位的定性分析，覆盖资料审计、个案备忘录、迭代编码、负例检验、解释和引文核验。

## 适合处理

- 访谈材料覆盖、格式、隐私和用途边界审计
- 单份逐字稿的快速个案分析
- 多份逐字稿的系统编码与跨案例比较
- 引文逐字核对、负例分析和有边界的研究结论

本 Skill 不负责转写、普通会议纪要、销售通话摘要、问卷统计，也不会用少量引文估计总体比例。

## 使用

在 Codex 中直接调用：

```text
$interview-analyst-cn 分析这些原始访谈逐字稿，并区分事实、推断、反证和未知。
```

安装到个人 Skill 目录的一种方式：

```bash
git clone https://github.com/fengxinbo558/interview-analyst-cn.git ~/.codex/skills/interview-analyst-cn
```

若目标目录已经存在，请先自行检查，不要直接覆盖。

## 内容

- `SKILL.md`：主入口、模式选择、证据与隐私边界
- `agents/openai.yaml`：中性中文 UI 元数据
- `phases/`：六阶段分析方法
- `evals/`：触发与行为样例

## 验证与来源

本仓库版本已通过结构、安全、链接和隔离安装检查。来源和修改边界见 `UPSTREAM.md`，适用许可证原文见 `LICENSE.upstream`；这些文件属于法律与诚实溯源记录，不应删除。
