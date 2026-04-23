<div style="border:1px solid #ccc; margin:16px 0;">

  <!-- ヘッダー -->
  <div style="display:flex; background:#f5f5f5;">
    <div style="width:50%; padding:8px; font-weight:bold; color:#000; border-right:1px solid #ccc;">
      実際のコード
    </div>
    <div style="width:50%; padding:8px; font-weight:bold; color:#000;">
      ブラウザ表示
    </div>
  </div>

  <!-- 中身 -->
  <div style="display:flex;">
    
    <!-- 左：コード -->
    <div style="width:50%; padding:8px; background:#1e1e1e; color:#fff; border-right:1px solid #ccc;">
      {{CODE}}
    </div>

    <!-- 右：プレビュー -->
    <div style="width:50%; padding:8px; background:#fff;">
      <iframe 
        src="{{URL}}"
        style="width:100%; height:300px; border:0;">
      </iframe>
    </div>

  </div>

</div>