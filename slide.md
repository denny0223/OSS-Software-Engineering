title: 開放原始碼專案的軟體工程實踐
output: index.html
--

<h1 style="font-size: 72px">
  開放原始碼專案的<br />
  軟體工程實踐
</h1>
<br />

## Denny Huang
## 2023/12/11

--

<h1 style="font-size: 36px">
  https://denny.one/OSS-Software-Engineering
</h1>

--

### Who am I ?

<br />
<h2 style="font-size: 60px">
  <b>Denny Huang</b>
</h2>

* 雷亞遊戲 Rayark Inc.

* SITCON 學生計算機年會 共同發起人

* <a href="https://denny.one/" target="_blank">About me</a>

--

# 開發經驗

--

# 軟體工程？

--

<br />
<h2 style="font-size: 70px">
系統性<br />
規範化<br />
可定量的程序化方法
</h2>
<div align="right">
	<a href="http://zh.wikipedia.org/zh-tw/%E8%BD%AF%E4%BB%B6%E5%B7%A5%E7%A8%8B" target="_blank">wiki</a>
</div>

--

* Request and Analysis Phase（需求與分析階段）

* Design Phase（設計階段）

* Coding Phase （撰寫階段）

* Testing Phase（測試階段）

* Maintenance Phase （維護階段）

--

<h1 style="font-size: 45px">
	Open Source Project 的開發流程？
</h1>

--

# [大教堂和市集](https://zh.wikipedia.org/wiki/%E5%A4%A7%E6%95%99%E5%A0%82%E5%92%8C%E5%B8%82%E9%9B%86)
## [維護一個大型開源項目是怎樣的體驗？](https://www.zhihu.com/question/36292298/answer/160028010)

--

# Release early, release often.

--

# 溝通及討論平台

--

- Slack
	- [g0v](https://g0v.hackmd.io/@jothon/joing0vslack) / [Firebase](https://firebase.community/)
- Telegram
- Gitter
- Mailing list
	- [Google Groups](https://groups.google.com/) / [HyperKitty](https://gitlab.com/mailman/hyperkitty)
	- [SITCON：日常](https://groups.google.com/g/sitcon-general) / [Fedora](https://mail.gnome.org/archives/) / [Linux Kernel](https://lore.kernel.org/)
	- [GNOME Project](https://mail.gnome.org/)
- IRC
	- irssi / webchat
	- [Libera.Chat](https://libera.chat/) / [freenode](https://freenode.net/)
	- [SITCON IRC](https://sitcon.org/irc)

--

<br />
<br />
<h2 style="font-size: 60px">
	Request and Analysis Phase<br />
	需求與分析階段
</h2>

--

# [OPass](https://opass.app/)

--

<h1 style="font-size: 70px">
	Issue Tracking System
</h1>

--

# [GitHub Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)
## [Hudi Issue Support](https://github.com/orgs/apache/projects/40)

--

# [GitLab Issue Board](https://docs.gitlab.com/ee/user/project/issue_board.html)
## [GNOME shell](https://gitlab.gnome.org/GNOME/gnome-shell/-/boards) / [SITCON Camp 2023](https://gitlab.com/sitcon-tw/camp-2023/sitcon-camp-2023-board/-/boards)

--

# [錯誤示範](https://github.com/nwjs/nw.js/issues/293)

--

<br />
<br />
<h2 style="font-size: 60px">
	Design Phase<br />
	設計階段
</h2>

--

# Wiki
## [GNOME Project](https://wiki.gnome.org/) / [nw.js](https://github.com/nwjs/nw.js/wiki)

--

<br />
<br />
<h2 style="font-size: 60px">
	Coding Phase<br />
	撰寫階段
</h2>

--

# 版本控制

--

# Git
## [Git 教學](https://www.youtube.com/watch?v=eznLhINAvQI) / [協作不想吵架？快用版本控制系統](https://www.youtube.com/watch?v=-mcjQxoyaEI)

--

<div align="center">
	<img src="./img/git_branching_model.png" width="380"/>
	<a href="http://nvie.com/posts/a-successful-git-branching-model/" target="_blank">src</a>
</div>

--

# Talk is cheap. Show me the code.

--

# Pull Request / Merge Request

--

<br />
<br />
<h2 style="font-size: 60px">
	Testing Phase<br />
	測試階段
</h2>

--

### Testing
- [Golang testing package](https://pkg.go.dev/testing)
- [Python unittest](https://docs.python.org/3/library/unittest.html)
- [Node.js Test runner](https://nodejs.org/api/test.html)

--

<br />
<h2 style="font-size: 75px">
	Continuous Integration / Continuous Delivery
</h2>

--

# [GitHub Actions](https://github.com/features/actions)
## [SITCON 2022](https://github.com/sitcon-tw/2022/actions)

--

# [GitLab CI](https://docs.gitlab.com/ee/ci/)
## [gnome-shell](https://gitlab.gnome.org/GNOME/gnome-shell/-/pipelines)

--

<br />
<br />
<h2 style="font-size: 60px">
	Maintenance Phase<br />
	維護階段
</h2>

--

# Example: AOSP
## [Report Bugs](https://source.android.com/docs/setup/contribute/report-bugs)

--

<h1 style="font-size:72px">Thanks for listening</h1>

<br />
<div align="center">
<img width="100" src="./img/by-sa.png" />
</div>
<h2 style="font-size: 18px">
本投影片採用<a href="http://creativecommons.org/licenses/by-sa/3.0/tw/" target="_blank">創用 CC「姓名標示—相同方式分享 3.0 台灣」授權條款</a>
</h2>
