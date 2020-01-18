# 甬江話字表

本倉庫包含五份甬江小片方言的同音字表，均爲 TSV（製表符分隔）格式。

文件 [`字表.tsv`](字表.tsv) 是完整的字表，爲了製作 [寧波話吳語拼音輸入方案](https://github.com/NGLI/rime-wugniu_gninpou) 而作。該字表現階段僅包含寧波城區口音。後續計劃加入甬江小片各地口音作爲對照。

文件 [`甬城.tsv`](甬城.tsv) 由 [`字表.tsv`](字表.tsv) 刪減而來，爲 [吳語學堂](https://www.wugniu.com/) 的寧波話字音查詢提供數據。兩者的差別請見 [pure 版](https://github.com/shinzoqchiuq/gninpou-dictionary#pure-版) 一節。

文件 [`鎮海.tsv`](鎮海.tsv)、[`北侖.tsv`](北侖.tsv) 及 [`定海.tsv`](定海.tsv) 分別爲鎮海、北侖和定海口音的字表，收錄了幾千個漢字在這三個地方的讀音。這三者也分別爲 [吳語學堂](https://www.wugniu.com/) 的鎮海話、北侖話和舟山話字音查詢提供數據。

所有的註音均使用吳語學堂式吳拼。

## 音系與拼音方案

### 寧波城區

#### 聲母表

|               |  清不送氣音  |    清送氣音    |     濁音     |  鼻音/邊音  | 清鼻音/邊音  |   清擦音    |     濁擦音      |
| :-----------: | :----------: | :------------: | :----------: | :---------: | :----------: | :---------: | :-------------: |
| **雙脣/脣齒** |  p \[p\] 八  |  ph \[pʰ\] 拍  |  b \[b\] 白  | m \[m\] 麥  | mh \[ʔm\] 眯 | f \[f\] 法  |   v \[v\] 佛    |
|   **齒齦**    |  t \[t\] 搭  |  th \[tʰ\] 脫  |  d \[d\] 達  | n \[n\] 捺  | nh \[ʔn\] 那 |             |                 |
|   **齒齦**    |              |                |              | l \[l\] 勒  | lh \[ʔl\] 拎 |             |                 |
|   **齒齦**    | ts \[ts\] 資 | tsh \[tsʰ\] 雌 | dz \[dz\] 瓷 |             |              | s \[s\] 絲  |   z \[z\] 市    |
|   **齦齶**    | c \[tɕ\] 見  | ch \[tɕʰ\] 千  | j \[dʑ\] 其  | gn \[ȵ\] 女 | kn \[ʔȵ\] 黏 | sh \[ɕ\] 西 |   zh \[ʑ\] 徐   |
|   **軟齶**    |  k \[k\] 割  |  kh \[kʰ\] 克  |  g \[ɡ\] 軋  | ng \[ŋ\] 額 | nk \[ʔŋ\] 孲 |             |                 |
|   **聲門**    |  ∅ \[ʔ\] 矮  |                |              |             |              | h \[h\] 喝  | gh/y/w \[ɦ\] 合 |

#### 韵母表

|        開口         |         齊齒          |      合口      |             撮口              |                |
| :-----------------: | :-------------------: | :------------: | :---------------------------: | :------------: |
|     y \[ɿ\] 孜      |      i \[i\] 衣       |   u \[u\] 烏   |          iu \[y\] 鴛          |  yu \[ʮ\] 朱   |
|     a \[a\] 啊      |     ia \[ia\] 亞      |  ua \[ua\] 娃  |                               |                |
|     o \[o\] 啞      |                       |  uo \[uo\] 蛙  | io \[yo\] 嘉<sub>舊文讀</sub> |                |
|     au \[ɔ\] 襖     |     iau \[io\] 要     |                |                               |                |
|     e \[e\] 愛      |     ie \[ie\] 茄      |                |                               |                |
|     ae \[ɛ\] 晏     |                       | uae \[uɛ\] 彎  |                               |                |
| oe \[ø\] / \[ʏ\] 團 |                       |                |                               |                |
|    ei \[ɐɪ\] 安     |                       | uei \[uɐɪ\] 委 |                               |                |
|    ou \[əu\] 倭     |                       |                |                               |                |
|    eu \[œʏ\] 歐     | ieu \[ʏ\] / \[iʏ\] 優 |                |                               |                |
|                     |                       |  un \[ũ\] 碗   |                               |                |
|     an \[ã\] 㹙     |     ian \[iã\] 央     | uan \[uã\] 橫  |                               |                |
|    aon \[ɔ̃\] 昂     |                       | uaon \[uɔ̃\] 汪 |        iaon \[yɔ̃\] 降         |                |
|    en \[əŋ\] 恩     |     in \[iŋ\] 英      | uen \[uəŋ\] 溫 |        iun \[yəŋ\] 軍         | yun \[ʮøŋ\] 春 |
|    on \[oŋ\] 翁     |                       |                |        ion \[yoŋ\] 永         |                |
|    aq \[ɐʔ\] 壓     |    iaq \[iɐʔ\] 約     | uaq \[uɐʔ\] 挖 |                               |                |
|                     |     iq \[iɪʔ\] 益     |                |        iuq \[yəʔ\] 鬱         | yuq \[ʮœʔ\] 室 |
|    oq \[oʔ\] 屋     |                       |                |        ioq \[yoʔ\] 吃         |                |
|    er \[əl\] 而     |                       |                |                               |                |
|     m \[m̩\] 姆      |                       |                |                               |                |
|     n \[n̩\] 芋      |                       |                |                               |                |
|     ng \[ŋ̍\] 五     |                       |                |                               |                |

#### 單字調

|   調類   | 拼音 | 調值 | 例字 |
| :------: | :--: | :--: | :--: |
| **陰平** |  1   |  53  |  東  |
| **陽平** |  2   |  24  |  同  |
| **陰上** |  3   |  35  |  懂  |
| **陰去** |  5   |  44  |  凍  |
| **陽去** |  6   | 213  |  動  |
| **陰入** |  7   |  5   |  篤  |
| **陽入** |  8   |  12  |  毒  |

### 鍾公廟

:construction:

### 鎮海

:construction:

### 北侖

:construction:

### 定海

:construction:

## 字表說明

1. [`字表.tsv`](字表.tsv) 的音系以湯版《寧波方言詞典》爲基礎，綜合了《宁波市志·方言》，相比湯版《寧波方言詞典》，區分了 \[ko\]、\[kuo\] 及 \[kʰo\]、\[kʰuo\]。另外單獨列出了清鼻邊音聲母。
2. \[ʏ\] 韻對應 ieu、oe 兩種拼音。在聲母 t \[t\]、l \[l\]、lh \[ʔl\] 之後拼作 ieu，在聲母 ts \[ts\]、tsh \[tsʰ\]、dz \[dz\]、s \[s\]、z \[z\] 之後拼作 oe。
3. 對於同一個字的單字調，幾種資料有時會有出入，此時以湯版《寧波方言詞典》的記錄爲準。
4. 若某字在資料中的兩個讀音符合吳拼教程 [新老差異](https://shinzoqchiuq.github.io/gninpou-tutorial/内部差异/新老差异.html) 一節中提到的第 3 點到第 12 點。字表內只記錄其中的老派讀音。
5. 寧波城區老派口音僅有 7 個單字調，其中陽上併入了陽去。但在兩字組的前字位置，陽上陽去有所不同。陽上變爲 23，陽去變爲 22。字表中依據變調的不同將兩者分別標爲 4 和 6。注意這 **並不** 表示兩者的單字調有區別。對於單字調爲陽上陽去，且不出現在前字位置的那些字，字表中依照該字在中古的調類標註。這可能會導致一些錯誤，請使用者自行考量。
6. 每個字的字音所參考的資料標註在「出處」一欄。數字表示後面所列的 7 種 [參考資料](https://github.com/shinzoqchiuq/gninpou-dictionary#參考資料) 的編號。例如出處爲 1，則表示該字的字音來源於湯版《寧波方言詞典》。
7. 參考資料 6. 《鄞縣通志》和 7. 《The Ningpo Syllabary》記錄的是古寧波話。兩者的音系和現在的寧波話有不少差別。所以字表「出處」一欄標註爲 6 和 7 的字，讀音經過了推導。其中《The Ningpo Syllabary》原書不標註聲調，字表中的聲調參照中古的調類標註。無論字音的推導還是聲調的推導都可能存在錯誤，得到的讀音可能與時音不同。故若得到的字音與前 5 種資料有衝突，字表中將不記錄推導得到的讀音。但許多字不見於前 5 種資料，字表中便會記錄推導得到的讀音，對於這些字音的可信度，請使用者自行考量。
8. 一些字有舊讀和新讀，如「遲」舊讀 ji2，新讀 dzy2，「家」舊文讀 cio1，文讀 cia1。這類字，《The Ningpo Syllabary》中只有舊讀，字表中依照規律收錄了新讀，「出處」標記爲 0。當然，若在前5種資料中就有記錄新舊讀的，則依照前5種資料記錄。
9. 還有一少部分常見字不見於所有 7 種資料，字表中依照中古音推導得到現代音。另有一些新造的化學用字，字表依照讀半邊（如「氫」）或反切（如「羥」）的原則給這些字注音。這些字的「出處」一欄沒有標註，無法保證字音的可信度，使用者在採信時請仔細考慮。
10. 「清末」一欄標註的是《The Ningpo Syllabary》中記錄的字音。「字頻」一欄標註的是 [寧波話輸入法](https://github.com/NGLI/rime-wugniu_gninpou) 中使用的字頻。
11. 輸入法提供城區和鍾公廟兩種口音。字表爲了兼容鍾公廟，做了一些設置。一些字的吳拼用了大寫，表示這個字在兩地讀音不同。兩地的讀音差異見輸入法文檔的 [鄞县钟公庙（鄞县中区）](https://github.com/NGLI/rime-wugniu_gninpou/wiki/音系及拼音方案#鄞县钟公庙鄞县中区) 一節。如果僅需要城區口音，將這些大寫視爲小寫即可。具體可以參看 [兼容設置説明](兼容設置説明.md)。
12. 一些資料中出現的讀音，個人認爲有問題或不合適的，會在「篩選」一欄打上#號。這些讀音將不會出現在輸入法中。

## pure 版

上文 [說明](https://github.com/shinzoqchiuq/gninpou-dictionary#說明) 中第 5 條以及第 7 - 12 條提到，[`字表.tsv`](字表.tsv) 有諸多超出方言志和方言詞典的內容。如果使用者不需要這些內容，也可以查看文件 [`甬城.tsv`](甬城.tsv)。pure 版字表只收錄來自前 5 種 [參考資料](https://github.com/shinzoqchiuq/gninpou-dictionary#參考資料) 的字音，不區分陽上和陽去，也沒有爲兼容鍾公廟進行改動，更接近原始的參考資料。同時，pure 版字表也不提供字頻等用於輸入法的信息，僅僅提供繁體、简体、吳拼、出處和備註這五列信息。[吳語學堂](https://www.wugniu.com/) 中寧波話字音查詢的數據源便是這張表，網站上的查詢結果僅僅是在本表的基礎上加上了 IPA 一欄，刪去了出處一欄。

## 反饋

限於本人水平，字表中難免會有錯漏。如果使用者有任何問題或是發現了任何錯誤，歡迎提交 [issue](https://github.com/shinzoqchiuq/gninpou-dictionary/issues)，或是通過以下郵箱直接與我聯繫。

本人郵箱：shinzoqchiuq@outlook.com

## 參考資料

1. 湯珍珠、陳忠敏、吳新賢：《寧波方言詞典》，江蘇教育出版社，1997
2. 宁波市地方志编纂委员会：《宁波市志·方言》，中华书局，1995
3. 朱彰年、薛恭穆、周志锋、汪维辉：《阿拉宁波话(修订版)》，宁波出版社，2016
4. 朱彰年、薛恭穆、周志锋、汪维辉：《宁波方言词典》，汉语大辞典出版社，1996
5. 周志锋：《江苏教育版<宁波方言词典>词目用字问题》，方言 2008 年第一期
6. 《鄞縣通志·文獻志·方言》，鄞縣通志館，1951
7. P. G. von Möllendorff：《The Ningpo Syllabary》，Shanghai: American Presbyterian Mission Press，1901
8. 《镇海县志》编纂委员会：《镇海县志·方言》，中国大百科全书出版社上海分社，1994
9. 周志锋、胡方：《北仑方言》，中国文史出版社，2007
10. 方松熹：《舟山方言研究》，社会科学文献出版社，1993

