---
marp: true

style: |
    {
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
            position: relative;
            top: -100px;
            display: block;
            margin: 0 auto;
            text-align: center;
            padding: 5px;
            size: 20px;
        }

        .headMain{
            background-color: black;
            color: white;
            width: 70%;
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
            position: relative;
            size: 10%;
            top: -190px;
            left: 750px; 
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
footer: <img src="footer.png" >
-->
#
![bg fit](プレゼン資料_テンプレート20250401.png)
<span class="icon">![h:80](CONFIDENTIAL.png)</span>
<div class="head headMain">〇〇社様</br>ご提案について</div>
<div class="head headSub">2025/06/16</div>

# 
![bg fit](ロゴのみ.png)
<div class="title titleMain">メインタイトル</div>
<div class="title titleSub">サブタイトル</div>

#
<!--
footer: <img>
backgroundImage: url(base.png)
backgroundSize: cover
paginate: true
-->

<div class="slideTop">XXXXXXX</div>


<div class="agenda">
<!-- markdown テーブル
2.こういう時は| p.1 
:---|---:
1.大体こんなことをしたいという| p.1 
tett | p.3 
-->
    <table>
        <tr>
            <th>1</th>
            <td>内容1-11111111111111111111x</td>
            <td>p.111</td>
        </tr>
        <tr>
            <th>2</th>
            <td>内容1-2</td>
            <td>p.111</td>
        </tr>
        <tr>
            <th>3</th>
            <td>内容2-1</td>
            <td>p.111</td>
        </tr>
        <tr>
            <th>4</th>
            <td>内容2-1</td>
            <td>p.111</td>
        </tr>
    </table>
</div>

#

```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title プロジェクトのフェーズ

    section 計画
    要件定義      :done,    des1, 2025-07-20, 3d
    設計書作成    :active,  des2, 2025-07-23, 5d

    section 開発
    モジュールA開発 :         dev1, after des2, 7d
    モジュールB開発 :         dev2, after dev1, 5d

    section テスト
    単体テスト    :         test1, after dev1, 3d
    結合テスト    :         test2, after test1, 2d

#

#

#

#

#

#

#

#

#

#

#


