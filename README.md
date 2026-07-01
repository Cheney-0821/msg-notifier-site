# 消息通知助手公开下载页

这是"消息通知助手"的公开下载页仓库。

## 用途

- GitHub Pages 静态官网
- 公开 Releases 下载入口
- 自动更新失败时的手动下载兜底

## 公开仓库边界

这个仓库只放公开展示内容。

可以放：

- `index.html`
- `styles.css`
- 无敏感信息的图片资源
- 面向用户的说明文案
- GitHub Releases 中的正式安装包

不能放：

- 主程序源码
- GitHub token
- Authorization header
- 用户反馈数据
- 本地日志
- 开发文档
- 构建中间产物

## 发布约定

Release asset 固定命名：

```text
MsgNotifierSetup.exe
```

官网主下载按钮指向：

```text
https://github.com/Cheney-0821/msg-notifier-site/releases/latest/download/MsgNotifierSetup.exe
```

每次发布新版时，创建新的 Release，并上传同名 asset。
