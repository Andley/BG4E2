---
title: "圖析符號說明"
draft: false
---

# 圖析符號說明 (2026-07)


形式 (form) 的符號  | 含意 
:---: | :----: 
<span class='verb'>紅色字體希臘文</span> | 動詞 
<span class='ptc'>藍色字體希臘文</span> | 分詞 
<span class='inf'>綠色字體希臘文</span> | 不定詞 
xxx⁞yyy | 詞形代碼有兩種可能

結構 (structure) 的符號  | 含意 
:---: | :----: 
 ( ...... ) | 子句的構成元素 (constituent) 
 ⟦ .. ⟦ ... ⟧.. ⟧ | 內嵌子句 (Embedded Clause) 
 ⟨ ...... ⟩ | 內嵌子句的構成元素 (constituent) 
 « .. ‹ .... › .. » | 構成元素內的詞組 (word group)
(前半段)⦇ ... ⦈(後半段) |  倒置 (hyperbaton)
⸉⸊、⸉δὲ⸊ | 後置詞原本的位置、調換之後的新位置



功能 (function) 的符號  | 含意
:---: | :----: 
S/P/C/A/V| S=主語; P=謂語; C=補語; A=狀語; V=稱謂 or 驚嘆
S/P/C/A<br>s/p/c/a<br><sub>s</sub>/<sub>p</sub>/<sub>c</sub>/<sub>a</sub> | 主要子句、從屬子句的構成元素用大寫<br>內嵌子句 (Embedded Clause) 用小寫<br>遞迴內嵌子句 (Recursive Embedded Clause) 用<sub>下標的小寫</sub>
= |  同位 (apposition)</br>通常涉及名詞類，可以取代先行詞 (antecedent)
≒| 附帶說明 (epexegetical)</br>通常涉及動詞類，不能取代先行詞 (antecedent)
+  | 補充 (complement) </br> object-complement 中的 complement (相當於 object 的 predicate)


意義 (meaning) 的符號  | 含意
:---: | :----: 
...xxx... | 從上下文推敲出來被省略掉的字詞
°¹, °², °³ ...| 指向(修飾、連結)其他的字詞/片語
xxx°¹、yyy°², zzz°³ ...| 被指向 (修飾、連結) 的字詞/片語
⮥、⮧ |  指向上文、指向下文


段落 (paragraph) 的符號  | 含意
:---: | :----: 
═════════════| 大段落
─────────────| 中段落
⋯⋯⋯⋯⋯⋯⋯| 小段落
⎀ ...⎀ | 插入的段落


<div style='page-break-after: always;'></div>

#### 經文出處
- 都用英文縮寫，空一格，數字:數字 ⇒ 這樣 reference tagger 才會 work
- 編號 
	- 章節：
		- Chapter §57
			- §57.1
				- §57.1a
	- 例句：§57(1)


#### OpenText 2.0 未來長相

Christopher D. Land and Francis G. H Pang, “The Past, Present, and Future of the OpenText.Org Annotated Greek Corpus,” in _The Language and Literature of the New Testament: Essays in Honour of Stanley E. Porter’s 60th Birthday_, ed. Lois K. Fuller Dow, Craig Alan Evans, and Andrew W. Pitts, Biblical Interpretation Series Volume 150 (Leiden: Boston (Mass.) Brill, 2017), 92.

(1) 不改變 word-order，呈現希臘文 discontinuity (hyperbaton) 的特色
> In developing our XML format, we chose to *rigidly* maintain the canonical word order of the base texts being annotated.

- <rt>Mat 14:16</rt> <RUBY><ruby><ruby>Ὁ<rt>-</rt></ruby><rt>ὁ</rt></ruby><rt>T-NSM</rt></RUBY> <RUBY><ruby><ruby>δὲ<rt>And</rt></ruby><rt>δέ</rt></ruby><rt>CONJ</rt></RUBY> <RUBY><ruby><ruby>Ἰησοῦς<rt>Jesus</rt></ruby><rt>Ἰησοῦς</rt></ruby><rt>N-NSM-P</rt></RUBY> (<RUBY><ruby><ruby><mark class='verb'>εἶπεν<rt>said</rt></ruby><rt>ἔπω, ἐρῶ, εἶπον</rt></ruby><rt>V-AAI-3S</rt></RUBY>)P <RUBY><ruby><ruby>αὐτοῖς·<rt>to them</rt></ruby><rt>αὐτός</rt></ruby><rt>P-DPM</rt></RUBY>  
- Opentext 1.0 vs. 2.0 ![images/Pasted image 20230317084649.png](images/Pasted%20image%2020230317084649.png)

