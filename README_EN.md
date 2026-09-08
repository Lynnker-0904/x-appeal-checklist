# X Appeal Pre-Submission Checklist

[🇬🇧 English](README_EN.md) · [🇨🇳 中文](README.md)

An **offline-first, single-file, no-backend** investigation workspace for people preparing an appeal after an X / Twitter account suspension, restriction, or read-only state.

> This is not an X product and cannot determine whether an account violated a rule. It cannot prove that an OAuth application, IP address, VPN, device, or other third-party factor caused a suspension. Its purpose is to help turn scattered clues into a traceable record.

## What this project does

After an account is suspended, it is easy to fall into one of two traps: repeatedly appealing without reconstructing what happened, or finding one suspicious clue and immediately treating it as the cause.

This project uses a deliberately conservative workflow:

**Facts → Leads → Timeline → Security → Evidence → Appeal → Review**

The central rule is simple: **an OAuth permission is not evidence of actual behavior, and temporal proximity is not proof of causation.**

If you do not know where to begin, you can give this repository to an AI assistant and work through the investigation together. Ask the AI to distinguish clearly between **confirmed facts, anomaly signals, hypotheses, and things that cannot currently be verified**.

## Who is it for?

Use the project when your account:

- has been suspended, limited, or placed in a read-only state;
- shows a reason such as `inauthentic behavior`, spam, or platform manipulation;
- receives repeated automated-looking appeal responses;
- is told to “follow the on-screen instructions” but no usable instructions appear;
- receives a restoration notice while important functions remain unavailable;
- may have been compromised or contains unfamiliar login/session activity;
- has unfamiliar third-party OAuth applications;
- needs a clean timeline and evidence record before another appeal.

## Recommended workflow

### 01 · Record the current state

Write down the username, visible account state, profile changes, unfamiliar sessions/devices, and unexplained posts, likes, follows, unfollows, reposts, or other activity.

### 02 · Review OAuth / third-party applications

For each application, record its name, developer, authorization date, permission scope, whether you recognize it, whether you used it, whether it has been revoked, and any notes.

> A third-party application appearing in your account does **not** by itself establish that it performed an action or caused enforcement.

### 03 · Build a timeline

Record suspension notices, OAuth authorization, login/security events, unexplained activity, security actions, appeals, replies, restoration notices, and later changes in account functionality.

### 04 · Secure the account

Review your password, 2FA, active sessions, connected applications, email, phone number, account sharing, and public/shared devices. If you find an unfamiliar authorization or login, protect the account first and investigate afterward.

### 05 · Build an evidence ledger

Keep screenshots, emails, notices, logs, and other original materials. Record what each item proves and which event it relates to. Do not alter the original evidence merely to make it look cleaner.

### 06 · Prepare the appeal material

Complete the factual checklist, record the issues you want X to review, and document the security measures you actually took. Then generate copy-ready investigation material.

### 07 · Use AI as a reviewer, not a source of facts

Give the generated material to an AI assistant and ask it to check the timeline, identify missing information, separate facts from hypotheses, and help organize the final appeal.

> **Do not let an AI invent experiences, security events, OAuth activity, or other facts that you cannot support.**

## The web tool

Open the live self-check tool:

- https://lynnker-0904.github.io/x-appeal-checklist/

The web app remains intentionally simple: local storage, no account, no backend, and no third-party analytics.

## Public information collection

The repository also contains a separate research layer for public cases:

- [INFORMATION_COLLECTION.md](INFORMATION_COLLECTION.md) — public cases, search keywords, source types, and collection methods.
- [APPEAL_TEMPLATES.md](APPEAL_TEMPLATES.md) — appeal structures, unusual cases, counterexamples, and evidence-weighted conclusions.
- [reddit-appeal-notes.md](reddit-appeal-notes.md) — Reddit cases and notes from the Family Tree / Twitter Family investigation.
- [official-and-community-references.md](official-and-community-references.md) — official rules and selected public cases.
- [INVESTIGATION_FRAMEWORK.md](INVESTIGATION_FRAMEWORK.md) — the framework for separating facts, anomalies, hypotheses, and unknowns.

