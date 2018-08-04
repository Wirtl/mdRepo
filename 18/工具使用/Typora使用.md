## 配置

### 配置图片粘贴

在设置 -- 图片插入中将图片设置复制到当前目录

### 自动保存

偏好设置 -- 系统 -- 保存&恢复 -- 自动保存

### 转换为word等格式/其它格式转化为md

安装Pandoc   [download page](https://github.com/jgm/pandoc/releases/latest)

使用  文件 -- 导出



## typora 快捷键

### 设置快捷键

设置 -- 打开高级设置 -- 修改 `conf.user.json` 文件

```js
"keyBinding": {
    // "Always on Top": "Ctrl+Shift+P"
    "Always On Top": "Ctrl+Shift+P",
    "Code Fences": "Ctrl+Shift+C",
    //"Ordered List": "Ctrl+Alt+o",
    //"Unordered List": "Ctrl+Alt+u"
  },
```

- 无序列表：输入-之后输入空格
- 有序列表：输入数字+“.”之后输入空格
- 任务列表：- [ ]空格 文字
- 标题：ctrl+数字
- 表格：ctrl+t
- 生成目录：[TOC]按回车
- 选中一整行：ctrl+l
- 选中单词：ctrl+d
- 选中相同格式的文字：ctrl+e
- 跳转到文章开头：ctrl+home
- 跳转到文章结尾：ctrl+end
- 搜索：ctrl+f
- 替换：ctrl+h
- 引用：输入>之后输入空格
- 加粗：ctrl+b
- 倾斜：ctrl+i
- 下划线：ctrl+u
- 删除线：alt+shift+5
- 插入图片：直接拖动到指定位置即可或者ctrl+shift+i
- 插入链接：ctrl+k