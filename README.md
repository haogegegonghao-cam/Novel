# 《最后一个常数》（The Last Constant）

中文原创科幻短篇项目 · AI 辅助工作稿阶段

> **状态（2026-10-29，第二轮）**：根据作者第二轮的要求重新构思并重写为 v3。AI 已完成：审视旧稿、重新设计、完整工作稿、科学审查、编辑审查、修订与 HTML 排版。**人类作者尚未进行实质性修改。** 本目录中的小说文本是 AI 生成的工作稿，不等同于最终的人类原创作品。
> 本项目未提交到任何 Git 仓库，未上传、发布或投稿。

---

## 一句话

一位年轻物理学家发现了一条新的自然规律；它在被全世界的机器同步使用之后一天天变弱，最后安定下来，上面留下了使用者的心跳。她由此回头去看人类最古老的常数，发现它们也被什么东西扶着。

## 文件

| 文件 | 内容 |
|---|---|
| `novel.html` | **从这里开始读。**v3 排版阅读版，电脑与手机浏览器均可直接打开（章节目录、字号、明暗切换） |
| `novel_draft.md` | v3 正文 Markdown（约 1.35 万字，含标点），供后续修改 |
| `plot_structure.md` | 对 v2 的审视（保留/删除）、揭示顺序、八节结构、伏笔表、结局逻辑 |
| `worldbuilding.md` | v3 科学世界观：真实/外推/虚构的划分、虚构公设、八个限制性问题、六组概念区分、刻意保留的未知 |
| `characters.md` | v3 人物档案 |
| `scientific_review.md` | v3 科学审查（真实物理核查、一致性压力测试、修改记录） |
| `editorial_review.md` | v3 编辑审查与修订清单 |
| `similar_works.md` | 既有作品比较；文末为 v3 新增风险（Lem《新宇宙创始论》等） |
| `concepts.md` | 第一轮的四个方案比较，文末附 v3 与各方案的关系 |
| `creative_log.md` | 创意来源、作者与 AI 的贡献划分、两轮的决策与版本记录 |
| `author_decisions.md` | 需要作者决定或重写的事项（★ 为重点） |
| `versions/` | 全部历史版本：v1、v2、v3 审查前快照、v2 时期的全部文档与 HTML、HTML 生成脚本 |

## 建议的阅读顺序
1. `novel.html`（先作为普通读者读一遍）
2. `author_decisions.md`
3. `editorial_review.md`、`scientific_review.md`
4. 其余按需查阅

## 修改 Markdown 后重新生成 HTML

```bash
python3 ~/Desktop/The_Last_Constant/versions/make_html.py ~/Desktop/The_Last_Constant/novel_draft.md ~/Desktop/The_Last_Constant/novel.html
```

## 建议的下一步
1. 开始修改前，把 `novel_draft.md` 另存为 `versions/novel_draft_v3_ai.md` 冻结。
2. 处理 `author_decisions.md` 中的 ★ 项。
3. 亲自重写首句、末句、上海的两场戏和书记员的最后几句话。
4. 每轮修改在 `creative_log.md` §6 记录。

## 关于存放位置
会话的初始工作目录 `/Volumes/Claude` 是只读的安装磁盘映像，因此项目建在 `~/Desktop/The_Last_Constant/`。
