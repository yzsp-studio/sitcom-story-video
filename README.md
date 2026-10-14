<div align="center">

# 🎬 sitcom-story-video

## 一个梗概变情景喜剧，同一镜头最多拍 3 次
## One pitch to AI sitcom, capped at three takes per shot

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

把梗概、剧本、分镜或参考素材转成短篇影视化 AI 情景喜剧。流程在镜头之间保持角色身份、场景地理、道具、光线、轴线和喜剧因果一致，交付故事圣经、剪辑图、生成提示词包与质量检查建议，可直接用于图生视频或文生视频。内置统一的预算与授权台账：失败分为执行失败、内容失败、音频/混音失败三类，各自走不同的修复路径，超时或状态未知不算生成失败。同一镜头同一问题最多 3 次实际生成尝试（含首轮），换模型、改规格、拆镜都不能清零。

### ✨ 能做什么

- 输入一句梗概/剧本/分镜/参考素材 → 输出镜头级生成提示词包
- 故事圣经 + 剪辑图锁定角色身份、场景地理、道具、光线与轴线
- 按喜剧节拍与因果链检查每场戏
- 失败三分类（执行/内容/音频混音），各自只做最小修复
- 统一预算台账：首次生成、重试、修内容、低规格测试都计入额度
- 同一镜头同一问题上限 3 次生成，达上限即停止并交接待审版本

### 📦 包含的技能

- `sitcom-story-video` —— 见 [`sitcom-story-video/SKILL.md`](sitcom-story-video/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/sitcom-story-video.git
cp -r sitcom-story-video/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

Turns a logline, script, storyboard or reference material into a short cinematic AI sitcom. The flow holds character identity, scene geography, props, lighting, axis and comedic causality consistent across shots, delivering a story bible, an edit map, a generation prompt pack and quality-check advice usable for image-to-video or text-to-video. A single budget and authorization ledger is enforced: failures split into execution, content and audio/mix classes with different repair paths, while a timeout or unknown status is not treated as a generation failure. The same issue on the same shot gets at most three real generation attempts including the first, and swapping models, changing specs or splitting shots does not reset that count.

### ✨ What it does

- A one-line logline, script, storyboard or reference in, a shot-level generation prompt pack out
- Story bible plus edit map locking character identity, scene geography, props, lighting and axis
- Comedy beats and causal chain checked for every scene
- Three failure classes (execution, content, audio/mix) each repaired minimally
- One shared budget ledger covering first generations, retries, content fixes and low-spec tests
- Hard cap of three generation attempts for the same issue on the same shot, then stop and hand over a clearly marked pending version

### 📦 Skills included

- `sitcom-story-video` — [`sitcom-story-video/SKILL.md`](sitcom-story-video/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/sitcom-story-video.git
cp -r sitcom-story-video/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
