---
title: "Contact"
date: 2026-01-01T15:00:00+09:00
---

<form name="contact" method="POST" data-netlify="true" action="/contactthankyou/">

    <div style="margin-bottom: 20px;">
        <label style="display: block; font-weight: bold;">お名前 (必須)</label>
        <!-- placeholderを追加 -->
        <input type="text" name="name" required placeholder="うね うね子" style="width: 100%; padding: 12px; border: 2px solid #fff; color: #fff !important; background: #000 !important; font-size: 18px;">
    </div>
    <div style="margin-bottom: 20px;">
        <label style="display: block; font-weight: bold;">E-mail(必須)</label>
        <!-- placeholderを追加 -->
        <input type="email" name="email" required placeholder="uneune.create@unel.com" style="width: 100%; padding: 12px; border: 2px solid #fff; color: #fff !important; background: #000 !important; font-size: 18px;">
    </div>
    <div style="margin-bottom: 20px;">
        <label style="display: block; font-weight: bold;">メッセージ (必須)</label>
        <!-- placeholderを追加 -->
        <textarea name="message" rows="6" required placeholder="メッセージをここに入力してください" style="width: 100%; padding: 12px; border: 2px solid #fff; color: #fff !important; background: #000 !important; font-size: 18px;"></textarea>
    </div>
    <!-- ファイルアップロード欄 -->
    <div style="margin-bottom: 20px;">
        <label style="display: block; font-weight: bold; color: #fff;">ファイルのアップロード</label>
        <input type="file" name="uploads" multiple style="width: 100%; padding: 12px; font-size: 16px; color: #fff; background: #000;">
    </div>
    <button type="submit" style="width: 100%; padding: 20px; background: #fff; color: #000; border: none; font-weight: bold; font-size: 18px; cursor: pointer;">送信する</button>
</form>
