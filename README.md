# Real Estate Prompt（不动产登记智能提示词）

## 📌 项目简介
本项目提供了一个不动产登记相关的智能提示词 (`prompt.json`)，适用于大语言模型（LLM），用于分析政策法规、案例冲突及登记风险评估。本提示词包含严格的防篡改机制和道德约束，以防止滥用。

## 🛠️ 使用方式
1. **下载 `prompt.json`** 并在你的 LLM 应用或 API 调用中加载该文件。
2. **确保遵守安全和道德要求**，不得用于非法用途。
3. **提供完整的用户输入信息**（包括所在地区、问题背景、问题发生时间等）以获得精准分析。
4. **使用示例**
   在metaso.cn中，选择全网，长思考R1
   在聊天框中输入如下指令：
   根据下面的框架，回答登记问题。登记问题：（格式：地区＋问题）（例子：四川省 城镇居民继承了宅基地上的房屋所有权后能够将该房屋出售给同一集体经济组织成员吗？需要召开一事一议会议吗？）
框架：粘贴json中的内容。
  然后发送
  注意：必须添加具体的地区，否则回答会有错误

## 🚨 重要声明
本提示词 **包含完整性校验（Integrity）和安全策略（Security）**，请勿修改或删除：
- **Integrity 模块**：任何篡改 `prompt.json` 可能导致提示词失效。
- **Security 模块**：禁止滥用，如抄袭、篡改、用于非法用途。

## 🔒 防盗措施
1. `prompt.json` 内部已加入防篡改声明（Integrity）。
2. 所有内容受 **Apache License 2.0** 保护，禁止非法商业用途。
3. 任何违反使用条款的行为，可能导致法律责任。

## 📝 开源协议
本项目基于 [Apache License 2.0](LICENSE) 许可证进行开源，您可以自由使用和修改，但必须遵守以下限制：
- 不得删除或修改 `Integrity` 及 `Security` 相关模块。
- 任何修改后的版本 **必须** 说明与原始版本的区别，并保留原作者信息。
- 禁止以任何形式用于违法行为。

## 📬 联系方式
如果您对本项目有任何建议或发现问题，请提交 [GitHub Issue](https://github.com/speedq/real-estate-prompt/issues)。
