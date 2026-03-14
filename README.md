## 目录结构

```bash
├── BiVisualPath               # 大屏设计
├── DocumentFile               # 文档
├── DocumentPreview            # 文档预览
├── EmailFile                  # 邮件附件
├── IMContentFile              # IM聊天附件
├── Language                   # 语言包
├── ReportFile                 # 报表相关资源
├── SystemFile                 # 系统附件
├── TemplateCodeVue3           # 代码生成器模板
│      ├── helper              # 前端调用api接口
│      ├── java                # 后端模板，各表单类型使用同一套模板
│      ├── macro               # 流程表单模板
│      ├── PublicMacro         # 公用宏（通用方法和变量）
│      ├── TemplateCode1       # 发起表单（流程表单）
│      ├── TemplateCode2       # 功能表单（表单列表）
│      ├── TemplateCode3       # 功能流程（表单列表流程）
│      ├── TemplateCode4       # 纯表单
│      ├── TemplateCode5       # 纯表单+流程
│      └── TemplateCode6       # 视图代码生成
├── TemplateFile               # 其他模板文档
├── TemporaryFile              # 临时存放目录
├── UserAvatar                 # 用户头像
└── WebAnnexFile               # 其他

```

## 关联项目

| 项目 | 分支 |  说明 |
| --- | --- | --- |
| jnpf-dotnet  | v6.1.x-stable  | .NET单体后端项目源码 |
| jnpf-dotnet-cloud  | v6.1.x-stable  | .NET微服务后端项目源码 |
| jnpf-java-boot | v6.1.x-stable  | Java单体后端项目源码 |
| jnpf-java-cloud | v6.1.x-stable  | Java微服务后端项目源码 |