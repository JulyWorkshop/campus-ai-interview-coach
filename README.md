# 校招AI面试陪跑教练（WorkBuddy Skill）

版本：1.0.0

## 功能
根据应届生简历和目标岗位JD开展岗位定制模拟AI面试，默认每轮8题、一次一题；整轮结束后按五维权重评分，提供逐题复盘、真实经历基础上的答案优化、多轮薄弱项复测，并以95分作为训练目标。

## 文件结构
- `SKILL.md`：主指令与工作流
- `references/source-methods.md`：17张《2027届秋招AI面试指导》PPT方法摘要
- `references/scoring-rubric.md`：五维评分、权重、评分锚点和风险调整
- `references/interview-frameworks.md`：STAR、PREP、PAR等答题框架
- `references/question-bank.md`：题型与自适应出题规则
- `references/report-template.md`：整轮报告和训练记录
- `references/qa-checklist.md`：验收用例

## 导入WorkBuddy
1. 打开 WorkBuddy 的「专家·技能·连接器」区域，进入「技能」。
2. 选择「添加技能」→「上传技能」。
3. 上传本压缩包；如平台要求 ZIP 根目录直接包含 `SKILL.md`，本包已按该形式组织。
4. 安装后在对话中调用“校招AI面试陪跑教练”，或使用“根据我的简历和JD开始模拟面试”等表达。
5. 首次测试建议使用脱敏简历和公开JD，检查技能是否能读取附件并一次只问一道题。

## 建议验收
先用测试简历与JD完成一轮；核查题目是否岗位相关、评分是否能对应具体证据、示范答案是否没有虚构经历、未达95分时是否能给出下一轮计划。

## 能力边界
本Skill主要依靠当前对话中的简历、JD和回答进行推理。它不会自动知道企业的私有AI评分算法，也不能仅凭文字判断眼神、表情、真实语速或设备状态。95分是本Skill内部的模拟训练目标，不是企业通过保证。
