---
marp: true

style: |
    {
            font-family:"Noto Sans JP",sans-serif;
        footer {
            text-align: center; /* フッター内のコンテンツを中央寄せ */
            width: 100%; /* フッター要素の幅をスライド全体に広げる */
            position: fixed; /* フッターを絶対配置にする（テーマによっては不要な場合も） */
            bottom: 15px; /* 下端に配置 */
            left: 0; /* 左端に配置 */
            }

        footer img {
            display: block; /* 画像をブロック要素にする */
            margin: 0 auto; /* 左右マージンを自動調整して中央寄せ */
            height: 13px; /* 画像の高さ */
        }
        section {
            width: 1280px;
            height: 720px;
            justify-content: start;
        }

        section::after {
            position: fixed;
            text-align: right;
            width: 30px;
            right: 50px;
            bottom: 25px;
            color: white;
        }

        .head{
            display: block;
            margin: 0 auto;
            text-align: center;
            padding: 5px;
            size: 20px;
        }

        .headMain{
            background-color: black;
            color: white;
            width: auto;
            padding: 5px;
            font-size: 50px;        
            margin-bottom: 20px;
        }

        .headSub{
            background-color: white;
            text-align: center;
            width: 50%;
            padding: 1px;
            size: 15px;
        }

        .icon{
            position: absolute;
            size: 10%;
            top: 60px;
            left: 820px;
        }

        .title{
            margin: 0 auto;
            text-align: center;
            width: 70%; 
            padding: 10px;
        }

        .titleMain{
            font-size: 60px;
            border: 5px, solid, #921;
            font-weight: bold;
            color: #AA0000;
        }
        .titleSub{
            margin: 0 auto;
            margin-top: 20px;
            text-align: center;
        }

        .slideTop{
            font-size: 40px;
            position: fixed;
            top: 30px;
            left: 110px;
            font-weight: bold;
        }
        
        .agenda td{
            border:solid 0px;
        }
        table{
            border-collapse: separate; 
            border-spacing: 20px;
        }

        .agenda th{
            background-color: #AA0000;
            width:8%;
            color:white;
            font-size: 40px;
        }

        .agenda td:nth-of-type(1){
            background-color: whitesmoke;
            width:82%;
        }
        .agenda td:nth-of-type(2){
            background-color: whitesmoke;
            width:10%;

        }
    }

headingDivider: 1 
---
<!-- 
footer: <img src="images/footer.png" >
-->

![bg fit](images/toppage.png)
<span class="icon">![h:80](images/CONFIDENTIAL.png)</span>
<div class="head" style="color:white;">株式会社XXXXXXX　御中</div>
<div class="head headMain">プロジェクトプロジェクトプロジェクト</br>キックオフ資料</div>
<div class="head headSub">XXXX/XX/XX</div>

---
<!--
footer: <img>
backgroundImage: url(images/base.png)
backgroundSize: cover
paginate: true
-->
<div class="slideTop">本日のゴール</div>

* プロジェクトチームのメンバー/役割紹介
* プロジェクトの内容やスコープに関して、共通の認識を形成する
* 背景、状況の確認
    * 現段階でお伺いしたい内容のヒアリング
* プロジェクト進行方法の確認
* Next Actionの確認

---
<div class="slideTop">アジェンダ</div>
</br>

1. プロジェクト概要
    1. メンバー紹介
    2. 事前情報の整理
    3. プロジェクトのゴールとスコープの確認
2. プロジェクト進行について
    1. スケジュールの確認
    2. 進行方法・ツールの確認
3. CNからの確認事項
    1. お伺いしたいこと
    2. 定例会の日程調整
    3. Next Actionの確認

---
![bg fit](images/onlylogopage.png)
<div class="title titleMain">プロジェクト概要</div>
<div class="title titleSub"></div>

---

<div class="slideTop">2-i メンバー紹介</div>

![](images/member_xxx.png)

---
<div class="slideTop">2-ii 事前情報の確認</div>

### **背景**
* 
* 

### **課題**
* 
* 

---
<div class="slideTop">2-iii プロジェクトのゴール・スコープ</div>

## **【ゴール】**
* **ご要件、ご要望を満たす**

## **【スコープ】**
* **システムの選定**
※

* **システムの導入支援（ご要望に応じて）**
※

---
![bg fit](images/onlylogopage.png)
<div class="title titleMain">プロジェクト進行について</div>
<div class="title titleSub"></div>


---
<div class="slideTop">3-i スケジュールの確認</div>
</br>

![](images/schedule_xxx.png)
* <div style="font-size:20px">記載のスケジュールは、他のお客様の事例を目安に記載しております。実際の進捗はお客様の現場でのご都合に依存することが大きく、<span style="color:red;font-weight:bold;">==スケジュールを確約するものではございません。==</span></div>
* <div style="font-size:20px">お客様のご都合によって環境構築のスピード及び、お打ち合わせ頻度に応じて、</br><span style="color:red;font-weight:bold;">月ごとにサービスボリュームを変更いただくことが可能です。</span></li>
---
<div class="slideTop">3-ii 進行方法・ツールの確認</div>

下記それぞれの用途で弊社が利用しているツールでゲストとして招待させていただきます。
* コミュニケーション：Slack
* ビデオ会議：Zoom
* ファイル共有：Box
* タスク管理：Asana

※その他PJの進行過程で何らかのツールの利用が必要となった場合は都度協議する
marp
---
<div class="slideTop">3-ii 進行方法・ツールの確認</div>


* ZoomのURL
    * 定例会議では、基本的に同じURLを利用します。
    * カレンダーに登録頂くか、ブックマークして頂くことをお勧めします。
* Box上での作業
    * Box上のファイルは、ローカル上にダウンロードせずともOfficeやGoogleWorkSpaceで編集が可能です。
* ゲストアカウントの削除
    * Box・Slack Connectは、PJ終了後も利用可能です。
    * Asanaは、弊社セキュリティポリシーに従い、3ヶ月以上ご利用のないゲストアカウントは確認の上で削除されます。ゲストアカウントは再発行が可能ですので、Slackにてお問い合わせください。

---
![bg fit](images/onlylogopage.png)
<div class="title titleMain">当社からの確認事項</div>
<div class="title titleSub"></div>

---
<div class="slideTop">4-i お伺いしたいこと</div>

---
<div class="slideTop">4-ii 定例会の日程調整</div>



週次でのお打ち合わせの実施を想定しております。
後ほど別途ご連絡いたしますので、ご調整をお願い致します。

---
<div class="slideTop">4-ii 定例会の日程調整</div>

## 様
* 
* 

## クラウドネイティブ
* 
* 

---
<!-- 
footer: <img src="images/footer.png" >
backgroundImage: url()
-->

<img src="images/CorpLogo.svg" style="display:block;margin: 0 auto;">

<a href="https://cloudnative.co.jp" style="display:block;text-align:center;color:black;text-decoration:underline;
">https://cloudnative.co.jp</a>

ITの世界だからこそ、人と人とのコミュニケーションを最重要視し、
全員が前を向いて楽しく仕事を進められる世界を作るのが最大のミッションです。

<p style="position: absolute;left:900px;bottom:50px;font-size:15px;color:gray;">株式会社クラウドネイティブ
</br>Cloud Native Inc.
</br>設立：2017年5月
</br>所在地：〒106-0032 東京都港区六本木1-4-5　
</br>アークヒルズサウスタワー 16F
</br>代表電話番号：050-1791-0450
</br>Eメールアドレス：info@cloudnative.co.jp
</p>