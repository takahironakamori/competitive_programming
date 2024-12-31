# 問題一覧

過去に挑戦したAtCoder等の競技プログラミング問題を、分野別に一覧表に整理しています。
各分野を主観で入門と上級に分けています。また、各問題に対する分野も自分が解きやすい分野を選定しています。

<br>

## 目次

| 分野 | 主なアルゴリズム等 |
| --- | --- |
| [全探索【入門】](#section-01-a)| bit全探索、順列全探索 |
| [二分探索【入門】](#section-02-a)| 基本的な二分探索 |
| [並び替え【入門】](#section-03-a)| sort、比較関数を使った並び替え |
| [累積和【入門】](#section-04-a)| 基本的な累積和・いもす法 |
| [データ構造【入門】](#section-05-a)| Set、Stack、Deque、UnionFind、Priority Queue |
| [動的計画法【入門】](#section-06-a)| ナップサック、DP復元 |
| [グラフ【入門】](#section-07-a)| グラフ基礎、dfs、bfs、経路の列挙、閉路の距離、拡張ダイクストラ |
| [数学【入門】](#section-08-a)| 最大公約数、最小公倍数、約数、素数、N進法 |
| [総合問題【入門】](#section-09-a)|  |

| 分野 | 主なアルゴリズム等 |
| --- | --- |
| [考察テクニック](#section-10-b)| オーバーフロー、コーナーケース、円環等 |
| [全探索【上級】](#section-01-b)| bit全探索、しゃくとり法、半分全列挙、ランレングス圧縮 |
| [二分探索【上級】](#section-02-b)| 値で二分探索 |
| [累積和【上級】](#section-04-b)| 二次元累積和・いもす法 |
| [グラフ【上級】](#section-07-b)| バックトラック、ワーシャルフロイド、最小全域木、二部グラフ、強連結成分分解、最小共通祖先、最大流問題、最小費用流問題 |
| [データ構造【上級】](#section-05-b)| UnionFind、セグメント木、Fenwick Tree、遅延評価セグメント木、ハッシュ、ダブリング、平面走査 |
| [動的計画法【上級】](#section-06-b)| bitDP、木DP、区間DP、期待値DP、セグメント木を使ったDP |
| [数学【上級】](#section-09-b)| 組み合わせ、偏角ソート、行列、期待値 |
| [ゲーム【上級】](#section-11-b)| Nim |
| [総合問題【上級】](#section-09-b)|  |
| [ヒューリスティック](#section-12-b)| 焼きなまし法、ビームサーチ |

<br>

<a id="section-01-a"></a>
## 全探索【入門】

### bit全探索

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-002 Encyclopedia of Parentheses](https://atcoder.jp/contests/typical90/tasks/typical90_b) | |
| [ABC384-C Perfect Standings](https://atcoder.jp/contests/abc384/tasks/abc384_c) | |

### 順列全探索

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-032 AtCoder Ekiden](https://atcoder.jp/contests/typical90/tasks/typical90_af) | |

<br>

<a id="section-02-a"></a>
## 二分探索【入門】

| 問題名 | メモ |
| --- | --- |
| | |

<br>

<a id="section-03-a"></a>
## 並び替え【入門】

| 問題名 | メモ |
| --- | --- |
| | |

<br>

<a id="section-04-a"></a>
## 累積和【入門】

| 問題名 | メモ |
| --- | --- |
| | |

<br>

<a id="section-05-a"></a>
## データ構造【入門】

### Set

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-027 Sign Up Requests](https://atcoder.jp/contests/typical90/tasks/typical90_aa) | |

### Stack

| 問題名 | メモ |
| --- | --- |
| [ABC189-C Mandarin Orange](https://atcoder.jp/contests/abc189/tasks/abc189_c) | |

### Queue,Deque

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-061 Deck](https://atcoder.jp/contests/typical90/tasks/typical90_bi) | |
| [ABC379-D Home Garden](https://atcoder.jp/contests/abc379/tasks/abc379\_d) | |

### Union-Find

| 問題名 | メモ |
| --- | --- |
| [ATC001-B UnionFind](https://atcoder.jp/contests/atc001/tasks/unionfind_a) | |
| [競プロ典型90問-012 RedPainting](https://atcoder.jp/contests/typical90/tasks/typical90_l) | |

### Priority Queue

| 問題名 | メモ |
| --- | --- |
| [ABC217-E Sorting Queries](https://atcoder.jp/contests/abc217/tasks/abc217_e) | |

<br>

<a id="section-06-a"></a>
## 動的計画法【入門】

### 基礎

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A16 Dungeon 1](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_p) | |
| [EDPC-A Frog 1](https://atcoder.jp/contests/dp/tasks/dp_a) | |
| [EDPC-B Frog 2](https://atcoder.jp/contests/dp/tasks/dp_b) | |
| [EDPC-C Vacation](https://atcoder.jp/contests/dp/tasks/dp_c) | |
| [TDPC-A - コンテスト](https://atcoder.jp/contests/tdpc/tasks/tdpc_contest) | |

### 中級

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A17 Dungeon 2](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_q) | 経路の復元 |
| [競プロ鉄則-B17 Frog 1 with Restoration](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_cp) | 経路の復元 |
| [競プロ典型90問-050 Stair Jump](https://atcoder.jp/contests/typical90/tasks/typical90_ax) | |
| [EDPC-D Knapsack 1](https://atcoder.jp/contests/dp/tasks/dp_d) | |
| [EDPC-E Knapsack 2](https://atcoder.jp/contests/dp/tasks/dp_e) | |

### LCS

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A20 LCS](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_t) |  |
| [EDPC-F LCS](https://atcoder.jp/contests/dp/tasks/dp_f) | 復元 |

<br>

<a id="section-07-a"></a>
## グラフ【入門】

### DFS

| 問題名 | メモ |
| --- | --- |
| [ABC378-D Count Simple Paths](https://atcoder.jp/contests/abc378/tasks/abc378_d) | |
| [競プロ鉄則-B65 Road to Promotion Hard](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_el) | |
| [ABC378-D Count Simple Paths](https://atcoder.jp/contests/abc378/tasks/abc378_d) | 経路の列挙 |

### BFS

| 問題名 | メモ |
| --- | --- |
| [ABC376-D Cycle](https://atcoder.jp/contests/abc376/tasks/abc376_d) | 閉路の最短距離 |
| [ABC383-C Humidifier 3](https://atcoder.jp/contests/abc383/tasks/abc383_c) | 複数点でスタートするBFS |

### 拡張ダイクストラ

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-043 Maze Challenge with Lack of Sleep](https://atcoder.jp/contests/typical90/tasks/typical90_aq) |  |

<br>

<a id="section-08-a"></a>
## 数学【入門】

### 最大公約数・最小公倍数

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-022 Cubic Cake](https://atcoder.jp/contests/typical90/tasks/typical90_v) |  |
| [競プロ典型90問-038 Large LCM](https://atcoder.jp/contests/typical90/tasks/typical90_al) |  |

### 約数列挙

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-085 Multiplication 085](https://atcoder.jp/contests/typical90/tasks/typical90_cg) |  |

### 素数列挙

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-030 K Factors](https://atcoder.jp/contests/typical90/tasks/typical90_ad) |  |
| [ABC383-D 9 Divisors](https://atcoder.jp/contests/abc383/tasks/abc383_d) |  |

### 素因数分解

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-075 Magic For Balls](https://atcoder.jp/contests/typical90/tasks/typical90_bw) |  |

### 数式を変形する

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-052 Dice Product](https://atcoder.jp/contests/typical90/tasks/typical90_az) |  |

### N進法

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-067 Base 8 to 9](https://atcoder.jp/contests/typical90/tasks/typical90_bo) |  |

### 階差

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-064 Uplift](https://atcoder.jp/contests/typical90/tasks/typical90_bl) |  |

### 組み合わせの計算(繰り返し二乗法)

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-069 Colorful Blocks 2](https://atcoder.jp/contests/typical90/tasks/typical90_bq) |  |

<br>

<a id="section-09-a"></a>
## 総合問題【入門】

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A71 Homework](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_bs) | |
| [競プロ鉄則-A72 Tile Painting](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_bt) | |
| [競プロ鉄則-A73 Marathon Route](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_bu) | |
| [競プロ鉄則-A74 Board Game](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_bv) | |

<br>

<a id="section-10-b"></a>
## 考察テクニック

### オーバーフロー

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-055 Select 5](https://atcoder.jp/contests/typical90/tasks/typical90_bc) | |

### コーナーソース

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-033 Not Too Bright](https://atcoder.jp/contests/typical90/tasks/typical90_ag) | |

### 見かけ上の変化をメモ

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-044 Shift and Swapping](https://atcoder.jp/contests/typical90/tasks/typical90_ar) | |

### ソートして貪欲法

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-014 We Used to Sing a Song Together](https://atcoder.jp/contests/typical90/tasks/typical90_n) | |
| [ABC376-C Prepare Another Box](https://atcoder.jp/contests/abc376/tasks/abc376_c) | |

### 円環

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-076 Cake Cut](https://atcoder.jp/contests/typical90/tasks/typical90_bx) | |
| [ABC384-D Repeated Sequence](https://atcoder.jp/contests/abc384/tasks/abc384_d) | 円環、しゃくとり法 |

### 辞書順最小は前から貪欲法

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-006 Smallest Subsequence](https://atcoder.jp/contests/typical90/tasks/typical90_f) | |

### 偶奇を考える

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A36 Travel](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_aj) | |
| [競プロ鉄則-B36 Switching Lights](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_di) | |

### 部分問題に分解する

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-082 Counting Numbers](https://atcoder.jp/contests/typical90/tasks/typical90_cd) | |

### 足された回数を考える

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A37 Travel 2](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_ak) | |
| [競プロ鉄則-B37 Sum of Digits](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_dj) | |

### 上限値・下限値を考える

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A38 Black Company 1](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_al) | |
| [競プロ鉄則-B38 Height of Grass](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_dk) | |
| [競プロ典型90問-048 I will not drop out](https://atcoder.jp/contests/typical90/tasks/typical90_av) | |

### 一手先を考える

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A39 Interval Scheduling Problem](https://atcoder.jp/contests/tessoku-book/tasks/math_and_algorithm_bn) | |
| [競プロ鉄則-B39 Taro's Job](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_dl) | |

### 個数を考える

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A40 Triangle](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_an) | |
| [競プロ鉄則-B40 Divide by 100](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_dm) | |
| [競プロ典型90問-046 I Love 46](https://atcoder.jp/contests/typical90/tasks/typical90_at) | |

### うしろから考える、両側から考える

| 問題名 | メモ |
| --- | --- |
| [ABC040-D 道路の老朽化対策について](https://atcoder.jp/contests/abc040/tasks/abc040_d) | |
| [ABC120-D Decayed Bridges](https://atcoder.jp/contests/abc120/tasks/abc120_d) | |
| [競プロ鉄則-A41 Tile Coloring](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_ao) | |
| [競プロ鉄則-B41 Reverse of Euclid](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_dn) | |
| [競プロ典型90問-060 Chimera](https://atcoder.jp/contests/typical90/tasks/typical90_bh) | |
| [競プロ典型90問-062 Paint All](https://atcoder.jp/contests/typical90/tasks/typical90_bj) | |
| [第四回アルゴリズム実技検定過去問-M 筆塗り](https://atcoder.jp/contests/past202010-open/tasks/past202010_m) | |

### 固定して考える

| 問題名 | メモ |
| --- | --- |
| [ABC085-C Otoshidama](https://atcoder.jp/contests/abc085/tasks/abc085_c) | |
| [ABC077-C Snuke Festival](https://atcoder.jp/contests/abc077/tasks/arc084_a) | |
| [競プロ鉄則-A42 Soccer](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_ap) | |
| [競プロ鉄則-B42 Two Faced Cards](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_do) | |
| [第八回アルゴリズム実技検定過去問-M バランス](https://atcoder.jp/contests/past202109-open/tasks/past202109_m) | |
| [ABC385-C Illuminate Buildings](https://atcoder.jp/contests/abc385/tasks/abc385_c) | |

### 問題を言い換える

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A43 Travel 3](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_aq) | |
| [競プロ鉄則-B43 Quiz Contest](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_dp) | |
| [競プロ典型90問-049 Flip Digits 2](https://atcoder.jp/contests/typical90/tasks/typical90_aw) | |

### 周期を考える

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-058 Original Calculator](https://atcoder.jp/contests/typical90/tasks/typical90_bf) | |
| [ABC384-D Repeated Sequence](https://atcoder.jp/contests/abc384/tasks/abc384_d) | 円環、しゃくとり法 |

### データの持ち方を工夫する

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A44 Change and Reverse](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_ar) | |
| [競プロ鉄則-B44 Grid Operations](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_dq) | |
| [ABC382-C Kaiten Sushi](https://atcoder.jp/contests/abc382/tasks/abc382_c) | |
| [ABC379-D Home Garden](https://atcoder.jp/contests/abc379/tasks/abc379\_d) | 計算量の見積もり |

### 不変量に着目する

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A45 Card Elimination](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_as) | |
| [競プロ鉄則-B45 Blackboard 2](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_dr) | |
| [競プロ典型90問-074 ABC String 2](https://atcoder.jp/contests/typical90/tasks/typical90_bv) | |

### 答えへの貢献度を考える（主客転倒）

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-039 Tree Distance](https://atcoder.jp/contests/typical90/tasks/typical90_am) | |

### クエリ先読み

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-068 Paired Information](https://atcoder.jp/contests/typical90/tasks/typical90_bp) | |

### XとYを独立で考える, 操作順序を気にしない、bitごと独立で考える

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-070 Plant Planning](https://atcoder.jp/contests/typical90/tasks/typical90_br) | |
| [競プロ典型90問-079 Two by Two](https://atcoder.jp/contests/typical90/tasks/typical90_ca) | |
| [競プロ典型90問-086 Snukes Favorite Arrays](https://atcoder.jp/contests/typical90/tasks/typical90_ch) | |

### 鳩ノ巣原理

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-088 Similar but Different Ways](https://atcoder.jp/contests/typical90/tasks/typical90_cj) | |

<br>

<a id="section-01-b"></a>
## 全探索【上級】

### bit全探索

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-063 Monochromatic Subgrid](https://atcoder.jp/contests/typical90/tasks/typical90_bk) | |

### しゃくとり法

| 問題名 | メモ |
| --- | --- |
| [ABC032-C 列](https://atcoder.jp/contests/abc032/tasks/abc032_c) | |
| [ABC229-D Longest X](https://atcoder.jp/contests/abc229/tasks/abc229_d) | |
| [競プロ典型90問-034 There Are Few Types Of Elements](https://atcoder.jp/contests/typical90/tasks/typical90_ah) | |
| [ABC377-D Many Segments 2](https://atcoder.jp/contests/abc377/tasks/abc377_d) | |
| [ABC381-D 1122 Substring](https://atcoder.jp/contests/abc381/tasks/abc381_d) | |
| [ABC382-C Kaiten Sushi](https://atcoder.jp/contests/abc382/tasks/abc382_c) | しゃくとり法で前計算 |
| [ABC384-D Repeated Sequence](https://atcoder.jp/contests/abc384/tasks/abc384_d) | 円環、しゃくとり法 |

### 再帰

| 問題名 | メモ |
| --- | --- |
| [ABC382-D Keep Distance](https://atcoder.jp/contests/abc382/tasks/abc382_d) | 枝刈りして全探索 |

### 半分全列挙

| 問題名 | メモ |
| --- | --- |
| プログラミングコンテストチャレンジブック第2版 147頁『4 Values whose Sum is 0』 | |
| [ABC381-D 1122 Substring](https://atcoder.jp/contests/abc381/tasks/abc381_d) | |
| プログラミングコンテストチャレンジブック第2版 148頁『巨大ナップサック』 | |
| [競プロ典型90問-051 Typical Shop](https://atcoder.jp/contests/typical90/tasks/typical90_ay) | |

### ランレングス圧縮

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-084 There are two types of characters](https://atcoder.jp/contests/typical90/tasks/typical90_cf) | |

<br>

<a id="section-02-b"></a>
## 二分探索【上級】

### 二分探索

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-007 CPClasses](https://atcoder.jp/contests/typical90/tasks/typical90_g) | |

### 値で二分探索

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-001 Yokan Party](https://atcoder.jp/contests/typical90/tasks/typical90_a) | |
| [競プロ典型90問-087 Chokuda is Demand](https://atcoder.jp/contests/typical90/tasks/typical90_ci) | |

<br>

<a id="section-04-b"></a>
## 累積和【上級】

### 累積和

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-004 Cross Sum](https://atcoder.jp/contests/typical90/tasks/typical90_d) | |
| [競プロ典型90問-010 Score Sum Queries](https://atcoder.jp/contests/typical90/tasks/typical90_j) | |

### 二次元累積和

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-081 Friendly Group](https://atcoder.jp/contests/typical90/tasks/typical90_cc) | |

<br>

<a id="section-07-b"></a>
## グラフ【上級】

### dfs、バックトラック

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-072 Loop Railway Plan](https://atcoder.jp/contests/typical90/tasks/typical90_bt) | |
| [競プロ典型90問-088 Similar but Different Ways](https://atcoder.jp/contests/typical90/tasks/typical90_cj) | |

### トポロジカルソート

| 問題名 | メモ |
| --- | --- |
| [EDPC-G Longest Path](https://atcoder.jp/contests/dp/tasks/dp_g) |  |

### ワーシャルフロイド

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-087 Chokuda is Demand](https://atcoder.jp/contests/typical90/tasks/typical90_ci) | |

### 最小全域木

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A67 MST](https://atcoder.jp/contests/typical90/tasks/typical90_ci) | |
| [競プロ鉄則-B67 Max MST](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_en) |  |
| [競プロ典型90問-049 Flip Digits 2](https://atcoder.jp/contests/typical90/tasks/typical90_aw) |  |

### 二部グラフ

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-026 Independent Setona Tree](https://atcoder.jp/contests/typical90/tasks/typical90_z) |  |
| [CODEFESTIVAL 2017 qualB-C 3 Steps](https://atcoder.jp/contests/code-festival-2017-qualb/tasks/code_festival_2017_qualb_c) |  |

### 強連結成分分解（SCC）

| 問題名 | メモ |
| --- | --- |
| [ALPC-G SCC](https://atcoder.jp/contests/practice2/tasks/practice2_g) |  |
| [競プロ典型90問-021 Come Back in One Piece](https://atcoder.jp/contests/typical90/tasks/typical90_u) |  |

### 最小共通祖先（LCA）

| 問題名 | メモ |
| --- | --- |
| [典型アルゴリズム問題集 上級〜エキスパート編-D 最小共通祖先](https://atcoder.jp/contests/pastbook2022/tasks/pastbook2022_d) |  |
| [第一回アルゴリズム実技検定過去問-K 巨大企業](https://atcoder.jp/contests/past201912-open/tasks/past201912_k) |  |
| [ABC040-D 道路の老朽化対策について](https://atcoder.jp/contests/abc040/tasks/abc040_d) |  |
| [第四回アルゴリズム実技検定過去問-M 筆塗り](https://atcoder.jp/contests/past202010-open/tasks/past202010_m) |  |

### グラフ構造に工夫を

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-054 Takahashi Number](https://atcoder.jp/contests/typical90/tasks/typical90_bb) |  |

### 最大流問題

| 問題名 | メモ |
| --- | --- |
| [典型アルゴリズム問題集 上級〜エキスパート編-E 最大流](https://atcoder.jp/contests/pastbook2022/tasks/pastbook2022_e) |  |
| [ABC205-F Gridand Tokens](https://atcoder.jp/contests/abc205/tasks/abc205_f) |  |

### 二部マッチング問題

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A69 Bipartite Matching](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_bq) |  |
| [競プロ鉄則-B69 Black Company 2](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_ep) |  |

### 最小費用流問題

| 問題名 | メモ |
| --- | --- |
| [典型アルゴリズム問題集 上級〜エキスパート編-F 最小費用流問題](https://atcoder.jp/contests/pastbook2022/tasks/pastbook2022_f) |  |
| [第三回アルゴリズム実技検定過去問-O 輪投げ](https://atcoder.jp/contests/past202005-open/tasks/past202005_o) |  |
| [第八回アルゴリズム実技検定過去問-K ニワトリのお見合い](https://atcoder.jp/contests/past202109-open/tasks/past202109_k) |  |
| [第七回アルゴリズム実技検定過去問-M 分割](https://atcoder.jp/contests/past202107-open/tasks/past202107_m) |  |

<br>

<a id="section-05-b"></a>
## データ構造【上級】

### map,set

| 問題名 | メモ |
| --- | --- |
| [ABC385-D Santa Claus 2](https://atcoder.jp/contests/abc385/tasks/abc385_d) | |

### Union-Find

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-068 Paired Information](https://atcoder.jp/contests/typical90/tasks/typical90_bp) | |
| [ARC065-D 連結](https://atcoder.jp/contests/arc065/tasks/arc065_b) | |
| [ABC040-D 道路の老朽化対策について](https://atcoder.jp/contests/abc040/tasks/abc040_d)| |
| [ABC097-D Equals](https://atcoder.jp/contests/abc097/tasks/arc097_b)| |
| [CODEFESTIVAL 2017 qualB-C 3 Steps](https://atcoder.jp/contests/code-festival-2017-qualb/tasks/code_festival_2017_qualb_c)| |
| [ABC120-D Decayed Bridges](https://atcoder.jp/contests/abc120/tasks/abc120_d)| |
| [ARC036-D 偶数メートル](https://atcoder.jp/contests/arc036/tasks/arc036_d)| |
| [第四回アルゴリズム実技検定過去問-M 筆塗り](https://atcoder.jp/contests/past202010-open/tasks/past202010_m)| |

### 木（部分木）

| 問題名 | メモ |
| --- | --- |
| [ABC385-E Snowflake Tree](https://atcoder.jp/contests/abc385/tasks/abc385_e) | 部分木のサイズを効率的に計算する |

### 完全二分木

| 問題名 | メモ |
| --- | --- |
| [ABC380-D Strange Mirroring](https://atcoder.jp/contests/abc380/tasks/abc380_d) | 左右どっちに進んだのかを数える |
| [ABC220-E Distance on Large Perfect Binary Tree](https://atcoder.jp/contests/abc220/tasks/abc220_e) | パスの数を数える |

### セグメント木

| 問題名 | メモ |
| --- | --- |
| [典型アルゴリズム問題集 上級〜エキスパート編-G 一点更新・区間最小値](https://atcoder.jp/contests/pastbook2022/tasks/pastbook2022_g) | |
| [ALPC-J Segment Tree](https://atcoder.jp/contests/practice2/tasks/practice2_j) | |
| [競プロ鉄則-A58 RMQ](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_bf) | |
| [競プロ鉄則-B58 Jumping](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_ee) | |
| [競プロ鉄則-A59 RSQ](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_bg) | |
| [競プロ鉄則-B59 Number of Inversions](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_ef) | |
| [ABC190-F Shift and Inversions](https://atcoder.jp/contests/abc190/tasks/abc190_f) | |
| [ABC185-F Range Xor Query](https://atcoder.jp/contests/abc185/tasks/abc185_f) | |
| [ABC217-D Cutting Woods](https://atcoder.jp/contests/abc217/tasks/abc217_d) | |

### Fenwick Tree

| 問題名 | メモ |
| --- | --- |
| [ALPC-B Fenwick Tree](https://atcoder.jp/contests/practice2/tasks/practice2_b) | |

### 遅延評価セグメント木

| 問題名 | メモ |
| --- | --- |
| [典型アルゴリズム問題集 上級〜エキスパート編-H 区間加算・区間最小値](https://atcoder.jp/contests/pastbook2022/tasks/pastbook2022_h) | |
| [ACLBeginnerContest-E Replace Digits](https://atcoder.jp/contests/abl/tasks/abl_e) | |
| [ALPC-K Range Affine Range Sum](https://atcoder.jp/contests/practice2/tasks/practice2_k) | |
| [ALPC-L Lazy Segment Tree](https://atcoder.jp/contests/practice2/tasks/practice2_l) | |

### 文字列のハッシュ

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A56 StringHash](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_bd) | |
| [競プロ鉄則-B56 PalindromeQueries](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_ec) | |

### ダブリング

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A57 Doubling](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_be) | |
| [競プロ鉄則-B57 Calculator](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_ed) | |

### 平面走査

| 問題名 | メモ |
| --- | --- |
| [ABC038-D プレゼント](https://atcoder.jp/contests/abc038/tasks/abc038_d) | |
| [ABC174-F Range Set Query](https://atcoder.jp/contests/abc174/tasks/abc174_f) | |
| [第二回アルゴリズム実技検定過去問-N ビルの建設](https://atcoder.jp/contests/past202004-open/tasks/past202004_n) | |
| [第七回アルゴリズム実技検定過去問-N モノクロデザイン](https://atcoder.jp/contests/past202107-open/tasks/past202107_n) | |

<br>

<a id="section-06-b"></a>
## 動的計画法【上級】

### 未分類

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-008 AtCounter](https://atcoder.jp/contests/typical90/tasks/typical90_h) | |
| [競プロ典型90問-011 Gravy Jobs](https://atcoder.jp/contests/typical90/tasks/typical90_k) | |
| [EDPC-G Longest Path](https://atcoder.jp/contests/dp/tasks/dp_g) |  |
| [第二回アルゴリズム実技検定過去問-K 括弧](https://atcoder.jp/contests/past202004-open/tasks/past202004_k) | |
| [典型アルゴリズム問題集 上級〜エキスパート編-A 区間分割の仕方を最適化する問題](https://atcoder.jp/contests/pastbook2022/tasks/pastbook2022_a) | |
| [JOI本選2016-A オレンジの出荷](https://atcoder.jp/contests/joi2016ho/tasks/joi2016ho_a) | |
| [典型アルゴリズム問題集 上級〜エキスパート編-B 編集距離](https://atcoder.jp/contests/pastbook2022/tasks/pastbook2022_b) | |
| [EDPC-N Slimes](https://atcoder.jp/contests/dp/tasks/dp_nx) | |
| [TDPC-I イウィ](https://atcoder.jp/contests/tdpc/tasks/tdpc_iwi) | |
| [典型アルゴリズム問題集 C 巡回セールスマン問題](https://atcoder.jp/contests/typical-algorithm/tasks/typical_algorithm_c) | |
| [JOI予選2017-D ぬいぐるみの整理](https://atcoder.jp/contests/joi2017yo/tasks/joi2017yo_d) | |
| [EDPC-O Matching](https://atcoder.jp/contests/dp/tasks/dp_o) | |
| [JOI春合宿2010-stairs 階段](https://atcoder.jp/contests/joisc2010/tasks/joisc2010_stairs) | |
| [EDPC-M Candies](https://atcoder.jp/contests/dp/tasks/dp_m) | |
| [EDPC-R Walk](https://atcoder.jp/contests/dp/tasks/dp_r) | |
| [TDPC-M 家](https://atcoder.jp/contests/tdpc/tasks/tdpc_house) | |
| [第六回アルゴリズム実技検定過去問-N 活動](https://atcoder.jp/contests/past202104-open/tasks/past202104_n) | |
| [EDPC-X Tower](https://atcoder.jp/contests/dp/tasks/dp_x) | |
| [典型アルゴリズム問題集 上級〜エキスパート編-C 各部分木の大きさ](https://atcoder.jp/contests/pastbook2022/tasks/pastbook2022_c) | |
| [EDPC-P Independent Set](https://atcoder.jp/contests/dp/tasks/dp_p) | |
| [EDPC-S Digit Sum](https://atcoder.jp/contests/dp/tasks/dp_s) | |
| [EDPC-U Grouping](https://atcoder.jp/contests/dp/tasks/dp_u) | |
| [EDPC-T Permutation](https://atcoder.jp/contests/dp/tasks/dp_t) | |

### DP(上級)

| 問題名 | メモ |
| --- | --- |
| [TDPC-F 準急](https://atcoder.jp/contests/tdpc/tasks/tdpc_semiexp) |  |
| [TDPC-G 辞書順](https://atcoder.jp/contests/tdpc/tasks/tdpc_lexicographical) |  |
| [TDPC-H ナップザック](https://atcoder.jp/contests/tdpc/tasks/tdpc_knapsack) |  |

### 桁DP

| 問題名 | メモ |
| --- | --- |
| [TDPC-E 数](https://atcoder.jp/contests/tdpc/tasks/tdpc\_number) |  |

### 完全二分木とDP

| 問題名 | メモ |
| --- | --- |
| [TDPC-C トーナメント](https://atcoder.jp/contests/tdpc/tasks/tdpc_tournament) |  |

### LCS(上級)

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-B20 Edit Distance](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_cs) |  |

### 素因数分解とDP

| 問題名 | メモ |
| --- | --- |
| [TDPC-D サイコロ](https://atcoder.jp/contests/tdpc/tasks/tdpc_dice) |  |

### 確率とDP

| 問題名 | メモ |
| --- | --- |
| [EDPC-I Coins](https://atcoder.jp/contests/dp/tasks/dp_i) |  |

### 期待値とDP

| 問題名 | メモ |
| --- | --- |
| [EDPC-J Sushi](https://atcoder.jp/contests/dp/tasks/dp_j) |  |

### ゲームとDP

| 問題名 | メモ |
| --- | --- |
| [EDPC-K Stones](https://atcoder.jp/contests/dp/tasks/dp_k) |  |

### 最長増加部分列

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-060 Chimera](https://atcoder.jp/contests/typical90/tasks/typical90_bh) | |

### DP復元

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-056 Lucky Bag](https://atcoder.jp/contests/typical90/tasks/typical90_bd) | |

### bitDP

| 問題名 | メモ |
| --- | --- |
| [JOI予選2014-D 部活のスケジュール表](https://atcoder.jp/contests/joi2014yo/tasks/joi2014yo_d) | |
| [競プロ典型90問-045 Simple Grouping](https://atcoder.jp/contests/typical90/tasks/typical90_as) | |
| [TDPC-J ボール](https://atcoder.jp/contests/tdpc/tasks/tdpc_ball) |  |

### 区間DP

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A21 Block Game](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_u) | |
| [競プロ鉄則-B21 Longest Subpalindrome](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_ct) | |
| [競プロ典型90問-019 Pick Two](https://atcoder.jp/contests/typical90/tasks/typical90_s) | |

### 木DP

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A65 Road to Promotion](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_bm) | |
| [競プロ典型90問-073 We Need Bothaandb](https://atcoder.jp/contests/typical90/tasks/typical90_bu) | |

### BITとDP

| 問題名 | メモ |
| --- | --- |
| [EDPC-Q Flowers](https://atcoder.jp/contests/dp/tasks/dp_q) | |

### 組み合わせの計算とDP

| 問題名 | メモ |
| --- | --- |
| [EDPC-W Intervals](https://atcoder.jp/contests/dp/tasks/dp_w) | |
| [EDPC-Y_Grid2](https://atcoder.jp/contests/dp/tasks/dp_y) | |

### セグメント木を使ったDP

| 問題名 | メモ |
| --- | --- |
| [第八回アルゴリズム実技検定過去問-N ジグザグな数列](https://atcoder.jp/contests/past202109-open/tasks/past202109_n) | |
| [第四回アルゴリズム実技検定過去問-O 宝箱](https://atcoder.jp/contests/past202010-open/tasks/past202010_o) | |
| [競プロ典型90問-037 Don't Leave the Spice](https://atcoder.jp/contests/typical90/tasks/typical90_ak) | |
| [第七回アルゴリズム実技検定過去問-O_コンピュータ](https://atcoder.jp/contests/past202107-open/tasks/past202107_o) | |

### 全方位木DP

| 問題名 | メモ |
| --- | --- |
| [EDPC-V Subtree](https://atcoder.jp/contests/dp/tasks/dp_v) | |
| [ABC348-E Minimize Sum of Distances](https://atcoder.jp/contests/abc348/tasks/abc348_e) | |

### ConvexHullTrick

| 問題名 | メモ |
| --- | --- |
| [EDPC-Z Frog 3](https://atcoder.jp/contests/dp/tasks/dp_z) | |

<br>

<a id="section-09-b"></a>
## 数学【上級】

### 組み合わせ

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-015 Don't be too close](https://atcoder.jp/contests/typical90/tasks/typical90_o) | |

### 偏角ソート

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-009 Three Point Angle](https://atcoder.jp/contests/typical90/tasks/typical90_i) | |

### マンハッタン距離

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-036 Max Manhattan Distance](https://atcoder.jp/contests/typical90/tasks/typical90_aj) | |

### xの倍数の性質

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-042 Multiple of 9](https://atcoder.jp/contests/typical90/tasks/typical90_ap) | |

### 行列の掃き出し法

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-057 Flip Flap](https://atcoder.jp/contests/typical90/tasks/typical90_be) | |

### 期待値の線形性

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-066 VariousArrays](https://atcoder.jp/contests/typical90/tasks/typical90_bn) | |

### 包除原理

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-080 Let's Share Bit](https://atcoder.jp/contests/typical90/tasks/typical90_cb) | |

### 平方分割

| 問題名 | メモ |
| --- | --- |
| [競プロ典型90問-083 Colorful Graph](https://atcoder.jp/contests/typical90/tasks/typical90_ce) | |

<br>

<a id="section-11-b"></a>
## ゲーム【上級】

| 問題名 | メモ |
| --- | --- |
| プログラミングコンテストチャレンジブック第2版 272頁『コインのゲーム』 |  |
| プログラミングコンテストチャレンジブック第2版 273頁『A Funny Game』 |  |
| プログラミングコンテストチャレンジブック第2版 275頁『Euclid's Game』 |  |
| プログラミングコンテストチャレンジブック第2版 277頁『Nim』 |  |
| プログラミングコンテストチャレンジブック第2版 278頁『Georgia and Bob』 |  |
| プログラミングコンテストチャレンジブック第2版 278頁『Georgia and Bob』 |  |
| プログラミングコンテストチャレンジブック第2版 281頁『コインのゲーム2』 |  |
| プログラミングコンテストチャレンジブック第2版 283頁『Cutting Game』 |  |
| [競プロ典型90問-031 VS AtCoder](https://atcoder.jp/contests/typical90/tasks/typical90_ae) | |

<br>

<a id="section-09-b"></a>
## 総合問題【上級】

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A75 Examination](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_bw) | |
| [競プロ鉄則-A76 River Crossing](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_bx) | |

<br>

<a id="section-12-b"></a>
## ヒューリスティック

| 問題名 | メモ |
| --- | --- |
| [競プロ鉄則-A75 Examination](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_bw) | |
| [競プロ鉄則-A76 River Crossing](https://atcoder.jp/contests/tessoku-book/tasks/tessoku_book_bx) | |
