# 誉馨·学习讨论设计

把课程、读书、讲座或录音材料，转化为贴近生活、能引发思考并包含现场练习的短时分享。

## 安装到 Codex

把本仓库链接发给支持 Codex Skills 的 AI，并说：

> 请使用 skill-installer，从 GitHub 仓库 kfyanjun/yuxin-learning-discussion 安装 skill。仓库根目录就是 skill 目录，安装名称用 yuxin-learning-discussion。

对应的安装命令是：

```bash
python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo kfyanjun/yuxin-learning-discussion \
  --path . \
  --name yuxin-learning-discussion
```

安装后，重启或刷新 Codex；之后可在请求中提到“誉馨·学习讨论设计”或使用 `$yuxin-learning-discussion`。

## 其他 AI 工具

能否直接安装取决于对方使用的 AI 是否支持 Skills，以及是否有 GitHub 安装能力。若不支持，可打开仓库里的 [SKILL.md](SKILL.md)，复制内容到该工具支持的自定义指令或技能设置中。

## 文件

- [SKILL.md](SKILL.md)：技能说明与工作流程
- [LICENSE](LICENSE)：MIT License
