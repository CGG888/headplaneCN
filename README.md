# design-preview —— 设计稿与验收截图（仅供 issue 内链引用图片）

这个分支只放两类二进制资源，**不含任何源码改动**：

- `design/` —— HeadplaneCN 改版的 28 张面板设计稿（`p01.png` … `p28.png`，编号从左到右、从上到下），
  另有 `sheet1.jpg` … `sheet4.jpg`（每张 9 格的联络图）、`boxes.json`（切图边界）与 `INVENTORY.md`（清点与外壳规范）。
- `shots/` —— 逐页验收时的实现截图（真实 dev 环境，1680px 宽），用于和设计稿对照。

这些图被仓库的 issue 正文以内链引用（`https://raw.githubusercontent.com/CGG888/headplaneCN/design-preview/...`）。
如果这个分支被删除，issue 里的图片会全部失效。

设计稿是本分支改版工作的准绳（见 `AGENTS.md` 的硬规则：严格照图 · 多余功能另开 Tab · 每页截图验收），
逐页对齐进度记录在 `.devdata/ACCEPTANCE.md`（该目录不入库）。

上游项目：[tale/headplane](https://github.com/tale/headplane)。
