# xianyu-check — 闲鱼交易对手识别

双向验人 skill：验卖家（我要买）+ 验买家（我要卖），免登录读取闲鱼/goofish 个人主页，按品类画像、上架节奏（item ID 跨度）、信用徽章、评价比值、行为话术判定风险，输出 emoji 分级报告（🟢/🟡/🔴）。

## 安装

ZCode / Claude Code 类 agent：

```bash
# 用户级安装（所有项目可用）
git clone <本仓库> && cp -r xianyu-check ~/.zcode/skills/
# 或项目级
cp -r xianyu-check <项目>/.zcode/skills/
```

依赖：browser-use（内建浏览器）技能；无浏览器环境时自动退化为规则清单自查模式。

## 使用

```
/xianyu-check <闲鱼分享链接>
```

详见 [xianyu-check/SKILL.md](xianyu-check/SKILL.md)。