- <rt>Heb 10:1</rt> ⸉<RUBY><ruby><ruby>γὰρ<rt>for</rt></ruby><rt>γάρ</rt></ruby><rt>CONJ</rt></RUBY>⸊⮥⬎⬏
	- (<<RUBY><ruby><ruby>Σκιὰν<rt>A shadow</rt></ruby><rt>σκιά</rt></ruby><rt>N-ASF</rt></RUBY>>c... ⸉⸊<RUBY><ruby><ruby><mark class='ptc'>ἔχων<rt>having</rt></ruby><rt>ἔχω</rt></ruby><rt>V-PAP-NSM</rt></RUBY>)A... (<RUBY><ruby><ruby>ὁ<rt>the</rt></ruby><rt>ὁ</rt></ruby><rt>T-NSM</rt></RUBY> <RUBY><ruby><ruby>νόμος<rt>law</rt></ruby><rt>νόμος</rt></ruby><rt>N-NSM</rt></RUBY>)S ...A(...c‹<RUBY><ruby><ruby>τῶν<rt>of the</rt></ruby><rt>ὁ</rt></ruby><rt>T-GPN</rt></RUBY> <RUBY><ruby><ruby><mark class='ptc'>μελλόντων<rt>coming</rt></ruby><rt>μέλλω</rt></ruby><rt>V-PAP-GPN</rt></RUBY> <RUBY><ruby><ruby>ἀγαθῶν,<rt>good things</rt></ruby><rt>ἀγαθός</rt></ruby><rt>A-GPN</rt></RUBY>› ») <RUBY><ruby><ruby>οὐκ<rt>not</rt></ruby><rt>οὐ</rt></ruby><rt>PRT-N</rt></RUBY> <RUBY><ruby><ruby>αὐτὴν<rt>themselves</rt></ruby><rt>αὐτός</rt></ruby><rt>P-ASF</rt></RUBY> <RUBY><ruby><ruby>τὴν<rt>the</rt></ruby><rt>ὁ</rt></ruby><rt>T-ASF</rt></RUBY> <RUBY><ruby><ruby>εἰκόνα<rt>form</rt></ruby><rt>εἰκών</rt></ruby><rt>N-ASF</rt></RUBY> <RUBY><ruby><ruby>τῶν<rt>of the</rt></ruby><rt>ὁ</rt></ruby><rt>T-GPN</rt></RUBY> <RUBY><ruby><ruby>πραγμάτων,<rt>things</rt></ruby><rt>πρᾶγμα</rt></ruby><rt>N-GPN</rt></RUBY> <RUBY><ruby><ruby>κατ᾽<rt>each</rt></ruby><rt>κατά</rt></ruby><rt>PREP</rt></RUBY> <RUBY><ruby><ruby>ἐνιαυτὸν<rt>year</rt></ruby><rt>ἐνιαυτός</rt></ruby><rt>N-ASM</rt></RUBY> <RUBY><ruby><ruby>ταῖς<rt>with the</rt></ruby><rt>ὁ</rt></ruby><rt>T-DPF</rt></RUBY> <RUBY><ruby><ruby>αὐταῖς<rt>same</rt></ruby><rt>αὐτός</rt></ruby><rt>P-DPF</rt></RUBY> <RUBY><ruby><ruby>θυσίαις<rt>sacrifices</rt></ruby><rt>θυσία</rt></ruby><rt>N-DPF</rt></RUBY> <RUBY><ruby><ruby>ἃς<rt>which</rt></ruby><rt>ὅς, ἥ</rt></ruby><rt>R-APF</rt></RUBY> (<RUBY><ruby><ruby><mark class='verb'>προσφέρουσιν<rt>they offer</rt></ruby><rt>προσφέρω</rt></ruby><rt>V-PAI-3P</rt></RUBY>)P <RUBY><ruby><ruby>εἰς<rt>to</rt></ruby><rt>εἰς</rt></ruby><rt>PREP</rt></RUBY> <RUBY><ruby><ruby>τὸ<rt>the</rt></ruby><rt>ὁ</rt></ruby><rt>T-ASN</rt></RUBY> <RUBY><ruby><ruby>διηνεκὲς<rt>continuous</rt></ruby><rt>διηνεκής</rt></ruby><rt>A-ASN</rt></RUBY> <RUBY><ruby><ruby>οὐδέποτε<rt>never</rt></ruby><rt>οὐδέποτε</rt></ruby><rt>ADV</rt></RUBY> (<RUBY><ruby><ruby><mark class='verb'>δύναται<rt>is able</rt></ruby><rt>δύναμαι</rt></ruby><rt>V-PNI-3S</rt></RUBY>)P <RUBY><ruby><ruby>τοὺς<rt>those</rt></ruby><rt>ὁ</rt></ruby><rt>T-APM</rt></RUBY> <RUBY><ruby><ruby><mark class='ptc'>προσερχομένους<rt>drawing near</rt></ruby><rt>προσέρχομαι</rt></ruby><rt>V-PNP-APM</rt></RUBY> <RUBY><ruby><ruby><em>τελειῶσαι·</em><rt>to perfect</rt></ruby><rt>τελειόω</rt></ruby><rt>V-AAN</rt></RUBY> 
- Opentext 1.0 ![images/Pasted image 20230317084752.png](images/Pasted%20image%2020230317084752.png)
- Opentext 2.0 ![images/Pasted image 20220611064936.png](images/Pasted%20image%2020220611064936.png)




(2) 把冠詞、分詞內嵌子句分開來
- Opentext 1.0 vs 2.0 ![images/Pasted image 20220611063614.png](images/Pasted%20image%2020220611063614.png)

