# 2ch.net
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>掲示板@2ch風</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;}
body{
  background:#ffffee;
  color:#111;
  font-family:"MS PGothic","ＭＳ Ｐゴシック",osaka,"Hiragino Kaku Gothic Pro",sans-serif;
  font-size:15px;
  line-height:1.7;
}
a{color:#0000cc;text-decoration:underline;cursor:pointer;}
a:visited{color:#551a8b;}
a:hover{color:#dd0000;}

#header{background:#e8e8d0;border-bottom:3px solid #888;padding:6px 12px;display:flex;align-items:center;gap:10px;}
#header-logo{font-size:22px;font-weight:bold;color:#cc0000;letter-spacing:2px;cursor:pointer;}
#header-logo:hover{text-decoration:underline;}
#header-sub{font-size:12px;color:#555;}
#header-right{margin-left:auto;font-size:12px;color:#555;}
#clock{font-weight:bold;color:#222;}

#breadcrumb{background:#f0f0e0;border-bottom:1px solid #ccc;padding:3px 12px;font-size:12px;color:#555;}
#breadcrumb a{color:#000080;}

#nav{background:#ddddc8;border-bottom:1px solid #999;padding:3px 12px;font-size:13px;line-height:2;}
#nav a{margin-right:12px;color:#000080;}

#wrap{max-width:1100px;margin:0 auto;display:flex;}
#main{flex:1;padding:10px 12px;min-width:0;}

/* ━━ サイドバー（板一覧） ━━ */
#side{
  width:220px;
  border-left:2px solid #ccc;
  padding:8px;
  flex-shrink:0;
  background:#f5f5e8;
  font-size:13px;
}
.side-title{
  font-size:14px;font-weight:bold;color:#cc0000;
  border-bottom:2px solid #cc0000;margin-bottom:6px;padding-bottom:2px;
}
.side-section{margin-bottom:14px;}
.side-cat{
  font-size:11px;font-weight:bold;color:#fff;
  background:#666;padding:1px 6px;margin:8px 0 4px;
  display:block;
}
.side-link{
  display:block;font-size:13px;padding:2px 2px;
  color:#000080;text-decoration:underline;cursor:pointer;
  background:none;border:none;text-align:left;font-family:inherit;
  width:100%;
}
.side-link:hover{color:#cc0000;background:#ffe8e8;}
.side-link .bc{font-size:11px;color:#888;float:right;}

.stat-table{width:100%;border-collapse:collapse;font-size:13px;}
.stat-table td{padding:3px 5px;border:1px solid #ddd;}
.stat-table .s-label{background:#e8e8d0;color:#555;}
.stat-table .s-val{text-align:right;font-weight:bold;color:#cc0000;font-size:14px;}

.news-item{font-size:12px;padding:4px 0;border-bottom:1px dotted #ccc;color:#222;line-height:1.5;}
.news-item:last-child{border:none;}
.news-cat{font-size:10px;font-weight:bold;color:#fff;background:#cc0000;padding:0 4px;margin-right:4px;}
.news-cat.blue{background:#0000cc;}
.news-cat.green{background:#006600;}

/* ━━ 板タイトル ━━ */
.board-title{
  font-size:18px;font-weight:bold;color:#cc0000;
  border-bottom:3px solid #cc0000;padding-bottom:3px;margin-bottom:10px;
}

/* ━━ フォーム ━━ */
.post-form{background:#f0f0e0;border:1px solid #bbb;padding:10px;margin-bottom:12px;}
.post-form b{font-size:14px;}
.post-form table{width:100%;border-collapse:collapse;margin-top:6px;}
.post-form td{padding:3px 5px;vertical-align:middle;}
.post-form .label{width:80px;color:#555;white-space:nowrap;font-size:13px;}
.post-form input[type=text]{
  width:100%;border:1px inset #aaa;background:#fff;
  padding:4px 6px;font-size:14px;font-family:inherit;
}
.post-form select{
  border:1px inset #aaa;background:#fff;padding:3px 6px;
  font-size:13px;font-family:inherit;min-width:160px;
}
.post-form input[type=submit]{
  background:#e8e8d0;border:2px outset #aaa;
  padding:3px 16px;font-size:13px;cursor:pointer;font-family:inherit;
}
.post-form input[type=submit]:active{border-style:inset;}
#char-info{font-size:12px;color:#666;margin-left:8px;}

/* ━━ ツールバー ━━ */
.toolbar{
  background:#e8e8d0;border:1px solid #bbb;
  padding:4px 8px;margin-bottom:8px;
  font-size:12px;display:flex;align-items:center;gap:6px;flex-wrap:wrap;
}
.toolbar-btn{
  background:#f0f0e0;border:1px outset #aaa;
  padding:2px 10px;font-size:12px;cursor:pointer;font-family:inherit;
}
.toolbar-btn:active,.toolbar-btn.on{border-style:inset;background:#ddddc8;}
.filter-btn{
  display:inline-block;background:#e8e8d0;border:1px solid #aaa;
  padding:1px 8px;font-size:12px;cursor:pointer;margin:1px;font-family:inherit;
}
.filter-btn:hover{background:#ddddc8;}
.filter-btn.active{background:#cc0000;color:#fff;border-color:#990000;}

/* ━━ スレ一覧テーブル ━━ */
.thread-list{border-collapse:collapse;width:100%;font-size:14px;}
.thread-list th{
  background:#ddddc8;border:1px solid #aaa;
  padding:4px 8px;text-align:center;font-size:13px;white-space:nowrap;
}
.thread-list td{border:1px solid #ccc;padding:5px 8px;vertical-align:middle;}
.thread-list tr:nth-child(odd) td{background:#fffff4;}
.thread-list tr:nth-child(even) td{background:#f0f0e8;}
.thread-list tr:hover td{background:#ffd8d8;}
.t-num{text-align:center;width:36px;color:#666;font-size:12px;}
.t-board{text-align:center;width:110px;font-size:12px;color:#333;}
.t-res{text-align:right;width:56px;font-size:12px;color:#555;white-space:nowrap;}
.t-del{text-align:center;width:26px;}
.del-btn{background:none;border:none;color:#bbb;cursor:pointer;font-size:13px;padding:0;display:none;}
.thread-list tr:hover .del-btn{display:inline;}
.del-btn:hover{color:#cc0000;}
.new-badge{background:#cc0000;color:#fff;font-size:10px;padding:1px 4px;margin-left:5px;font-weight:bold;}
.res-hot{color:#cc0000;font-weight:bold;}
.empty{padding:24px;text-align:center;color:#999;font-size:13px;border:1px solid #ddd;background:#fafaf0;}

/* ━━ スレッドビュー ━━ */
#thread-view{display:none;} 
.thread-header-bar{
  background:#e8e8d0;border:1px solid #aaa;
  padding:5px 10px;margin-bottom:10px;
  display:flex;align-items:center;gap:8px;font-size:13px;
}
.back-btn{
  background:#f0f0e0;border:2px outset #aaa;
  padding:2px 12px;font-size:13px;cursor:pointer;font-family:inherit;
}
.back-btn:active{border-style:inset;}
.thread-view-title{
  font-size:17px;font-weight:bold;color:#cc0000;
  border-bottom:2px solid #cc0000;padding-bottom:3px;margin-bottom:6px;
}
.thread-info{font-size:12px;color:#666;margin-bottom:10px;}

/* ━━ レス ━━ */
.res-wrap{margin-bottom:3px;}
.res-header{
  background:#e8e8d0;border:1px solid #ccc;border-bottom:none;
  padding:3px 8px;font-size:12px;color:#555;
  display:flex;gap:10px;align-items:baseline;flex-wrap:wrap;
}
.res-num{font-weight:bold;color:#cc0000;font-size:13px;}
.res-name{font-weight:bold;color:#006600;font-size:13px;}
.res-mail{color:#0000cc;font-size:12px;}
.res-date{color:#888;font-size:11px;}
.res-id{color:#555;font-size:11px;font-family:monospace;}
.res-body{
  border:1px solid #ccc;background:#fffff4;
  padding:6px 10px 8px;
  white-space:pre-wrap;word-break:break-all;
  font-size:14px;line-height:1.8;
  color:#111;
}
.res-wrap:nth-child(even) .res-body{background:#f4f4ec;}
.anc-ref{color:#0000cc;text-decoration:underline;cursor:pointer;font-weight:bold;}

/* ━━ レス投稿フォーム ━━ */
.reply-form{background:#f0f0e0;border:1px solid #bbb;padding:10px;margin-top:14px;}
.reply-form b{font-size:14px;}
.reply-form table{width:100%;border-collapse:collapse;margin-top:6px;}
.reply-form td{padding:3px 5px;vertical-align:middle;}
.reply-form .label{width:70px;color:#555;white-space:nowrap;font-size:13px;}
.reply-form input[type=text]{
  width:100%;border:1px inset #aaa;background:#fff;
  padding:4px 6px;font-size:14px;font-family:inherit;
}
.reply-form textarea{
  width:100%;border:1px inset #aaa;background:#fff;
  padding:6px;font-size:14px;font-family:inherit;
  height:110px;resize:vertical;line-height:1.7;
}
.reply-form input[type=submit]{
  background:#e8e8d0;border:2px outset #aaa;
  padding:3px 18px;font-size:13px;cursor:pointer;font-family:inherit;
}
.reply-form input[type=submit]:active{border-style:inset;}
#reply-char{font-size:12px;color:#666;margin-left:8px;}

/* ━━ フッター ━━ */
#footer{
  border-top:2px solid #999;background:#e8e8d0;
  padding:5px 12px;text-align:center;font-size:12px;color:#555;margin-top:16px;
}

/* ━━ 板一覧モーダル ━━ */
#board-modal-overlay{display:none;position:fixed;inset:0;background:rgba(0,0,0,0.55);z-index:2000;align-items:flex-start;justify-content:center;overflow-y:auto;padding:30px 0;}
#board-modal-overlay.show{display:flex;}
#board-modal-box{
  background:#ffffee;border:2px outset #aaa;
  padding:16px;width:760px;max-width:98vw;
  box-shadow:4px 4px 0 #888;margin:auto;
}
#board-modal-box h2{font-size:15px;color:#cc0000;border-bottom:2px solid #cc0000;padding-bottom:4px;margin-bottom:12px;}
.bm-cat-title{
  font-size:13px;font-weight:bold;background:#ddddc8;
  border:1px solid #aaa;padding:2px 8px;margin:10px 0 4px;
}
.bm-grid{display:flex;flex-wrap:wrap;gap:2px 0;}
.bm-item{
  width:25%;font-size:13px;padding:2px 6px;
  border-bottom:1px dotted #ddd;
  cursor:pointer;color:#000080;text-decoration:underline;
  background:none;border-top:none;border-left:none;border-right:none;
  text-align:left;font-family:inherit;
}
.bm-item:hover{color:#cc0000;background:#ffe8e8;}
.bm-close{background:#e8e8d0;border:2px outset #aaa;padding:3px 14px;font-size:13px;cursor:pointer;font-family:inherit;margin-top:12px;}
.bm-close:active{border-style:inset;}

/* ━━ 削除依頼モーダル ━━ */
#modal-overlay{display:none;position:fixed;inset:0;background:rgba(0,0,0,0.5);z-index:1000;align-items:center;justify-content:center;}
#modal-overlay.show{display:flex;}
#modal-box{background:#ffffee;border:2px outset #aaa;padding:16px;width:440px;max-width:96vw;font-size:13px;box-shadow:4px 4px 0 #999;}
#modal-box h2{font-size:14px;color:#cc0000;border-bottom:1px solid #cc0000;padding-bottom:4px;margin-bottom:10px;}
.modal-form-table{width:100%;border-collapse:collapse;}
.modal-form-table td{padding:3px 5px;vertical-align:top;}
.modal-form-table .mlabel{width:90px;color:#555;padding-top:5px;font-size:13px;}
.modal-form-table input[type=text],.modal-form-table select,.modal-form-table textarea{
  width:100%;border:1px inset #aaa;background:#fff;padding:3px 5px;font-size:13px;font-family:inherit;
}
.modal-form-table textarea{height:60px;resize:vertical;}
.modal-btns{text-align:right;margin-top:10px;}
.modal-btns input{background:#e8e8d0;border:2px outset #aaa;padding:2px 14px;font-size:12px;cursor:pointer;font-family:inherit;margin-left:6px;}
.modal-btns input:active{border-style:inset;}
#del-req-result{display:none;background:#f0fff0;border:1px solid #090;padding:6px 8px;font-size:12px;color:#006600;margin-top:8px;}

#to-top{position:fixed;bottom:16px;right:16px;background:#e8e8d0;border:2px outset #aaa;padding:5px 10px;font-size:12px;cursor:pointer;font-family:inherit;display:none;}
#to-top:active{border-style:inset;}
</style>
</head>
<body>

<div id="header">
  <div id="header-logo" onclick="showList()">■ 掲示板@2ch風</div>
  <div id="header-sub">総合ポータル掲示板（保存機能付）</div>
  <div id="header-right"><span id="clock"></span></div>
</div>

<div id="breadcrumb">
  <a onclick="showList()">ホーム</a>
  <span id="bc-thread" style="display:none;"> &gt; <span id="bc-thread-name"></span></span>
</div>

<div id="nav">
  <a onclick="showList()">ホーム</a>
  <a onclick="openBoardModal()">板一覧</a>
  <a href="#">実況板</a>
  <a href="#">ニュース速報</a>
  <a href="#">VIP</a>
  <a href="#">なんでも実況</a>
  <a onclick="openModal();return false;">削除依頼</a>
</div>

<div id="wrap">
<div id="main">

<!-- ━━━ スレ一覧ビュー ━━━ -->
<div id="list-view">
  <div class="board-title" id="list-title">■ 全板 ＠ 掲示板ポータル</div>

  <div class="post-form">
    <b>【新規スレッド作成】</b>
    <table>
      <tr>
        <td class="label">名前</td>
        <td><input type="text" id="threadOpName" maxlength="30" autocomplete="off" placeholder="名前（省略すると「1」になります）"></td>
      </tr>
      <tr>
        <td class="label">タイトル</td>
        <td><input type="text" id="threadTitle" maxlength="100" autocomplete="off" placeholder="スレッドタイトル（100文字以内）"></td>
      </tr>
      <tr>
        <td class="label">本文</td>
        <td><textarea id="threadBodyText" maxlength="1000" placeholder="本文を入力（1レス目になります）" style="width:100%;height:80px;border:1px inset #aaa;background:#fff;padding:4px;font-size:14px;font-family:inherit;resize:vertical;line-height:1.7;"></textarea></td>
      </tr>
      <tr>
        <td class="label">板</td>
        <td>
          <select id="threadBoard" style="min-width:200px;"></select>
          &nbsp;
          <input type="submit" value="スレッドを立てる" onclick="addThread()">
          <span id="char-info">0/100文字</span>
        </td>
      </tr>
    </table>
  </div>

  <div class="toolbar">
    <b>表示：</b>
    <button class="toolbar-btn on" id="sort-new" onclick="sortThreads('new')">新着順</button>
    <button class="toolbar-btn" id="sort-hot" onclick="sortThreads('hot')">レス数順</button>
    &nbsp;|&nbsp;
    <b>板：</b>
    <span id="filter-btns-wrap">
      <button class="filter-btn active" id="fb-all" onclick="filterBoard(null,this)">全部</button>
    </span>
    <button class="toolbar-btn" onclick="openBoardModal()" style="margin-left:4px;">板一覧▼</button>
  </div>

  <table class="thread-list">
    <thead>
      <tr>
        <th class="t-num">番号</th>
        <th>タイトル</th>
        <th class="t-board">板</th>
        <th class="t-res">レス</th>
        <th class="t-del"></th>
      </tr>
    </thead>
    <tbody id="threadBody"></tbody>
  </table>
  <div class="empty" id="emptyState">スレッドがありません。最初のスレッドを立ててみましょう！</div>
</div>

<!-- ━━━ スレッドビュー ━━━ -->
<div id="thread-view">
  <div class="thread-header-bar">
    <button class="back-btn" onclick="showList()">◀ 板に戻る</button>
    <span id="tv-board" style="font-size:12px;color:#555;"></span>
  </div>
  <div class="thread-view-title" id="tv-title"></div>
  <div class="thread-info" id="tv-info"></div>
  <div id="res-list"></div>
  <div class="reply-form">
    <b>【レスを書く】</b>
    <table>
      <tr>
        <td class="label">名前</td>
        <td><input type="text" id="res-name" placeholder="名無しさん" maxlength="30"></td>
      </tr>
      <tr>
        <td class="label">メール</td>
        <td><input type="text" id="res-mail" placeholder="sage" maxlength="50"></td>
      </tr>
      <tr>
        <td class="label">本文</td>
        <td>
          <textarea id="res-body" placeholder="本文を入力（1000文字以内）&#10;>>番号 でアンカーできます" maxlength="1000"></textarea>
          <div><span id="reply-char">0/1000文字</span></div>
        </td>
      </tr>
      <tr>
        <td></td>
        <td><input type="submit" value="書き込む" onclick="postReply()"></td>
      </tr>
    </table>
  </div>
</div>

</div><!-- /main -->

<!-- ━━━ サイドバー ━━━ -->
<div id="side">
  <div class="side-section">
    <div class="side-title">■ 統計</div>
    <table class="stat-table">
      <tr><td class="s-label">スレッド数</td><td class="s-val" id="st-threads">0</td></tr>
      <tr><td class="s-label">総レス数</td><td class="s-val" id="st-posts">0</td></tr>
      <tr><td class="s-label">今日の投稿</td><td class="s-val" id="st-today">0</td></tr>
    </table>
  </div>

  <div class="side-section">
    <div class="side-title">■ 注目ニュース</div>
    <div class="news-item"><span class="news-cat">速報</span>掲示板がリニューアル！</div>
    <div class="news-item"><span class="news-cat blue">技術</span>AI関連スレが急増中</div>
    <div class="news-item"><span class="news-cat green">一般</span>今週の人気スレまとめ</div>
    <div class="news-item"><span class="news-cat">速報</span>VIP板で祭り発生中</div>
  </div>

  <div class="side-section">
    <div class="side-title">■ カテゴリ</div>
    <div id="side-cat-list"></div>
  </div>
</div>
</div><!-- /wrap -->

<div id="footer">
  掲示板ポータル @2ch風 &nbsp;|&nbsp; <a href="#">お問い合わせ</a> &nbsp;|&nbsp; <a href="#">利用規約</a> &nbsp;|&nbsp; <a onclick="openModal();return false;">削除依頼</a>
</div>

<button id="to-top" onclick="scrollTo(0,0)">▲ 上へ</button>

<!-- 板一覧モーダル -->
<div id="board-modal-overlay">
  <div id="board-modal-box">
    <h2>■ 板一覧（全カテゴリ）</h2>
    <div id="board-modal-content"></div>
    <div style="text-align:right;margin-top:12px;">
      <button class="bm-close" onclick="closeBoardModal()">閉じる</button>
    </div>
  </div>
</div>

<!-- 削除依頼モーダル -->
<div id="modal-overlay">
  <div id="modal-box">
    <h2>■ 削除依頼フォーム</h2>
    <table class="modal-form-table">
      <tr><td class="mlabel">対象スレ番号</td><td><input type="text" id="del-num" placeholder="例: 3"></td></tr>
      <tr><td class="mlabel">対象スレタイ</td><td><input type="text" id="del-title" placeholder="スレッドタイトル"></td></tr>
      <tr><td class="mlabel">削除理由</td><td>
        <select id="del-reason">
          <option>個人情報の掲載</option><option>誹謗中傷・名誉毀損</option>
          <option>著作権侵害</option><option>スパム・宣伝</option>
          <option>わいせつ・違法コンテンツ</option><option>その他</option>
        </select>
      </td></tr>
      <tr><td class="mlabel">詳細</td><td><textarea id="del-detail" placeholder="削除が必要な理由（任意）"></textarea></td></tr>
    </table>
    <div id="del-req-result">削除依頼を受け付けました。確認後、対応いたします。</div>
    <div class="modal-btns">
      <input type="submit" value="依頼を送信" onclick="submitDelReq()">
      <input type="button" value="閉じる" onclick="closeModal()">
    </div>
  </div>
</div>

<script>
// ━━━━━━━━━━━━━━━━━━━━━━━━
// 板データ（100板以上）
// ━━━━━━━━━━━━━━━━━━━━━━━━
const BOARD_CATS = [
  {cat:'ニュース', boards:['ニュース速報','ニュース速報+','国際ニュース','政治','経済ニュース','社会ニュース','地域ニュース','スポーツニュース','芸能ニュース','科学ニュース','IT・ネットニュース','環境・自然','事件・事故','裁判・法律','選挙']},
  {cat:'VIP・なんでも', boards:['VIP','なんでも実況J','なんでも実況G','なんでも実況+','ニュー速VIP','ネタ・お笑い','ネタ・コント','ダジャレ','雑談','一般雑談','深夜の雑談','ひとりごと']},
  {cat:'ゲーム', boards:['ゲーム一般','ゲーム難民','RPG','格闘ゲーム','シューティング','パズルゲーム','ADV・ノベル','オンラインゲーム','スマホゲーム','レトロゲーム','テーブルゲーム','麻雀','将棋・囲碁','ポケモン','モンハン','FF','ドラクエ','ソシャゲ','eスポーツ','インディーゲーム']},
  {cat:'アニメ・漫画', boards:['アニメ','アニメ2','深夜アニメ','声優','漫画','少年漫画','少女漫画','青年漫画','同人','ライトノベル','アニソン','特撮','ヒーロー','魔法少女','ロボットアニメ']},
  {cat:'映画・テレビ', boards:['映画一般','洋画','邦画','映画作品','ドラマ','連続ドラマ','海外ドラマ','バラエティ','ドキュメンタリー','テレビ一般','NHK','CM']},
  {cat:'音楽', boards:['音楽一般','邦楽','洋楽','J-POP','ロック','ヒップホップ','クラシック','ジャズ','アイドル','バンド','ボカロ','DTM','楽器','ライブ・フェス','レコード・CD']},
  {cat:'スポーツ', boards:['野球','プロ野球','高校野球','サッカー','Jリーグ','テニス','バスケットボール','バレーボール','格闘技','競馬','競輪・競艇','ゴルフ','陸上競技','水泳','スキー・スノーボード','マラソン','オリンピック']},
  {cat:'パソコン・IT', boards:['PC一般','Windows','Mac','Linux','プログラミング','Web制作','セキュリティ','ハードウェア','自作PC','スマートフォン','Android','iPhone','ガジェット','AI・機械学習','ネットワーク','データベース']},
  {cat:'学問・文化', boards:['学問一般','数学','物理','化学','生物','歴史','哲学','心理学','語学・英語','語学・中国語','文学','考古学','地理','天文・宇宙','医学・健康']},
  {cat:'趣味・生活', boards:['趣味一般','料理','グルメ','旅行','鉄道','車・バイク','自転車','釣り','山・登山','DIY','カメラ','写真','ファッション','インテリア','ガーデニング','ペット','猫','犬','熱帯魚','読書']},
  {cat:'その他', boards:['就職・転職','副業・起業','投資','株式','FX','不動産','育児','恋愛','婚活','メンタルヘルス','ダイエット','美容','オカルト','UFO・宇宙人','都市伝説','未解決事件']},
];

// 全板フラット
const ALL_BOARDS = BOARD_CATS.flatMap(c=>c.boards);

// ━━━━━━━━━━━━━━━━━━━━━━━━
// 初期化
// ━━━━━━━━━━━━━━━━━━━━━━━━
function buildBoardSelect(){
  const sel=document.getElementById('threadBoard');
  BOARD_CATS.forEach(cat=>{
    const og=document.createElement('optgroup');
    og.label=cat.cat;
    cat.boards.forEach(b=>{
      const op=document.createElement('option');
      op.value=b; op.textContent=b;
      og.appendChild(op);
    });
    sel.appendChild(og);
  });
}

function buildSideCat(){
  const wrap=document.getElementById('side-cat-list');
  BOARD_CATS.forEach(cat=>{
    const span=document.createElement('span');
    span.className='side-cat';
    span.textContent='▼ '+cat.cat;
    wrap.appendChild(span);
    cat.boards.slice(0,5).forEach(b=>{
      const btn=document.createElement('button');
      btn.className='side-link';
      btn.innerHTML=b+'<span class="bc" id="bc-'+encodeBoard(b)+'">0</span>';
      btn.onclick=()=>{filterBoard(b,null);showList();};
      wrap.appendChild(btn);
    });
    if(cat.boards.length>5){
      const more=document.createElement('button');
      more.className='side-link';
      more.style.color='#888';
      more.textContent='…他'+(cat.boards.length-5)+'板';
      more.onclick=()=>openBoardModal();
      wrap.appendChild(more);
    }
  });
}

function buildBoardModal(){
  const wrap=document.getElementById('board-modal-content');
  BOARD_CATS.forEach(cat=>{
    const title=document.createElement('div');
    title.className='bm-cat-title';
    title.textContent='【'+cat.cat+'】';
    wrap.appendChild(title);
    const grid=document.createElement('div');
    grid.className='bm-grid';
    cat.boards.forEach(b=>{
      const btn=document.createElement('button');
      btn.className='bm-item';
      btn.textContent=b;
      btn.onclick=()=>{filterBoard(b,null);showList();closeBoardModal();};
      grid.appendChild(btn);
    });
    wrap.appendChild(grid);
  });
}

const encodeBoard=b=>b.replace(/[^a-zA-Z0-9]/g,'_');

buildBoardSelect();
buildSideCat();
buildBoardModal();

// ━━━━━━━━━━━━━━━━━━━━━━━━
// ユーティリティ
// ━━━━━━━━━━━━━━━━━━━━━━━━
const pad=v=>String(v).padStart(2,'0');
function fmtDate(ts){
  if(!ts)return '';
  const d=new Date(ts);
  return d.getFullYear()+'/'+(d.getMonth()+1)+'/'+d.getDate()+
    ' '+pad(d.getHours())+':'+pad(d.getMinutes())+':'+pad(d.getSeconds());
}
function genId(ts){
  const chars='ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789';
  const s=String(ts%10000000).split('').reverse().join('');
  let id='';
  for(let i=0;i<8;i++) id+=chars[(parseInt(s[i]||'0')+i*7)%chars.length];
  return id;
}

function tick(){
  const n=new Date();
  document.getElementById('clock').textContent=
    n.getFullYear()+'/'+pad(n.getMonth()+1)+'/'+pad(n.getDate())+
    ' '+pad(n.getHours())+':'+pad(n.getMinutes())+':'+pad(n.getSeconds());
}
setInterval(tick,1000); tick();
window.addEventListener('scroll',()=>{
  document.getElementById('to-top').style.display=scrollY>300?'block':'none';
});

// ━━━━━━━━━━━━━━━━━━━━━━━━
// データ
// ━━━━━━━━━━━━━━━━━━━━━━━━
function loadData(){
  try{
    const raw=localStorage.getItem('bbs2ch_v3');
    if(!raw) return {threads:[]};
    const d=JSON.parse(raw);
    if(!Array.isArray(d.threads)) return {threads:[]};
    return {threads: d.threads.filter(t=>
      t && typeof t.title==='string' && typeof t.id==='number'
    ).map(t=>({
      id:    Number(t.id),
      title: String(t.title).slice(0,100),
      board: String(t.board||'雑談').slice(0,30),
      count: Number(t.count)||0,
      ts:    Number(t.ts)||0,
      today: Boolean(t.today),
        opName: String(t.opName||'1').slice(0,30),
        opBody: String(t.opBody||'').slice(0,1000),
      posts: Array.isArray(t.posts)?t.posts.filter(p=>p&&typeof p.body==='string').map(p=>({
        id:   Number(p.id)||0,
        name: String(p.name||'名無しさん').slice(0,30),
        mail: String(p.mail||'').slice(0,50),
        body: String(p.body).slice(0,1000),
        ts:   Number(p.ts)||0,
      })):[],
    }))};
  }catch(e){return {threads:[]};}
}
function saveData(){
  try{localStorage.setItem('bbs2ch_v3',JSON.stringify({threads:threads.slice(0,200)}));}catch(e){}
}

let {threads}=loadData();
let sortMode='new', filterMode=null, currentThreadId=null;

// ━━━━━━━━━━━━━━━━━━━━━━━━
// 画面切替
// ━━━━━━━━━━━━━━━━━━━━━━━━
function showList(){
  document.getElementById('list-view').style.display='block';
  document.getElementById('thread-view').style.display='none';
  document.getElementById('bc-thread').style.display='none';
  currentThreadId=null;
  render();
  scrollTo(0,0);
}
function showThread(id){ id=Number(id);
  const t=threads.find(t=>t.id===id);
  if(!t)return;
  currentThreadId=id;
  document.getElementById('list-view').style.display='none';
  document.getElementById('thread-view').style.display='block';
  document.getElementById('bc-thread').style.display='inline';
  document.getElementById('bc-thread-name').textContent=t.title;
  document.getElementById('tv-title').textContent='【'+t.board+'】 '+t.title;
  document.getElementById('tv-board').textContent='板：'+t.board;
  renderThread(t);
  scrollTo(0,0);
}

// ━━━━━━━━━━━━━━━━━━━━━━━━
// スレッドビュー描画
// ━━━━━━━━━━━━━━━━━━━━━━━━
function renderThread(t){
  const list=document.getElementById('res-list');
  list.innerHTML='';
  document.getElementById('tv-info').textContent=
    'レス数: '+t.posts.length+' / 作成: '+fmtDate(t.ts);

  const allPosts=[
    {id:1,name:t.opName||'1',mail:'',body:t.opBody||'',ts:t.ts},
    ...t.posts.map((p,i)=>({...p,id:i+2}))
  ];

  allPosts.forEach(p=>{
    const wrap=document.createElement('div');
    wrap.className='res-wrap';
    wrap.id='res-'+p.id;

    const header=document.createElement('div');
    header.className='res-header';

    const mkSpan=(cls,txt)=>{const s=document.createElement('span');s.className=cls;s.textContent=txt;return s;};
    header.appendChild(mkSpan('res-num',p.id));
    header.appendChild(mkSpan('res-name',p.name||'名無しさん'));
    if(p.mail) header.appendChild(mkSpan('res-mail','['+p.mail+']'));
    header.appendChild(mkSpan('res-date',fmtDate(p.ts)));
    header.appendChild(mkSpan('res-id','ID:'+genId(p.ts)));

    const body=document.createElement('div');
    body.className='res-body';
    parseBody(p.body,body,allPosts.length);

    wrap.appendChild(header);
    wrap.appendChild(body);
    list.appendChild(wrap);
  });
}

function parseBody(text,container,maxRes){
  text.split('\n').forEach((line,li)=>{
    if(li>0) container.appendChild(document.createElement('br'));
    line.split(/(>>\d+)/g).forEach(part=>{
      const m=part.match(/^>>(\d+)$/);
      if(m){
        const n=parseInt(m[1]);
        const a=document.createElement('a');
        a.className='anc-ref';
        a.textContent=part;
        if(n>=1&&n<=maxRes){
          a.onclick=()=>{
            const el=document.getElementById('res-'+n);
            if(el)el.scrollIntoView({behavior:'smooth',block:'center'});
          };
        }
        container.appendChild(a);
      } else {
        container.appendChild(document.createTextNode(part));
      }
    });
  });
}

// ━━━━━━━━━━━━━━━━━━━━━━━━
// レス投稿
// ━━━━━━━━━━━━━━━━━━━━━━━━
function postReply(){
  if(!currentThreadId)return;
  const t=threads.find(t=>t.id===currentThreadId);
  if(!t){alert('スレが見つかりません');return;}
  if(t.posts.length>=999){alert('このスレは1000レスに達しました。新しいスレを立ててください。');return;}
  const name=document.getElementById('res-name').value.trim()||'名無しさん';
  const mail=document.getElementById('res-mail').value.trim();
  const body=document.getElementById('res-body').value.trim();
  if(!body){alert('本文を入力してください');return;}
  if(body.length>1000){alert('本文は1000文字以内です');return;}
  t.posts.push({id:Date.now(),name,mail,body,ts:Date.now()});
  t.count=t.posts.length;
  saveData();
  document.getElementById('res-name').value='';
  document.getElementById('res-mail').value='';
  document.getElementById('res-body').value='';
  document.getElementById('reply-char').textContent='0/1000文字';
  renderThread(t);
  const items=document.querySelectorAll('.res-wrap');
  if(items.length)items[items.length-1].scrollIntoView({behavior:'smooth',block:'start'});
}

// ━━━━━━━━━━━━━━━━━━━━━━━━
// 一覧描画
// ━━━━━━━━━━━━━━━━━━━━━━━━
function render(){
  const tbody=document.getElementById('threadBody');
  const empty=document.getElementById('emptyState');
  let list=[...threads];
  if(filterMode)list=list.filter(t=>t.board===filterMode);
  if(sortMode==='hot')list.sort((a,b)=>b.count-a.count);
  else list.sort((a,b)=>b.id-a.id);

  const title=document.getElementById('list-title');
  title.textContent='■ '+(filterMode||'全板')+' ＠ 掲示板ポータル';

  tbody.innerHTML='';
  empty.style.display=list.length?'none':'block';

  list.forEach((t,i)=>{
    const tr=document.createElement('tr');
    const tdNum=document.createElement('td');tdNum.className='t-num';tdNum.textContent=i+1;
    const tdTitle=document.createElement('td');
    const a=document.createElement('a');a.textContent=t.title;a.onclick=()=>showThread(t.id);
    tdTitle.appendChild(a);
    if(t.today){const b=document.createElement('span');b.className='new-badge';b.textContent='NEW';tdTitle.appendChild(b);}
    const tdBoard=document.createElement('td');tdBoard.className='t-board';tdBoard.textContent=t.board;
    const tdRes=document.createElement('td');tdRes.className='t-res'+(t.count>=100?' res-hot':'');tdRes.textContent=t.count;
    const tdDel=document.createElement('td');tdDel.className='t-del';
    const btn=document.createElement('button');btn.className='del-btn';btn.textContent='×';btn.title='削除';
    btn.onclick=e=>{e.stopPropagation();deleteThread(t.id);};tdDel.appendChild(btn);
    tr.append(tdNum,tdTitle,tdBoard,tdRes,tdDel);
    tbody.appendChild(tr);
  });
  updateStats();
}

function updateStats(){
  document.getElementById('st-threads').textContent=threads.length;
  document.getElementById('st-posts').textContent=threads.reduce((a,t)=>a+t.count,0);
  document.getElementById('st-today').textContent=threads.filter(t=>t.today).length;
  ALL_BOARDS.forEach(b=>{
    const el=document.getElementById('bc-'+encodeBoard(b));
    if(el)el.textContent=threads.filter(t=>t.board===b).length;
  });
}

// ━━━━━━━━━━━━━━━━━━━━━━━━
// スレ作成・削除
// ━━━━━━━━━━━━━━━━━━━━━━━━
function addThread(){
  const inp=document.getElementById('threadTitle');
  const board=document.getElementById('threadBoard').value;
  const opName=document.getElementById("threadOpName").value.trim();
  const opBody=document.getElementById("threadBodyText").value.trim();
  const title=inp.value.trim();
  if(!title){alert('タイトルを入力してください');inp.focus();return;}
  if(title.length>100){alert('タイトルは100文字以内です');return;}
  if(threads.length>=200){alert('スレッド保存上限（200件）に達しました');return;}
  threads.unshift({id:Date.now(),title,board,opName:opName||"1",opBody:opBody||"",count:0,ts:Date.now(),today:true,posts:[]});
  filterMode=null;
  document.querySelectorAll('.filter-btn').forEach(b=>b.classList.remove('active'));
  const fba=document.getElementById('fb-all'); if(fba)fba.classList.add('active');
  const cuf=document.querySelector('.current-filter'); if(cuf)cuf.remove();
  saveData();render();
  inp.value='';
  document.getElementById('char-info').textContent='0/100文字';
  document.getElementById('char-info').style.color='#666';
  document.getElementById('threadOpName').value='';
  document.getElementById('threadBodyText').value='';
}
function deleteThread(id){
  if(!confirm('このスレッドを削除しますか？'))return;
  threads=threads.filter(t=>t.id!==id);
  saveData();render();
}

// ━━━━━━━━━━━━━━━━━━━━━━━━
// ソート・フィルター
// ━━━━━━━━━━━━━━━━━━━━━━━━
function sortThreads(mode){
  sortMode=mode;
  document.getElementById('sort-new').className='toolbar-btn'+(mode==='new'?' on':'');
  document.getElementById('sort-hot').className='toolbar-btn'+(mode==='hot'?' on':'');
  render();
}
function filterBoard(board,btn){
  filterMode=board;
  document.querySelectorAll('.filter-btn').forEach(b=>b.classList.remove('active'));
  if(btn)btn.classList.add('active');
  else document.getElementById('fb-all').classList.add('active');
  // 選択板をツールバーに表示
  const wrap=document.getElementById('filter-btns-wrap');
  const existing=wrap.querySelector('.filter-btn.current-filter');
  if(existing)existing.remove();
  if(board){
    const fb=document.createElement('button');
    fb.className='filter-btn active current-filter';
    fb.textContent=board+' ×';
    fb.onclick=()=>filterBoard(null,document.getElementById('fb-all'));
    wrap.appendChild(fb);
  }
  render();
}

// ━━ 文字数
document.getElementById('threadTitle').addEventListener('input',function(){
  const len=this.value.length;
  const el=document.getElementById('char-info');
  el.textContent=len+'/100文字';
  el.style.color=len>100?'#cc0000':len>80?'#cc6600':'#666';
});
document.getElementById('res-body').addEventListener('input',function(){
  document.getElementById('reply-char').textContent=this.value.length+'/1000文字';
});
document.getElementById('threadTitle').addEventListener('keydown',e=>{if(e.key==='Enter')addThread();});

// ━━━━━━━━━━━━━━━━━━━━━━━━
// モーダル
// ━━━━━━━━━━━━━━━━━━━━━━━━
function openBoardModal(){
  document.getElementById('board-modal-overlay').classList.add('show');
}
function closeBoardModal(){
  document.getElementById('board-modal-overlay').classList.remove('show');
}
document.getElementById('board-modal-overlay').addEventListener('click',function(e){
  if(e.target===this)closeBoardModal();
});

function openModal(){
  document.getElementById('modal-overlay').classList.add('show');
  document.getElementById('del-req-result').style.display='none';
  ['del-num','del-title','del-detail'].forEach(id=>document.getElementById(id).value='');
}
function closeModal(){document.getElementById('modal-overlay').classList.remove('show');}
function submitDelReq(){
  const num=document.getElementById('del-num').value.trim();
  const title=document.getElementById('del-title').value.trim();
  if(!num&&!title){alert('スレ番号またはスレタイを入力してください');return;}
  document.getElementById('del-req-result').style.display='block';
  ['del-num','del-title','del-detail'].forEach(id=>document.getElementById(id).value='');
}
document.getElementById('modal-overlay').addEventListener('click',function(e){
  if(e.target===this)closeModal();
});

render();
</script>
</body>
</html>
