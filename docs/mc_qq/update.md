# 更新记录

此处不再记录，请前往 [Releases](https://github.com/17TheWord/nonebot-plugin-mcqq/releases/) 查看

## 2022 / 9 / 3

- MC Server 端
  - 插件端
    - 新增 `玩家死亡事件` 推送
  - 非插件端
    - 死亡信息类型较多，暂无 `玩家死亡事件` 事件推送

## 2022 / 8 / 31

- NoneBot 端
    - 新增 `MCRcon` 版本
        - 部分特殊消息可在游戏中单击跳转到浏览器查看
    - 新增 `非插件端` 版本
        - 部分特殊消息可在游戏中单击跳转到浏览器查看

## 2022 / 8 / 8

- 插件更名为 `MC_QQ`
- NoneBot 端
    - 新增 `pip` 安装方式
    - 频道适配补丁已添加到插件依赖中，无需手动安装

## 2022 / 8 / 4

- NoneBot 端
    - 增加 `群 回复` 消息处理方式
    - 更改 `群 @ 消息` 处理方式

## 2022 / 8 / 3

- NoneBot 端
    - `群 @ 消息` 简单处理

## 2022 / 7 / 31

- NoneBot 端
    - 半支持特殊消息，如 `@`、`[图片]`、 `[视频]`、等等
- MC Server 端
    - 自定义 插件是否启用
    - 自定义 `WebSocket` 服务端地址
    - 自定义 `WebSocket` 服务端端口
    - 自定义 发言修饰，如：`17TheWord 说：` 中的 `说：`

## 2022 / 7 / 30

- NoneBot 端
    - 自定义 `WebSocket` 客户端端口
    - 自定义 `群号`、`频道ID`—`子频道ID`

- MC Server 端
    - 自定义启用 `加入 / 离开` 服务器事件推送

## 2022 / 7 / 29

实现 `群`、`频道` 与 `MC Server` 消息互通

- MC Server 端
    - 自定义 `WebSocket` 服务端端口