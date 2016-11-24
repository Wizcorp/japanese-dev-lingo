# Japanese Lingo for Developers

[To the word list!](#word-list)


## Introduction

Wizcorp is a company with a very diverse international group of developers who find themselves interacting with both
international and Japanese customers. To help improve our Japanese communication we have set up this technical glossary.
We try to collect words that one does not typically find in most (business) Japanese language curriculums, yet we find
useful on a regular basis. A lot of this is driven by the words we hear our customers use.

* Original concept and word list by [Almir Kadric](https://github.com/AlmirKadric/)
* Transformed to Markdown and open sourced by [Ron Korving](https://github.com/ronkorving/)


## Contributing

Contributions in the form of Pull Requests are very welcome! We would like to ask everyone to stick to some simple
guidelines though, to keep things consistent and avoid it exploding into a copy of the dictionary.

### Guidelines

* Please do not add words that appear in dictionaries but not in common interaction with Japanese companies.
* Please stick to the topics below. If you have a hard time identifying the topic, please mention it in your PR.
* Please make sure to add kana versions of the Japanese words you add to the list in the `Kana` column.
* If a word is already 100% kana, you should leave the `Kana` cell empty.
* If a word is a common suru-verb, please add `（する）` to the `Japanese` column.
* If the English translation is not enough to convey the full meaning, use the `Notes` column to elaborate.
* Don't try to align the columns in the markdown below, it's impossible.
* If some words are missing, but you don't know the Japanese yourself, feel free to request additions through an issue.


## Useful tools

* [jisho.org](http://www.jisho.org/): The best Japanese dictionary on the web.
* [RikaiChan](http://www.polarcloud.com/rikaichan/): A popup Japanese dictionary tool for Firefox.
* [RikaiKun](https://chrome.google.com/webstore/detail/rikaikun/jipdnfibhldikgcjhfnomkfpcebammhp): RikaiChan for Chrome.
* [Safarikai](https://github.com/ashchan/safarikai): RikaiChan for Safari.


## Word list

### Computer and Application Usage

English | Japanese | Kana | Notes
--------|----------|------|------
Computer | コンピュータ / コンピューター | |
Personal computer, PC | パソコン | |
User | ユーザ / ユーザー | |
Settings | 設定 | せってい |
Configuration | 構成 | こうせい |
To save | 保存（する） | ほぞん |
To input | 入力（する） | にゅうりょく |
To output | 出力（する） | しゅつりょく |
To boot / start | 起動（する） | きどう |
To reboot / restart | 再起動（する） | さいきどう |
To update | 更新（する） | こうしん |
To register | 登録（する） | とうろく |
To edit | 編集（する） | へんしゅう |
To delete / remove | 削除（する） | さくじょ |
Automatic | 自動 | じどう |
Screen | 画面 | がめん |
Video | 動画 | どうが |
To display | 表示（する） | ひょうじ |
To copy and paste | コピペ（する） | |


### Devices

English | Japanese | Kana | Notes
--------|----------|------|------
Device, terminal | 端末 | たんまつ | Smartphones, tablets, e-readers, command-line interfaces, etc
Japanese feature phone | ガラ携 | ガラけい | From ガラパゴス携帯電話
Smartphone | スマホ / スマートフォン | |


### Projects

English | Japanese | Kana | Notes
--------|----------|------|------
Plan / Project | 企画 | きかく |
Specification | 仕様 | しよう |
Specification document | 仕様書 | しようしょ |


### Software Development

English | Japanese | Kana | Notes
--------|----------|------|------
Development | 開発 | かいはつ |
Developer | 開発者 | かいはつしゃ |
Engineer | PG (プログラマ) | ぷろぐらまー | 
Development department | 開発部 | かいはつぶ |
Research and development, R&D | 開発研究 | けんきゅうかいはつ
Implementation | 実装 | じっそう |
Not implemented | 未実装 | みじっそう |
Not implemented (Should have been implemebted) | 実装漏れ | じっそうもれ | 
Design | 設計 | せっけい | Of code, infrastructure and systems, etc.
Feature | 機能 | きのう |
Execution | 実行 | じっこう | Of a function or program
Structure | 仕組み | しくみ | Eg. of code
Format | 形式 | けいしき | Eg. of data
Line | 〜行 | ぎょう | Eg. １３行 (line 13)
To indent | インデント（する） | |
foo / bar | ほげ / ほげほげ | |
To assign | 割り当てる | わりあてる | To a variable
To define | 定義（する） | ていぎ |
Type | 型 | かた | As in data type
Variable | 変数 | へんすう |
Argument | 引数 | ひきすう | To a function or program
Null | ヌル | |
Value | 値 | あたい |
Return value | 戻り値 | もどりち |
Function | 関数 | かんすう |
Inherit (from X) | （Xを）継承（する） | けいしょう |
Static | 静的 | せいてき |
Dynamic | 動的 | どうてき |
To optimize | 最適化（する） | さいてきか |
Regular expression | 正規表現 | せいきひょうげん |
Brackets, parentheses | 括弧 | かっこ |
Synchronous | 同期 | どうき |
Asynchronous | 非同期 | ひどうき |
To select | 選択（する） | せんたく |
To search | 検索（する） | けんさく |
To process | 処理（する）| しょり |
Revision number (git, application) | リビジョン番号 | リビジオンばんごう |
Object Oriented Programming (OOP) | オブジェクト指向 | オブジェクトしこう |
Functional Programming (FP) | 関数型プログラミング | かんすうがたプログラミング |
Artificial Intelligence (AI) | 人工知能 | じんこうちのう |


### Security

English | Japanese | Kana | Notes
--------|----------|------|------
Authentication | 認証 | にんしょう |
Authority / power | 権限 | けんげん |
Basic Auth | ベーシック認証 | べーシックにんしょう |
Cipher | 暗号 | あんごう |
Encryption | 暗号化 | あんごうか |
Cipher/encryption key | 暗号キー | あんごうキー
Countermeasure | 対策 | たいさく | Eg. against hackers


### Servers

English | Japanese | Kana | Notes
--------|----------|------|------
Server | サーバ / サーバー | |
Physical server | 物理サーバ | ぶつりサーバ |
Virtual server  | 仮想サーバ | かそうサーバ |
Virtual machine | 仮想マシン | かそうマシン |
Server layout / architecture | サーバ構成 | サーバこうせい |
Static IP | 固定IP | こていIP |
Load | 負荷 | ふか |


### Operations

English | Japanese | Kana | Notes
--------|----------|------|------
Operation | 運用 | うんよう |
Environment | 環境 | かんきょう |
Production version / release | 本番 | ほんばん |
Beta version | ベータ版 | ベータばん |
Closed beta | クローズドベータ | |
Front-end | フロントエンド | |
Management | 管理 | かんり | Of people, software, etc
Manager | 管理者 | かんりしゃ |
Infrastructure | インフラ | |
System administrator | インフラ |


### Business

English | Japanese | Kana | Notes
--------|----------|------|------
Sales / Business | 営業 | えいぎょう |
Executive, company official | 役員 | やくいん |
Chief technical officer | 最高技術責任者 | さいこうぎじゅつせきにんしゃ |
Our company | 弊社 | へいしゃ |
Your company | 御社 | おんしゃ |
Office | 事務所 | じむしょ |
In-house | 社内 | しゃない |
External / 3rd party | 外部 | がいぶ |
Contractor | 外注先 | がいちゅうさき |
Suspend, discontinue | 中止 | ちゅうし |
