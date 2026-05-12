# Awesome Newmax Skills

> 牛马AI 官方与社区共建的技能仓库。本仓库存放所有通过牛马 AI 客户端发布的 Skill 内容，每个目录对应一个独立的 Skill。

## 这里有什么

```
skills/
  <category>/
    <skillKey>/
      SKILL.md
      references/
      scripts/
      meta.json
```

- 全部内容由牛马 AI 客户端"发布"按钮经由 niuma-web 服务端推送到这里，**禁止直接提 PR**
- `manifest.json` 由服务端自动重算生成，请勿手工修改
- 客户端通过 `raw.githubusercontent.com` 直接拉取，公开免认证

## Category 一览

`documentation` · `image` · `video` · `audio` · `lark` · `slack` · `social` · `ai-tools` · `dev-tools` · `productivity` · `design` · `other`

## 想发布自己的 Skill？

打开牛马 AI 客户端 → 牛马棚 → "上传/发布"，按界面引导操作。客户端会本地查杀通过后由服务端再扫一道，通过即自动推送至本仓。

## 想下架 / 投诉某个 Skill？

请通过牛马 AI 官网联系运营，由 admin 操作软下架。仓内文件保留作为审计快照。

---

详细架构：见 newmax-client 仓 `docs/architecture/skill-marketplace-git.md`
