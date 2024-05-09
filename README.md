# LXGW XiHei / 霞鶩晰黑 / LXGW 晰ゴシック
*原名：LXGW (Trad) Clear Gothic / 霞鶩（傳承）晰黑*

A Chinese font derived from IPAex Gothic. 一款衍生於「IPAex ゴシック」的中文字型。

[![最新版](https://img.shields.io/github/release/lxgw/LxgwXiHei?style=flat-square)](https://github.com/lxgw/LxgwXiHei/releases/latest)

## 項目介紹
2009 年，日本「獨立行政法人情報處理推進機構」（IPA）將「IPA 明朝」和「IPA ゴシック」兩款字型按照 IPA Font License 開源發佈。這兩款字型分別衍生自 TypeBank 公司出品的、由林隆男（Takao Hayashi）設計的[「TB 明朝」](https://www.typebank.co.jp/fontfamily/tbmincho/)和[「TB ゴシック」](https://www.typebank.co.jp/fontfamily/tbgothic/)。後經多年持續修訂，兩款字型擴充成[「IPAex 明朝」「IPAex ゴシック」](https://moji.or.jp/ipafont/)，包含 JIS 第一～第四水準的字符。而[「IPAmj 明朝」](https://moji.or.jp/mojikiban/font/)是對「IPAex 明朝」的進一步擴充，包含了「文字情報基盤」所涵蓋的漢字及其諸多 IVD 變體。

本項目「霞鶩晰黑」爲「IPAex ゴシック」的衍生字型項目，在原始字型的基礎上，利用原有的部件和筆形，增補原始字型未包含的字，並對原有的部分漢字按照舊式印刷常見字形進行調整。此外，簡化了一些部件的出腳（如「枸」「間」「陶」「崗」等字中「口」「日」「缶」「山」部件的出腳），使字形更加簡約。除此之外，重做了希臘字母和西里爾字母，與原字型拉丁字母部分風格一致；新增對越南語拉丁字的支持。符號方面，支持易經八卦和六十四卦符號、太玄經八十一卦符號、麻將符號、中國象棋符號、算籌數字、「正」字計數等特殊符號。

2020 年末，本項目創建，以一點字坊「傳承字形標準化文件」爲主要參考，對「IPAex ゴシック」進行改造（詳見 [legacy 分支](https://github.com/lxgw/LxgwXiHei/blob/legacy/Readme-TW.md)）。後由於傳承字形部件規則的複雜性，以及時間原因，本項目曾於 2021 年 7 月放棄維護並歸檔。由於近來[「霞鶩新晰黑」](https://github.com/lxgw/LxgwNeoXiHei)和[「霞鶩新緻宋」](https://github.com/lxgw/LxgwNeoZhiSong)的發佈和持續完善，2024 年春，本人決定重啓該項目，並創建新項目[「霞鶩緻宋」](https://github.com/lxgw/LxgwZhiSong)，在「霞鶩新晰黑／新緻宋」基礎上回歸舊字形寫法，原有「霞鶩晰黑」推倒重來。

## 總體計劃
本字型計劃發佈兩種不同字形版本。
- **Classic（CL）版：** 參考早期鉛字印刷字形常見寫法，回歸舊式印刷字形，合併一部分「源規格分離」原則下分化的異碼字。
- **Modern（MN）版：** 採用兼顧當代慣用部件寫法的折中印刷字形（非楷化字形），嚴格遵循「源規格分離」原則。

![](./documentation/images/xh-compare-1.png)
![](./documentation/images/xh-compare-2.png)
![](./documentation/images/xh-compare-3.png)

詳細的維護計劃請參閱：[《霞鶩晰黑》重生及《霞鶩緻宋》維護計劃](documentation/plan.md)。

## 收字情況
重啓後首次發佈的「霞鶩晰黑」收錄「國際表意文字核心」（IICore）範圍內的 [9810 個漢字](https://github.com/NightFurySL2001/CJK-character-count/blob/master/iicore-han.txt)。
> #### 何爲 IICore？
> 「國際表意文字核心」（International Ideographs Core，IICore）是 CJK 統一表意文字編碼的最小子集，包含了兩岸四地、日本、南韓、北朝鮮等區域提交的總共 9810 個常用漢字，可用於記憶體容量和輸入／輸出資源有限的設備，以及／或那些不能使用整套 ISO/IEC 10646 表意文字字集的應用系統。IICore 包含 9706 個基本區漢字、42 個擴展 A 區漢字和 62 個擴展 B 區漢字，於 2003 年 IRG 第 21 次會議提出，2004 年 IRG 第 22 次會議通過。

由於個人時間和精力等原因，「霞鶩晰黑」暫僅包含 IICore 所收錄的 9810 個常用漢字。
### 後續增字計劃？
鑒於 IICore 覆蓋範圍有限，本字型計劃後續增補「IPAex ゴシック」所包含的 JIS 第 1～4 級別漢字，另外會考慮增加[「jf 7000 當務字集」](https://justfont.com/jf7000)所收字、[《常用香港外字表》](https://github.com/ichitenfont/suppchara)收錄的常用及次常用字等。並未考慮與「霞鶩新晰黑」所收字彙看齊。

## 獲取字型
進入 [Releases](https://github.com/lxgw/LxgwXiHei/releases) 頁面下載 TTF 格式字型檔案。

## 授權資訊
- 本字型在 IPA 所開發並發佈的 [IPAex ゴシック](https://moji.or.jp/ipafont/) 基礎上衍生，依照 [IPA開放字型授權條款 第1.0版（IPA Font License 1.0）](https://opensource.org/licenses/IPA/) 授權。 使用本字型時，請遵從[「IPA開放字型授權條款 第1.0版」](LICENSE_CHT.md)（[IPA Font License 1.0](LICENSE.md#ipa-font-license-agreement-v10)， [IPAフォントライセンスv1.0](LICENSE.md)）之規定。
- 但凡有任何人使用、複製、修改、分發本字型，或對本字型進行任何符合 IPA Font License 1.0 規定的行為，使用、下載或行使合約規定權利之接受方，亦視為同意遵守 IPA Font License 1.0 的一切規定。
- 根據 IPA Font License 1.0 有關條款，後續衍生不可使用原始授權程序的名稱（包括程式名、檔案名、字型名），且須繼承原有授權條款（故 IPA Font License 1.0 與 SIL OFL 1.1 不相容）。
- 有關 IPA Font License 1.0 的其他常見問題，請參閱 [FAQ（日語）](https://moji.or.jp/ipafont/faq/)，需自備翻譯工具。
- 「IPA字型（IPA Font，IPAフォント）」為日本「獨立行政法人情報處理推進機構」（簡稱「IPA」）的註冊商標。

## 相關資料與工具
### 相關資料
- [原始授權字型 IPA Font](https://moji.or.jp/ipafont/)
- [秋空黑體](https://github.com/ChiuMing-Neko/ChiuKongGothic)
- [京華老宋體](https://zhuanlan.zhihu.com/p/637491623?utm_id=0)及[匯文明朝體](https://zhuanlan.zhihu.com/p/344103391)
- [IBM Plex Sans TC](https://github.com/IBM/plex)
- [臺北黑體](https://sites.google.com/view/jtfoundry/)
- [香港民間字集](https://github.com/hfhchan/hkcs)
- [華英明朝](https://github.com/GuiWonder/HuayingMincho)
- [五月雨明朝（字客網）](https://m.fontke.com/font/25603163/)
- [康熙字典網上版](https://www.kangxizidian.com/)
- [築地五號活字樣本](https://www.asahi-net.or.jp/~sd5a-ucd/Tsukiji-5go-S11-Specimenbook.html)
- [一點字坊](https://github.com/ichitenfont/)[傳承字形標準化文件](https://github.com/ichitenfont/inheritedglyphs)及[一點明體](https://github.com/ichitenfont/I.Ming)
- [共通中文界面](https://www.ccli.gov.hk/tc/iicore/)
- [書同文漢字網 IICore 兩岸四地校對平臺](https://hanzi.unihan.com.cn/IICoreExt)
- [IICore 字表（TXT 格式）](https://github.com/NightFurySL2001/CJK-character-count/blob/master/iicore-han.txt)
### 相關工具
- [漢文博士](https://www.cnblogs.com/hanbox)
- [字統網](https://zi.tools/)
## 更多「霞鶩」系列字型
### 與本項目有關聯的字型
- [霞鶩緻宋 / LXGW ZhiSong](https://github.com/lxgw/LxgwZhiSong)
- [霞鶩新晰黑 / LXGW Neo XiHei](https://github.com/lxgw/LxgwNeoXiHei)
- [霞鶩新緻宋 / LXGW Neo ZhiSong](https://github.com/lxgw/LxgwNeoZhiSong)
### 「霞鶩文楷」系列
- [霞鶩文楷 TC / LXGW WenKai TC](https://github.com/lxgw/LxgwWenKaiTC)
- [霞鶩文楷 GB / LXGW WenKai GB](https://github.com/lxgw/LxgwWenKaiGB) | [Lite](https://github.com/lxgw/LxgwWenKaiGB-Lite)
- [霞鶩文楷 / LXGW WenKai](https://github.com/lxgw/LxgwWenKai) | [Lite](https://github.com/lxgw/LxgwWenKai-Lite)
### 其他
- [霞鶩漫黑 / LXGW Marker Gothic](https://github.com/lxgw/LxgwMarkerGothic)
- [小賴字體 / Xiaolai](https://github.com/lxgw/kose-font)
- [悠哉字體 / Yozai](https://github.com/lxgw/yozai-font)