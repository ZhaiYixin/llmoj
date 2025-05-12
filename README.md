## 这个软件是什么？

上过编程课程的人肯定都用过OJ，就是一个做编程题的平台。这个软件调用大语言模型的API，把ChatGPT做进OJ里了，可以问它题目的提示或者答案。还有，实现了一个PDF阅读器，方便查阅老师的PPT课件。

## 实际运行效果怎么样？

如果想看演示视频，可以点击下面的图片。

### 学生端：

[![学生端演示视频](https://github.com/ZhaiYixin/llmoj/blob/master/docs/img/student_interface.png?raw=true)](https://www.bilibili.com/video/BV1VkETzkEhh/)

### 教师端：

[![教师端演示视频](https://github.com/ZhaiYixin/llmoj/blob/master/docs/img/teacher_interface.png?raw=true)](https://www.bilibili.com/video/BV15kETzkEwy/)

## 为什么做这个软件？

因为，不做这个，就毕不了业😅。这是一个本科毕设，选题是**基于大模型的Python学习助手的设计与实现**。

## 这个软件有什么用？

没什么用。但是自认为，聊天机器人、OJ系统、PDF阅读器，这三个软件的功能，都是实现得比较好的。至于**基于大模型**的功能有没有用，作为开发者，心里十分清楚🤣。

## 这个软件是如何实现的？

`llmoj-web/`是前端，基于Vue3。`llmoj-api/`是后端，基于Django。软件整体架构如下：

![软件整体架构](https://github.com/ZhaiYixin/llmoj/blob/master/docs/img/software_architecture.png?raw=true)
