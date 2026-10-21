# wechat-miniprogram-ui-gen

微信小程序 UI 设计 Skill。提取参考截图或项目源码的 UI 风格，生成配套背景图，先出 HTML 前端预览供你确认，再输出微信小程序原生 WXML+WXSS 和完整设计文档。

## 安装

需要先安装 Node.js（自带 npx）。

```bash
npx skills add tengyijie/wechat-miniprogram-ui-gen
```

安装到指定 agent：

```bash
npx skills add tengyijie/wechat-miniprogram-ui-gen -a cursor -a claude-code
```

全局安装：

```bash
npx skills add tengyijie/wechat-miniprogram-ui-gen -g -a cursor -a claude-code
```

## 怎么用

安装后，在 Cursor、Claude Code 等 agent 里直接说：

- “帮我做一个小程序 UI，风格是清新国风”

- “参考这几张截图，复刻这个小程序界面”

- “这是我的小程序源码，帮我优化界面，不要改功能”

## 文件结构

```text
skills/
└── wechat-miniprogram-ui-gen/
    └── SKILL.md
```

## License

MIT
