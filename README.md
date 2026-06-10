# SimJiang

SimJiang 是一款完全免费的 SIM / eSIM 号码资产管理与保号提醒 Android 工具。

## 功能

- SIM / eSIM 号码记录管理
- 国家/区号/运营商信息
- 到期日期与保号周期管理
- 本地通知提醒
- Telegram / SMTP 邮件提醒
- 云端提醒服务：多用户 API Key、按 Key 隔离数据、服务器定时检查到期
- 自动同步：新增、编辑、删除、保号、导入和提醒配置变更后自动同步
- 刷流量真实下载测试
- JSON/CSV 数据导入导出
- 深浅色与自定义背景
- 多语言界面：简体中文、繁体中文、English、日本語、阿拉伯语

## 云端提醒

App 默认使用云端地址：

```text
https://ccs.ziranaa.top:16670
```

服务端源码在：

```text
server/simjiang-reminder/
```

## TG 频道

https://t.me/simjiangAPP

## 构建

```bash
gradle assembleDebug --no-daemon --max-workers=1
```
