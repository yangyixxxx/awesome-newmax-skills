# 贡献指南

本仓库**不接受直接 PR**。所有内容由牛马 AI 客户端经服务端审核后自动推送。

## 想发布 Skill

1. 安装牛马 AI 桌面客户端
2. 打开 牛马棚 → 上传/发布
3. 按界面引导填写 displayName / description / category / version 等元数据
4. 客户端会本机用 [`@yangyixxxx/skill-guard`](https://github.com/yangyixxxx/skillguard) 静态查杀
5. 通过后由 niuma-web 服务端二次扫描兜底
6. 双侧通过即自动 commit 到本仓 `skills/<category>/<skillKey>/`

## 想修复某个已发布的 Skill

在客户端"我的牛马"页找到对应条目，点"重新提交"。**禁止**手工改本仓文件——下次发布会被服务端覆盖。

## 安全策略

- **永远不要**在 SKILL.md / scripts / references 里放真实 API key、私钥、token、个人信息
- 任何外网请求必须在 SKILL.md 里说明用途
- 违规内容由 admin 软下架（manifest 层过滤，仓内文件保留作审计）

## 报告问题

技能内容问题：通过牛马 AI 官网客服反馈
仓库基建问题：在 newmax-client 仓提 Issue
