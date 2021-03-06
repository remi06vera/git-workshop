# 4/30 Node.js 第一、第二堂

## 上課內容
* 終端機指令
* git 指令
* git 分支
* github平台運用
* git 一般業界實務
* Markdown 語法


## 終端機基本指令(window)

> **pwd**    顯示目前工作的資料夾 

> **cd**     指定到某個資料夾 

> **cd ..**  回到上一層   

> **touch**  建立新的檔案  

> **mkdir**  建立新的檔案夾

> **dir**    顯示該資料夾所有檔案列表  

> **rm**     刪除檔案

>**rmdir**   刪除資料夾 (資料夾不是空的不能刪除)

>**rm -rf**  刪除資料夾(不管資料夾內有沒有資料都會直接刪除)

>**ctrl+l**     讓畫面變乾淨

>**code 資料夾名稱**   用vscode開啟該資料夾 (退回上一層)


## git 

> **git --version**    git的版本

> **git init**     將資料夾 新增.git 文件  用來追蹤資料的改變

> **git status**  狀態(看工作目錄 和暫存區域)   

> **git log**  歷史 (看 commit)  

> **git add**  加到staging area

> **git commit -m "原因"**  提交入版本庫   

> **git rm --cached "資料名"**  從暫存區移開(反悔加入，但保留檔案)  

> **git rm -f  資料名**  反悔加入暫存區，而且真的刪除檔案

> **git restore --staged 資料名**  從暫存區域回到工作目錄 

> **git restore 資料名**  捨棄在工作目錄的改變(包括修改與刪除)

## git 分支

> **git branch**    查看分支

> **git branch 分支名**      創建新分支

> **git switch 分支名**  改到該分支   

> **git merge 分支名**  合併(要先 add  commit 才能merge)

## 上課心得
開始學習前端課程已過了兩個月，但因為吸收較慢，一直用很恐慌的心情上課

有著：「上過的語言沒學好，新的語言要開始了，我該怎麼辦」的感覺><

在4/30第一堂課上，小賴老師的教導方式和上課氣氛，讓我慢慢的跟得上上課進度，也讓我好像有多了一點點信心可以繼續下去學習程式語言。
謝謝老師分享實務經驗，和鼓勵我們發問問題，但另外我需要反省的是，有些粗心打錯字的地方沒注意到，向老師提問時才發現，這就是我自己需要努力的地方並要學習看指令。