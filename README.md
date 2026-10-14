# 祝你好心情！

I have a computing background and experience in patent agency work. I build tools around that work, from a small exam practice app to an AI-assisted drafting system.

I'm looking for **FDE and AI product roles**. My main project is TTC: I define the requirements and review process, work through the engineering decisions, and test the results. I use AI coding tools throughout development.

计算机背景，5年电学专利代理行业经验。目前主要在做 TTC，把实际撰写流程中的问题做成SAAS。

## 028 / TTC — patent drafting workflow

A practitioner uploads a technical disclosure, reviews the proposed solution, then works through claims, drawings and specification text.

One problem I spent time on: a model can return a result after its inputs have changed. TTC records the confirmed versions used by each run and checks them again before publishing. Failed attempts keep their drafts and leave the previous usable version intact.

**Next.js · React · TypeScript · SQLite · HTTP model APIs**

[Project and architecture](https://github.com/orphanwarrior/028-ttc-showcase) · [Engineering decisions](https://github.com/orphanwarrior/028-ttc-showcase/blob/main/docs/ENGINEERING_DECISIONS.md)

![TTC workbench](https://raw.githubusercontent.com/orphanwarrior/028-ttc-showcase/main/assets/screenshots/workbench.jpg)

*Real application UI in an isolated synthetic test environment.*

The application and its professional rules are private; the showcase explains the design and what has been tested.

## Patent Exam Practice

I made this for my patent agent exam preparation. It offers random questions, explanations, wrong-answer review, favorites and learning statistics. Records stay in the browser.

**HTML · CSS · JavaScript · GitHub Pages**

[Try it](https://orphanwarrior.github.io/test-web/study.html) · [Source](https://github.com/orphanwarrior/test-web)

The two projects reflect what I want to work on: understand a user's task, build something usable, and deal with the parts that go wrong after the first successful run.
