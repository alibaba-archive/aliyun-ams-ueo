# 移动推送iOS Xcode Objective-C Code Snippets

## 使用说明

- 适用于Objective-C编程。

### 导入

将`snippets/`目录下的`*.codesnippet`拷贝到Xcode Code Snippets管理目录：`~/Library/Developer/Xcode/UserData/CodeSnippets`。

```
cp ~/snippets/*.codesnippet ~/Library/Developer/Xcode/UserData/CodeSnippets/
```

### 删除

推送每条snippet里都有`移动推送`关键字，执行下面脚本将推送相关snippet删除。

```
grep -l "移动推送" ~/Library/Developer/Xcode/UserData/CodeSnippets/* | xargs rm
```

### 使用示例

![](assets/push-ios-snippets.gif)

## Snippets说明

Snippet说明 | Shortcut
--- | ---
初始化 | `push_init`
打开调试日志 | `push_turnon_log`
获取版本号 | `push_version`
获取通道状态 | `push_channel_status`
获取设备Id | `push_deviceId`
绑定账号 | `push_bind_account`
解绑账号 | `push_unbind_account`
绑定标签 | `push_bind_tag`
解绑标签 | `push_unbind_tag`
查询标签 | `push_list_tag`
添加别名 | `push_add_alias`
删除别名 | `push_remove_alias`
查询别名 | `push_list_alias`
APNs注册并上报deviceToken | `push_register_apns`
获取deviceToken | `push_deviceToken`
推送通道建立监听 | `push_channel_opened`
消息接收监听 | `push_receive_message`
通知处理 | `push_notification_handler`
