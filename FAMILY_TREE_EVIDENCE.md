# Family Tree / Round Year Fun：证据补充

> 本文只整理公开资料能够支持的历史事实与安全背景，不把这些资料直接解释成某个具体账号被 X 暂停的原因。

## 结论先行

目前能够找到的公开证据已经足以支持一个比“Family Tree 看起来可疑”更强、但仍然克制的结论：

**Twitter Family Tree / Round Year Fun 这一类第三方小游戏历史上确实存在广泛 OAuth 授权、权限范围过大，以及授权后替用户执行非预期账号操作的公开记录。**

因此，如果一个待调查账号的历史 OAuth 记录中出现 Family Tree、My Twitter Family、Twitter Family Tree 或明显属于同一生态的应用，它应该被当作一个值得核查的**第三方账号安全线索**。

但目前没有公开证据可以据此推出：某个具体用户授权过 Family Tree，就一定因此触发了 X 的 `inauthentic behavior` 判定。

---

## 1. Family Tree 与 Round Year Fun 的关系

公开网页曾将 **Twitter Family Tree**、**Twitter Interaction Circle**、Twitter Crush、Twitter Worth 等功能作为 Round Year Fun 的 Twitter 游戏产品列出。这至少能证明“Family Tree”并不是我们凭空创造出来的名称，而是这一类第三方 Twitter 游戏生态中的实际产品名称。

