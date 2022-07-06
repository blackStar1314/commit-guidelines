# commit-guidelines

## 标准化提交信息
### 格式
```
<type>[optional (<scope>)]: <subject>
<!-- BLANK LINE -->
[optional <body>]
<!-- BLANK LINE -->
[optional <footer>]
```

### 字段详情
|字段|必须|说明|
|:--|:--:|:--|
|type|是|提交类型，描述本次提交上下文|
|scope|否|提交类型影响的范围|
|subject|是|提交摘要|
|body|否|提交摘要附加信息描述|
|footer|否|一般描述重大更改的信息|

### type
|类型|说明|
|:--|:--|
|build|更改产品的构建系统或外部依赖项(添加，删除或升级依赖项)|
|change|现有功能的修改|
|chore|类似build|
|ci|对持续集成或持续交付脚本或配置文件的修改|
|deprecate|弃用现有功能，但是不从产品中删除改功能|
|docs|添加，修改，删除文档|
|feat|新增功能|
|fix|bug修复|
|perf|性能优化|
|refactor|非bug修复和新增功能的代码修改|
|remove|从产品中删除该功能|
|revert|版本回退，携带回退的提交ID|
|style|代码格式修改，不影响代码|
|test|添加或修改测试用例|

### type简化
|类型|说明|
|:--|:--|
|feat|新增|
|change|修改|
|deprecate|弃用|
|remove|移除|
|fix|修复|
|revert|回滚|
|test|测试|
|style|格式|
|docs|文档|






