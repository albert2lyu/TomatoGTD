﻿## 我想写好这个APP
### 2013/09/27 
删除了数据库操作之外的所有实现代码，重写程序，
使用MVC模式，从根本上降低代码之间的耦合度。
耦合度高的代码严重限制了进一步的思考。


### 2013/09/16 更新
1. 删除与番茄计时器相关的代码
2. 添加了基本的数据库操作(添加待办事项，查询待办事项)

### 2013/09/14 更新
1. 进一步抽象番茄计时器类

### 2013/09/11 更新
1. 为番茄钟添加运行时音效(tic ta tic ta ~)

### 2013/09/10 更新
1. 添加删除番茄钟按钮，并设置对应响应事件，完善番茄计时器逻辑
2. 使用观察者模式重新实现了番茄计时器的逻辑，降低代码的耦合度
3. 实现 当番茄钟启动时，页面禁止滑动效果

### 2013/09/09 更新
1. 待办卡片添加中断显示
2. 番茄钟计时效果，使用[AppMsg](https://github.com/johnkil/Android-AppMsg)提示框展示
3. 番茄钟启动时候，屏幕常亮
        

### 2013/09/08 更新
1. 今日待办页面添加“开启番茄钟”、标记“内部中断”、标记“外部中断”按钮
2. 修复显示第二排预估番茄钟数个数的圆圈 控件时，程序一场退出的问题

### 2013/09/07 更新
1. 为待办卡片方式添加 代表预估番茄钟个数的方格 控件
2. 修复应用从后台恢复，应用从锁屏状态恢复时，卡片背景颜色改变的问题

### 2013/09/06 更新
1. 将每个待办以卡片方式呈现，界面模仿“听会早新闻”APP，使用ViewPager实现基本效果
2. 使用[Android-ViewPagerIndicator](https://github.com/JakeWharton/Android-ViewPagerIndicator)添加分页指示器
        
