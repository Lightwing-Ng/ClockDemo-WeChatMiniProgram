# ClockDemo-WeChatMiniProgram
## 说明
```
    时钟演示
```
## 文件结构
```
.
├── .DS_Store
├── .git
│   ├── HEAD
│   ├── branches
│   ├── config
│   ├── description
│   ├── hooks
│   │   ├── applypatch-msg.sample
│   │   ├── commit-msg.sample
│   │   ├── fsmonitor-watchman.sample
│   │   ├── post-update.sample
│   │   ├── pre-applypatch.sample
│   │   ├── pre-commit.sample
│   │   ├── pre-push.sample
│   │   ├── pre-rebase.sample
│   │   ├── pre-receive.sample
│   │   ├── prepare-commit-msg.sample
│   │   └── update.sample
│   ├── index
│   ├── info
│   │   └── exclude
│   ├── objects
│   │   ├── b9
│   │   │   └── eef6a2aeb03f4313e57731c8c1cf0a848134e4
│   │   ├── info
│   │   └── pack
│   └── refs
│       ├── heads
│       └── tags
├── README.md               # 本文档
├── app.js                  # 主文档
├── app.json
├── app.wxss
├── pages
│   ├── index
│   │   ├── .DS_Store
│   │   ├── index.js
│   │   ├── index.wxml
│   │   └── index.wxss
│   ├── index.js            # 主页
│   ├── index.json
│   ├── index.wxml
│   ├── index.wxss
│   └── logs
│       ├── logs.js
│       ├── logs.json
│       ├── logs.wxml
│       └── logs.wxss
├── project.config.json
└── utils
    └── util.js
```
## 逻辑
```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```
## 运行