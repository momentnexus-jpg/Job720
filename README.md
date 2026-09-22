# Job720

**[中文](#job720-是什么)** · **[English](#what-is-job720)**

---

## Job720 是什么

一个**公开岗位信号的日更索引**。把 AI、芯片（IC 设计）、新能源、BMS、储能这几条方向
在招的岗位，按天、按城市、按公司摊开成一眼能扫完的读数。

**这个仓库里有什么**

| 位置 | 内容 | 节奏 |
|---|---|---|
| [`daily/`](daily/) | **岗位观察**：今天整个库动了什么 —— 新挂多少、撤了多少、哪几家动得最凶 | 每天一篇 |

**每天那篇怎么读**

- 每个数字都标着出处与统计窗口，**不替你下结论**；
- 「今天新挂」里有一部分是**我们自己**接入新来源造成的，那一批单独成句、自己认领，
  不与招聘方的动作混着说；
- 「下线」（这一轮没再看到它）是这条链里最干净的一类数，照实写。

**数据从哪来**：各公司**公开发布的招聘信息**的汇总。我们不改写 JD 原文，只做索引与读数。
按城市、按方向看当前的截面，在站点上：

- 全部在招岗位：<https://job720.goxba.com>
- 岗位观察的站内版：<https://job720.goxba.com/observe>

## 我们不是什么

- 不是招聘方，不替任何一家公司说话，也不评价任何一家公司；
- 不接收简历、不做投递、不做中介、不做培训；
- 不替你下「该去哪家」的结论 —— 数摆在这儿，怎么读是你的事。

## 顺手复查一下

我们给的数，你自己也能拉：

```bash
curl -s 'https://job720.goxba.com/api/jobs?limit=1' | head -c 400
```

---

## What is Job720

A **daily index of public hiring signals** — AI, IC design, new energy, BMS and energy
storage roles, laid out by day, city and company so they can be scanned at a glance.

**In this repository**

| Path | What | Cadence |
|---|---|---|
| [`daily/`](daily/) | **Hiring readout** — what moved across the index today: new postings, retirements, which companies moved most | daily |

**How to read it.** Every figure carries its source and its window, and we state no verdicts.
Part of the daily "newly posted" count comes from sources **we** just connected; that batch is
called out in its own sentence rather than mixed with employer activity. Retirements
(postings no longer seen this round) are the cleanest signal in the chain, and we report them plainly.

Data is aggregated from **publicly posted job openings**. We do not rewrite job descriptions —
we index and count. Live cross-sections by city and track: <https://job720.goxba.com>

**What we are not.** An employer, a recruiter, an agency or a training provider. We take no
side for any company and we do not tell you which one to choose.

```bash
curl -s 'https://job720.goxba.com/api/jobs?limit=1' | head -c 400
```

---

<sub>岗位条目的权利归各招聘方；本仓库只做索引与读数。Job titles and posting details belong to the respective employers; this repository only indexes and counts them.</sub>
