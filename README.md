xv6 中文文档
===========
== update 02/25/2016

== 2014 版的 xv6 (rev8) 相關文檔正在翻譯中。

xv6 是 MIT 開發的一個教學用的完整的 Unix 操作系統，並且在 MIT 的操作系統課程 [6.828] (http://pdos.csail.mit.edu/6.828/2012/xv6.html) 中使用。  通過閱讀並理解xv6的代碼，可以清楚地了解操作系統中多核心的概念，對操作系統感興趣的同學的十分推薦讀！這分檔案是中文翻譯的 MIT xv6 文檔，是閱讀代碼過程中非常好的參考資料。


[原文在此](http://pdos.csail.mit.edu/6.828/2012/xv6/book-rev7.pdf)

[文中引用的 xv6 源代码](http://pdos.csail.mit.edu/6.828/2012/xv6/xv6-rev7.pdf)

強烈推薦 xv6 源代碼書一同閱讀!原作和翻譯中遇到的括號內的數字，都是指上面連接中文件的源碼行號。





## 翻譯者

* 鮮染 北京大學 信息科學技術學院 計算機系
* 趙天雨 北京大學 信息科學技術學院 計算機系
* 胡樹偉 北京大學 信息科學技術學院 計算機系（I guess）
* 胡文濤 KAUST CS
* 曹揚 上海交通大學 電子信息與電氣工程學院 計算機系
* 安潤功 中國人民大學

*如果你願意貢獻，你的名字也會出現在這裡！ *

## 翻译状况

|章节|初稿|审校|二审
|----|----|----|----|
|封面 |+ |+ |+ |
|前言 |+ |+ |+ |
|零 |+ |+ |+ |
|一 |+ |+ |+ |
|二 |+ |+ | |
|三 |+ |+ | |
|四 |+ |+ | |
|五 |+ |+ | |
|六 |+ |+ |+ |
|附A |+ |+ |+ |
|附B |+ |+ |+ |

## 參與審校

熱情歡迎大家參與到審校工作中！請訪問 https://github.com/Th0ar/xv6-chinese

1. Fork
2. 審校並修改，保證修改後 markdown 解析正確
3. 發送 Pull Request
4. 等待你的名字（不久後）出現在譯者列表中！

## 許可證（License）

文檔中涉及到的 xv6 源代碼使用 [MIT](http://www.opensource.org/licenses/mit-license.php) 許可證。中文翻譯使用 [GNU GPL V3.0](http://www.gnu.org/copyleft/gpl.html) 許可證，在 GNU GPL V3.0 之上，轉載和引用須註明本項目 Github 地址。
---

# xv6 Documentation in Chinese

xv6 is a Unix-like teaching OS developed by MIT, and is being used in MIT's OS class 6.828. By using and understanding xv6's source code, you can grasp core concepts in OS design, thus it's very recommended for those who have strong interest in OS. This documentation is the Chinese translation of xv6 documentation, it is a good reference when reading the source code.

[This is MIT's version of the documentation](http://pdos.csail.mit.edu/6.828/2012/xv6/book-rev7.pdf)

[Source code referred in the documentation](http://pdos.csail.mit.edu/6.828/2012/xv6/xv6-rev7.pdf)