The research layer is intentionally separate from the personal checklist. Your own account record and other people's public stories should not be mixed together.

## How to read public success stories

A successful appeal is an observation, not a controlled experiment.

A person may report that they succeeded after a particular sentence, number of appeals, device change, browser change, VPN change, OAuth revocation, Premium contact, or external complaint. Unless independent evidence supports the mechanism, the safest description is:

> **They did X, and later Y happened. We do not yet know whether X caused Y.**

This distinction matters especially when studying rare or strange cases. Counterexamples are useful too: someone may copy a popular template and fail, while another person may write something completely different and succeed.

## Investigation principles

1. **Facts first.** Only state as fact what you can support.
2. **Keep “yes”, “no”, and “unknown” separate.** “No evidence found” is not automatically proof of absence.
3. **Do not confuse permission with behavior.** OAuth scope describes capability, not necessarily use.
4. **Do not confuse correlation with causation.** A close timestamp is a lead, not a conclusion.
5. **Preserve original evidence.** Keep the original screenshot, email, notice, or log when possible.
6. **Security comes first.** Protect the account before building theories about why enforcement happened.
7. **Treat AI as an organizing tool.** It can help compare and structure evidence, but it cannot replace evidence.
8. **Record failures as well as successes.** A failed template is useful counter-evidence.
9. **Respect people in public cases.** Collect only information that is already public; do not harass, track, expose, or investigate private information about individuals.
10. **Do not turn workarounds into folklore.** A community trick is not an official method simply because several people repeat it.

## Data and privacy

The web app is designed to be local-first:

- no login;
- no backend;
- no upload of self-check data;
- no third-party analytics;
- no external JavaScript dependencies;
- investigation data is stored in browser `localStorage`;
- JSON export is available;
- the current investigation can be reset.

If you use it on a shared computer, export what you need and clear the local data before leaving.

## Project structure

```text
x-appeal-checklist/
├── index.html                           # offline self-check tool
├── INFORMATION_COLLECTION.md            # public case research
├── APPEAL_TEMPLATES.md                  # appeal structures and case analysis
├── reddit-appeal-notes.md               # Reddit cases and Family Tree notes
├── official-and-community-references.md # official rules and selected cases
├── INVESTIGATION_FRAMEWORK.md           # investigation methodology
├── README.md                             # Chinese project documentation
└── README_EN.md                          # English project documentation
```

## Official sources

For enforcement and appeal procedures, use X's current official documentation first:

- [X Help: Suspended X accounts](https://help.x.com/en/managing-your-account/suspended-x-accounts)
- [X Help: Appeal a locked or suspended account](https://help.x.com/en/forms/account-access/appeals)
- [X Help: Authenticity](https://help.x.com/en/rules-and-policies/authenticity)

Community reports should be treated as secondary evidence and checked against the current official process.

## Disclaimer

This project is for public-information research, personal account investigation, documentation, and appeal preparation. It is **not** intended for illegal activity, harassment, stalking, doxxing, privacy invasion, or evasion of platform security or enforcement systems.

Public cases are usually first-person reports and may be incomplete, inaccurate, or based on the author's own interpretation of events. Their inclusion does not mean that the project endorses their claims or causal explanations.

If a person whose public case is referenced here believes that the material is inappropriate, violates privacy, or causes a legitimate rights concern, the relevant entry may be reviewed and removed or revised.

## Attribution

This project was initiated and maintained by **Lynn**. Parts of the research structure and writing were developed together with **ChatGPT / Sage**.

The project was started on the evening of **September 7, 2026**, after Lynn's third appeal had failed, and developed together with Sage as a way to investigate the account systematically. Hopefully it can be useful to others facing similar situations.
