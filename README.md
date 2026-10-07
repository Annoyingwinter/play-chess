# ♟️ Annoyingwinter 的公开棋局

一盘**谁都能下**的公开慢棋。走子不需要会代码：在下面的着法表里点一步棋、
提交那个自动填好的 issue，机器人几秒内应招，你的 GitHub 头像会留在棋谱里。

现在轮到 <!-- BEGIN TURN -->?<!-- END TURN --> 方走子。

<!-- BEGIN CHESS BOARD -->
(棋盘在这里生成)
<!-- END CHESS BOARD -->

**轮到你了！从下面的着法表里挑一步：**

<!-- BEGIN MOVES LIST -->
(着法表在这里生成)
<!-- END MOVES LIST -->

玩得开心？把链接甩给朋友，让 TA 接着走一步！

#### 这是怎么运作的

你提交着法 issue 后会触发一个 GitHub Action：Python 脚本走这步棋、重新生成棋盘并自动提交到本仓库。每盘棋都归档在 `games/` 目录（PGN 格式，可下载到棋软里复盘，每步棋都标注了是谁走的）。

发现 bug？欢迎开 issue。

<details>
  <summary>本局最近 5 步</summary>
<!-- BEGIN LAST MOVES -->
(这里自动生成)
<!-- END LAST MOVES -->
</details>

<details>
  <summary>历史所有棋局走子榜</summary>
<!-- BEGIN TOP MOVES -->
(这里自动生成)
<!-- END TOP MOVES -->
</details>

---

想自己也整一个？模板来自 [marcizhu/readme-chess](https://github.com/marcizhu/readme-chess)。