- [Round Year Fun / Fun Twitter Games](https://imageholder.art/)

这里的证据只能证明产品名称和功能关联，不能单独证明应用是否安全。

---

## 2. 2021 年的独立技术调查：权限与实际行为

这部分是目前最重要的证据之一。

Conspirador Norteño 在 2021 年公开调查 Round Year Fun 应用时记录：这些应用请求的 OAuth 权限非常广泛；在测试账号上，应用实际使账号关注了多个并非用户主动选择的账号，并同时对这些账号进行静音。

更重要的是，这不是单个用户“我感觉它有问题”的故事，而是一次公开的样本调查：研究者统计了十天内包含相关链接的 **214,830 条推文、180,402 个账号和 1,091 个不同应用名称**，并观察到大量与这些应用相关的异常关注增长。

- [Conspirador Norteño — Twitter Family / Round Year Fun 调查线程](https://threadreaderapp.com/thread/1383216080663945219.html)
- [Conspirador Norteño — Fun all year round until your Twitter account gets compromised](https://www.conspirator0.com/p/fun-all-year-round-until-your-twitter/)

这里最有价值的不是“这个网站很坏”这一结论，而是：**确实存在从 OAuth 授权 → 第三方应用 → 账号实际行为的公开技术调查链条。**

这也说明了为什么我们在调查 Lynn 的账号时不能只记录“Family Tree 出现在 OAuth 列表里”，而应该继续寻找实际行为证据。

---

## 3. Forbes 的独立报道

Forbes 在 2021 年报道 Twitter Family Tree 事件时，对 Round Year Fun 相关应用能够取得的权限进行了具体描述，包括：

- 查看时间线；
- 查看账户设置；
- 查看关注、静音、屏蔽关系；
- 关注 / 取消关注账号；
- 修改部分账户设置；
- 发布和删除推文；
- 点赞、取消点赞、回复和转推；
- 管理列表和 collections 等。

报道同时描述了应用在用户没有明确预期的情况下执行关注操作的情况。

- [Forbes — That ‘Twitter Family Tree’ Trend Is Secretly Following Random Accounts Without Your Consent](https://www.forbes.com/sites/jacksonweimer/2021/04/10/that-twitter-family-tree-trend-is-secretly-following-random-accounts--without-your-consent/)

Forbes 的价值在于：它与 Conspirador Norteño 的技术调查形成了独立来源之间的交叉验证。

但仍需注意，**媒体报道的是这一类应用的历史行为，不是 Lynn 本人的账号行为。**

---

## 4. 后续公开资料：这一生态并没有只出现一次

2022 年，Conspirador Norteño 再次整理 Round Year Fun 的相关行为，并指出 “My Twitter Family”等应用会利用授权权限替用户执行关注操作，同时记录到相关应用会使用大量不同的随机名称发布内容。

- [Conspirador Norteño — Fun all year round until your Twitter account gets compromised](https://www.conspirator0.com/p/fun-all-year-round-until-your-twitter/)

此外，后续日文技术文章继续追踪“私のTwitter家族 / Twitter家系図”等名称，并记录用户报告的未经预期的发帖、关注等行为。

- [SBAPP — 「私のTwitter家族」スパムが勝手にツイートする、乗っ取り連携解除と対処法](https://sbapp.net/appnews/sns/twi/twitterkazoku-127194)
- [Hashout — Xで大流行「やりとりークル」](https://hashout.jp/sns/1900/)
- [RoboIn — 「私のTwitter家族」「私のTwitterやりとりークル」は危険なスパム](https://roboin.io/article/2024/02/05/twitter-family-tree-is-spam/)

其中关于不同域名、名称是否由同一组织运营的判断，部分属于文章作者根据页面、图片、跳转关系作出的推断。因此本项目不会把“同一组织”写成已经独立证实的事实。

---

## 5. 这对 Lynn 的调查意味着什么？

这里必须把“生态级证据”和“账号级证据”分开。

### 生态级证据：目前较强

可以比较有把握地说：

1. Twitter Family Tree / Round Year Fun 曾经是实际存在的第三方 Twitter 游戏生态；
2. 相关应用曾请求非常广泛的 OAuth 权限；
3. 公开测试与调查曾观察到授权后的非预期账号操作；
4. 这一现象有研究者、媒体和后续技术文章等不同来源记录。

### 账号级证据：仍需要补

如果要把它与 Lynn 的账号联系起来，还需要尽可能找到：

1. 具体 OAuth 应用名称；
2. 具体授权时间；
3. 具体权限范围；
4. 当时使用的域名；
5. 是否真的打开并使用过 Family Tree；
6. 授权后账号是否出现异常关注、发帖、点赞、转推等活动；
7. 这些活动是否有 X 邮件、账号历史、截图或其他独立材料支持；
8. 最后才是这些事件与 suspension 的时间关系。

因此最有价值的下一步不是继续寻找“Family Tree 很危险”的文章，而是寻找**实例级证据**。

---

## 6. 为什么不能直接说“Family Tree 导致封号”

假设时间线是：

```text
授权 Family Tree
      ↓
几天后出现异常活动
      ↓
随后收到 inauthentic behavior suspension
```

这会使 Family Tree 成为一个**值得调查的候选解释**，但仍然不是因果证明。

更强的证据链应该接近：

```text
具体 OAuth App
      ↓
具体权限
      ↓
具体授权时间
      ↓
可验证的实际调用 / 账号操作
      ↓
异常行为与调用在时间上对应
      ↓
X 的通知或其他独立材料指向相关行为
      ↓
才能讨论较高可信度的因果关系
```

目前我们还没有公开材料能够把整条链补齐。

---

## 7. 当前建议的证据分级

| 证据 | 当前判断 |
|---|---|
| Family Tree / Twitter Family Tree 曾存在 | 已有公开资料支持 |
| 它属于 Round Year Fun 类 Twitter 游戏生态 | 有公开资料支持 |
| 相关应用请求广泛 OAuth 权限 | 有较强公开资料支持 |
| 相关应用曾替用户执行非预期操作 | 有技术调查 + 媒体报道支持 |
| Lynn 曾授权具体 Family Tree OAuth App | 需要账号自身记录确认 |
| Lynn 的 App 实际执行过异常操作 | 目前待核查 |
| 异常操作导致 X 判定 inauthentic behavior | 目前没有直接证据 |

**这张表就是目前最重要的边界。**

---

## 8. 一个更准确的项目表述

如果 README 或调查报告需要一句话介绍这个线索，建议使用：

> **Family Tree / Round Year Fun is a historically documented third-party Twitter application ecosystem associated with broad OAuth permissions and reports of unexpected account actions. If such an application appears in an account's OAuth history, it is worth investigating as a security lead; however, its presence alone does not establish that it caused an X suspension.**

中文：

> **Family Tree / Round Year Fun 是一个有公开历史资料记录的第三方 Twitter 应用生态，相关应用曾被记录具有较广泛的 OAuth 权限，并出现过非预期账号操作。若此类应用出现在某个账号的 OAuth 历史中，它值得作为安全线索进一步调查；但仅凭其存在，不能认定它导致了 X 的账号暂停。**

---

## 9. 资料来源

- [Forbes — That ‘Twitter Family Tree’ Trend Is Secretly Following Random Accounts Without Your Consent](https://www.forbes.com/sites/jacksonweimer/2021/04/10/that-twitter-family-tree-trend-is-secretly-following-random-accounts--without-your-consent/)
- [Conspirador Norteño — Fun all year round until your Twitter account gets compromised](https://www.conspirator0.com/p/fun-all-year-round-until-your-twitter/)
- [Thread Reader — Round Year Fun apps investigation](https://threadreaderapp.com/thread/1383216080663945219.html)
- [Laim McKenzie — Round Year Fun](https://laim.scot/blog/round-year-fun)
- [SBAPP — Twitter Family spam / account-linking investigation](https://sbapp.net/appnews/sns/twi/twitterkazoku-127194)
- [Hashout — X interaction-circle investigation](https://hashout.jp/sns/1900/)
- [RoboIn — Twitter Family Tree spam investigation](https://roboin.io/article/2024/02/05/twitter-family-tree-is-spam/)

---

**整理：Lynn**  
**资料检索与结构：ChatGPT / Sage**
