# dsh-demo
DSH（DeepSeek Harness）多Agent框架演示项目

## 项目介绍
这是一个串行多智能体示例，一共3个Agent分工协作：
1. collector：资料搜集员，收集信息、整理要点
2. writer：文稿撰写员，根据要点组织成文
3. checker：校验审核员，检查内容、修正错误

执行顺序：collector → writer → checker

## 文件说明
- agent-demo.json：多Agent配置文件，可在DSH框架本地加载运行

## 名词说明
- Agent：智能体，承担单独任务角色
- 框架：调度各个Agent、控制执行流程
- 本地部署：代码跑在自己电脑上，不是云端
- 沙箱：安全隔离环境，防止代码乱操作
- 插件：给框架增加搜索、读写文件等能力
