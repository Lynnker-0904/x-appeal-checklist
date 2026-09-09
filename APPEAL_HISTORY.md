# Lynn 的 X 申诉记录

> 本文件用于记录本次账号申诉过程中实际发送的申诉内容与结果。
> 这不是“成功申诉模板”，也不代表某一种措辞一定有效。它只是我们的实际案例记录，方便后续比较不同申诉内容、时间、渠道和结果。

## Account

`@lynnrebic`

## Background

本账号因 **“inauthentic behavior”** 被 X 暂停。

截至本文件建立时，已经进行过三次申诉，但前三次没有保存完整的原始申诉文本，因此这里不对前三次内容进行补写或推测。

前三次申诉的共同结果是：**失败。**

当时收到的回复基本都是提交后很快返回的自动化/机器人式回复，没有进入我们能够确认的人工沟通阶段。因此，前三次只能作为“已尝试但未成功”的历史记录，不能据此判断具体是哪一句话导致失败。

这也意味着，从前三次申诉中我们目前无法可靠比较具体措辞的效果。

## Appeal #4 — September 9, 2026

这是目前第一次完整保存原文的申诉。

计划发送时间：**芝加哥时间工作时段，并尽量与德州工作时间重合。**

> 注：这里记录的是发送计划，不把发送时间与申诉结果之间的关系预设为因果关系。后续如果账号状态发生变化，再单独记录实际时间。

### Submitted text

```text
Account: @lynnrebic

On August 31, 2026, I mistakenly authorized two third-party OAuth apps with Read & Write access. One was “Your Tweets Beyond #6V12,” linked to a Twitter Family Tree service, which posted two tweets on my behalf without my knowledge or intent. It was authorized at approximately 9:56 AM GMT+8.I also found another Read & Write authorization, “Omit Smart Stone,” approved at 11:32:42 AM GMT+8.

I want to clarify that granting access was a mistake and does not mean I knowingly intended the actions performed by these apps.

After my suspension, I identified these apps and attempted to revoke their access, but could not because my account was suspended. Please revoke their access on my behalf.

I respectfully request a human review of the activity flagged as inauthentic, including the API/activity logs from August 31 to September 3, to determine whether any flagged activity originated from these third-party apps rather than from me.
```

## Why this version is different

这一次的申诉没有把重点放在“我保证自己没有违规”这种抽象表述上，而是提供了可以被平台进一步核查的具体信息：

- 明确账号：`@lynnrebic`
- 明确第三方 OAuth 授权
- 明确 `Read & Write` 权限
- 明确具体应用名称
- 明确其中一个应用与 Twitter Family Tree 服务的关联
- 明确两条异常授权时间
- 明确发现应用后尝试撤销，但因为账号已被暂停而无法完成
- 请求平台代为撤销授权
- 请求人工复核 8 月 31 日至 9 月 3 日的 API / activity logs
- 不直接断言“OAuth 应用就是封号原因”，而是请求平台核查被标记为 inauthentic 的活动是否来自第三方应用

这里最重要的变化是：**把“解释”变成了一个可以被平台内部日志验证的调查请求。**

这并不意味着这种写法一定会成功。X 官方说明，认为账号被错误暂停的用户可以提交 appeal；官方也说明，真实用户的账号有时会被错误暂停，而被怀疑遭到入侵/盗用的账号也可能因为安全风险而被暂停。 [X Help — About suspended accounts](https://help.x.com/en/managing-your-account/suspended-x-accounts)

## Backup angle — login/session activity

这是下一次申诉失败后准备保留的另一个调查角度，**目前不作为已证明的封禁原因**。

Lynn 最近重新登录查看账号状态时注意到，账号的登录/会话记录已经超过 200 条。这个账号使用时间较长，而且 Lynn 有一个长期的个人使用习惯：**通常不会主动退出网页端账号，而是让已经登录的网页长期保持登录状态，偶尔打开或刷新页面。**

因此，登录/会话记录数量本身不能直接解释为异常登录，也不能据此断言 X 是因为“登录次数太多”而进行 enforcement。

如果下一次申诉仍然无效，可以从这个角度提出一个更具体的人工复核请求：

> 账号长期保持网页端登录，因此历史登录/会话记录数量较多。请不要仅依据记录数量判断异常行为；如这些登录/会话活动与本次 enforcement 有关，请核查其具体设备、会话、IP/网络来源以及实际活动，并区分正常的持续登录行为与真正的异常访问或自动化行为。

推荐的英文表述方向：

```text
My account has been in use for a long time, and I normally keep my web session signed in rather than repeatedly logging out. As a result, my account contains a large number of historical login/session records.

I would appreciate it if these records were reviewed based on their actual devices, sessions, network sources, and associated activity, rather than the number of login records alone. If any of this activity was considered relevant to the enforcement, please distinguish normal long-term web sessions from unauthorized access or automated activity.
```

### Evidence handling

目前这个角度只有一个明确事实：**登录/会话记录数量很多，以及长期保持网页登录的使用习惯。**

以下内容在没有后台证据前都只能作为假设：

- “200 多条登录记录触发了风控”；
- “网页长期挂着会被系统判定为机器人”；
- “刷新网页会生成一条新的异常登录”；
- “登录记录多导致了 inauthentic behavior suspension”。

如果后续再次申诉时使用这一角度，重点应该是**请求 X 核查日志，而不是自行认定触发机制**。

## Current observation — September 9, 2026

截至目前，**Appeal #4 尚未发送**。

今天 Lynn 主动退出了 X 账号，并计划暂时保持登出状态，不使用该账号浏览、点赞、转发或进行其他互动。

这一行为来自我们观察到的公开社区案例与个人历史经验，但目前**不能写成“保持登出一定会提高解封率”的结论**。

本次记录的目的，是把它作为后续可比较的变量：

- 是否保持完全登出；
- 登出持续时间；
- 下一次申诉使用的渠道（桌面网页 / 官方 App）；
- 下一次申诉距离上一次申诉的时间；
- 下一次回复是否仍然秒回；
- 回复是否仍为自动化拒绝；
- 后续账号状态是否变化。

## Result

待填写。

- Sent at:
- Response time:
- Response type: 
- Account status after response:
- Human review confirmed: 
- OAuth access revoked: 
- Notes:

## Research note

前三次失败并不意味着“申诉次数越多越没用”，也不能证明机器人回复就是拒绝的原因。我们目前只能确认：前三次没有成功，而且没有保存足够的原始材料来进行文本层面的比较。

近期公开案例也显示，**多次自动拒绝与最终恢复可以同时出现**；因此“已经被秒拒很多次”不能单独作为永久失败的证据。同时，也有案例显示账号恢复后很快再次被暂停，因此“恢复”与“恢复后的稳定状态”应当作为两个不同变量记录。

第四次开始完整保存原文，之后每次申诉都尽量记录：

1. 发送时间（含时区）
2. 使用的渠道
3. 完整申诉文本
4. 自动回复时间
5. 回复原文
6. 回复是否表现为模板化/自动化
7. 账号实际状态
8. 是否出现人工处理迹象
9. 是否发生后续状态变化
10. 新增了哪些事实或证据
11. 上一次申诉与本次申诉之间的间隔
12. 申诉前是否保持登出状态
13. 是否改变申诉渠道（网页 / 官方 App）

**反例也要保存。** 成功案例只能告诉我们某个方案“曾经发生过成功”，失败案例则能帮助我们排除一些看起来有效、实际上并不稳定的路线。

---

*Lynn / ChatGPT / Sage*
