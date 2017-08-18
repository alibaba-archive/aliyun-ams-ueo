# iOS Xcode Objective-C Code Snippets

## 使用说明

- 适用于Objective-C编程。

### 导入

将`snippets/`目录下的`*.codesnippet`拷贝到Xcode Code Snippets管理目录：`~/Library/Developer/Xcode/UserData/CodeSnippets`。

```
cp ~/snippets/*.codesnippet ~/Library/Developer/Xcode/UserData/CodeSnippets/
```

### 删除

推送每条snippet里都有`Feedback`关键字，执行下面脚本将推送相关snippet删除。

```
grep -l "Feedback" ~/Library/Developer/Xcode/UserData/CodeSnippets/* | xargs rm
```

### 使用示例

![](assets/feedback_introduce.gif)

## Snippets说明


Snippet说明 | Shortcut
--- | ---
Feedback SDK 初始化 | `feedback_init`
Feedback SDK 打开调试日志 | `feedback_log`
打开反馈模板       | `feedback-open`
获取未读消息数模板 | ``
设置默认联系方式模板   | ``


