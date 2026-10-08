# 海外留学生入台证 Skill

供 AI 助手协助**持中国大陆身份、在海外或港澳留学**的人准备赴台观光的单次入出境证或一年多次入出境证。其他国籍、赴台就学、工作等流程不在范围内。必须明确输入 `$taiwan-overseas-student-entry-permit` 才启动。

它会先说明要准备的材料、需要提供的信息以及登录、验证码、法律声明、提交审核等用户要做的动作；随后核对移民署总则和申请人所在地驻外馆处的现行规则，整理私密材料、核对表单与附件，交给用户审阅。**未获这一次申请的明确批准，不会最终送件。** 送件后也只在读到官方回执时报告“已提交”，不把受理等同获批。

这是工作流程辅助，不保证资格或获批。申请人的真实资料、证件扫描件、照片、验证码及审查意见应保存在申请人自己的私密目录，绝不放入本公开仓库或 Issue。官方规则以执行时的[移民署须知](https://www.immigration.gov.tw/5382/5385/7244/7250/7257/7266/36084/)和负责的驻外馆处公告为准。

## 文件

- [`SKILL.md`](SKILL.md)：入口、启动告知、工作流程和提交门槛。
- [`references/eligibility-and-sources.md`](references/eligibility-and-sources.md)：官方来源及资格预检。
- [`references/materials-and-form-map.md`](references/materials-and-form-map.md)：私密材料结构、资料核对和字段映射。
- [`agents/openai.yaml`](agents/openai.yaml)：界面说明及仅显式调用设置。

将整个目录放到支持 Skill 的个人安装位置（例如 Codex 的 `~/.codex/skills/`）后，使用上面的显式调用语句。目录中不要添加个人案件材料。
