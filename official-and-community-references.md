# X 申诉参考资料：官方规则与公开案例

这份文档作为 `x-appeal-checklist` 的补充资料，和 `reddit-appeal-notes.md` 配合使用。

核心原则仍然是：**公开案例用于观察经验，官方规则用于定义问题边界；二者都不能替代对具体账号证据的调查。**

## 一、优先阅读：X 官方 Authenticity 政策

X 当前的 Authenticity 政策是调查 `inauthentic behavior` 时最重要的基准材料之一：

- [X Help：Authenticity](https://help.x.com/en/rules-and-policies/authenticity)

值得特别关注的部分：

- **Unauthorized automation**：X 明确说明，用户对自己授权给第三方应用的访问或使用负有责任。
- **Multiple Accounts and Coordination**：多账号本身并不自动违规；政策同时列出了具有不同身份、用途并遵守技术限制的合法多账号场景。
- **Ban Evasion**：在已有执行措施后创建、接管或重新利用其他账号规避处罚可能导致进一步处罚。
- **Account Compromise**：X 将凭证、token、key、cookie 被恶意第三方应用或网站获取、弱密码、恶意软件、受感染网络等列为账号被 compromise 的可能情形。
- **Inauthentic Behaviors**：包括批量/重复内容、激进或自动化互动、follow churn、indiscriminate following、虚假互动、第三方服务实施违规互动等。
- **Appeals**：如果用户认为 X 作出了错误判断，可以提交 appeal。

### 对本项目的意义

这份政策说明了为什么自查表需要同时调查：

1. 第三方 OAuth 应用；
2. 自动化工具/API；
3. 短时间内的大量互动；
4. 多账号及账号之间的互动；
5. 登录和账号安全事件；
6. 是否存在可能的账号 compromise；
7. 是否有可能被解释为 ban evasion 的行为。

但政策本身**不能证明某个具体账号做过其中任何一项行为**。

尤其要避免下面这种错误推理：

> 发现一个有 Read & Write 权限的 OAuth 应用 → 所以它一定发过帖子 → 所以它导致了 `inauthentic behavior` 封禁。

正确的调查链应该是：

> 授权关系 → 权限范围 → 实际使用证据 → 时间关系 → 独立证据 → 是否存在因果解释。

## 二、X Transparency Center：Platform Manipulation

- [X Transparency Center：Platform Manipulation](https://transparency.x.com/en/reports/platform-manipulation)
- [X Transparency Center：Rules Enforcement](https://transparency.x.com/en/reports/rules-enforcement)

X 的 Transparency Center 将 platform manipulation 描述为通过大量、激进或欺骗性活动误导他人或干扰用户体验的行为，并讨论了 spam、恶意自动化、fake accounts、artificial amplification 和 coordinated activity 等类别。

历史报告还介绍过 anti-spam challenges，例如要求账号完成手机号/邮箱验证或 CAPTCHA，以确认可疑活动背后确实有人控制账号。

### 注意时间范围

Transparency Center 中的 Platform Manipulation 专题页目前展示的是较早期的公开报告数据，因此**不要把其中的历史统计数字直接当成 2026 年当前执法比例**。

这里更适合把它作为：

- 官方概念定义的补充；
- 了解 X 如何描述 platform manipulation 的历史材料；
- 理解“自动检测 / anti-spam challenge / 人工申诉”之间关系的背景资料。

## 三、一个很值得记录的公开申诉案例：围绕可验证的系统矛盾

近期公开的 Reddit 案例中，有用户在被标记为 `inauthentic behavior` 后多次申诉失败。后来用户注意到 X 要求其完成某项 “on-screen instructions”，但实际登录界面并没有出现相应指引。

后续申诉没有继续单纯强调“我是正常用户”，而是围绕这个**可验证的流程矛盾**说明情况。之后用户报告账号恢复，并收到 X 表示不存在违规的通知。

来源：

- [Reddit：X restored my account after 2 weeks](https://www.reddit.com/r/twitterhelp/comments/1w4qqu3/x_restored_my_account_after_2_weeks_of/)

### 为什么值得收录

这个案例不能证明“指出 on-screen instructions 不存在就一定能解封”。它真正值得参考的是调查方式：

> **系统要求 A → 用户实际看到 B → A 与 B 不一致 → 用截图/时间线证明差异 → 请求复核。**

这与本项目的思路高度一致：不要只写“我没有违规”，而是尽可能找出可以被第三方检查的事实。

## 四、反复申诉后恢复：只能作为经验观察

公开社区中还能看到一些用户经历了多次申诉后恢复账号，例如第三次、第四次甚至更多次提交后出现不同结果。

这类案例可以说明：

- 第一次自动回复并不一定等于最终结果；
- 重新整理事实和材料可能值得尝试；
- 不同账号、不同时间、不同触发条件可能得到不同结果。

但不能据此推出：

> “申诉到第 N 次就会解封。”

也不能推出某一种措辞、语气或 AI 生成方式具有因果上的必胜效果。

因此本项目只把“多次申诉后恢复”作为**观察到的社区经验**，不把次数写入 Checklist 的成功公式。

## 五、恢复邮件 ≠ 功能完全恢复

公开社区还存在一种值得注意的情况：用户收到“账号恢复”或类似通知，但实际登录后仍处于 read-only、功能受限或其他异常状态。

因此，如果账号最终出现“恢复”迹象，建议继续记录：

- 是否可以正常发帖；
- 是否可以回复；
- 是否可以点赞、转发、引用；
- 主页是否恢复正常；
- 历史内容是否恢复；
- 粉丝/关注数据是否恢复；
- 是否仍显示 suspended / read-only；
- 是否收到明确的 restoration email；
- 恢复后是否再次出现限制。

这也是为什么本项目应该把“申诉结果”和“实际功能状态”视为两个不同字段，而不是看到一封恢复邮件就结束调查。

## 六、不要把个案现象写成因果结论

公开社区中经常出现这样的叙述：

- “我创建了备用号，然后备用号也被封了”；
- “我撤销某个应用后账号恢复了”；
- “我用了某个模板之后账号恢复了”；
- “我发了第五次申诉之后恢复了”；
- “我用了 AI 写申诉信之后恢复了”。

这些都可以记录，但单独一个个案通常无法证明因果关系。

推荐记录为：

| 类型 | 写法 |
| --- | --- |
| 已确认事实 | “用户在 X 月 X 日提交第 3 次申诉，X 月 X 日账号恢复。” |
| 时间关系 | “恢复发生在某项操作之后。” |
| 异常信号 | “用户认为该操作可能与恢复有关。” |
| 尚未证明 | “目前没有独立证据证明该操作导致恢复。” |

这套分层也适用于 OAuth、Family Tree / Twitter Family、第三方应用和账号安全事件。

## 七、Threads / X 等平台的经验帖如何使用

Threads、X、Reddit 上的个人经验可以作为非常有价值的案例材料，但最好优先保存：

- 原帖链接；
- 发布时间；
- 封禁原因原文；
- 申诉次数和时间线；
- X 返回的原始邮件/页面截图；
- 用户明确描述的操作；
- 最终账号状态；
- 是否存在恢复后的再次限制。

如果只有“我解封了，这是我的模板”而没有时间线或原始证据，可以作为低置信度经验参考，不宜作为项目的核心结论。

## 八、资料使用等级

为了避免 README 最后变成“成功案例堆”，建议采用以下等级：

**A · 官方资料**

X Help、X Transparency Center 等。用于定义规则和官方概念。

**B · 有时间线和原始材料的公开个案**

优先收录。用于观察实际申诉流程。

**C · 有完整叙述但证据有限的个案**

可以收录，但必须标注为 anecdotal / 个案经验。

**D · 只有模板或单句成功宣称**

可以阅读，不作为方法论依据。

**E · 要求付费“代解封”、索要密码/验证码/token 的服务**

不作为申诉方法推荐；涉及账号安全时尤其需要警惕。

## 结论

这个项目不提供“万能申诉词”。

它更希望帮助用户完成一件简单但容易被忽略的事情：

> **在再次点击 Appeal 之前，先弄清楚到底发生了什么。**

整理：Lynn   
代笔：ChatGPT / Sage
