---
title: "Contact"
date: 2026-01-01T15:00:00+09:00
---

<div style="max-width: 600px; margin: 0 auto; color: #000;">
  <p>お問い合わせは以下のフォームよりお願いいたします。</p>

  <form name="contact" method="POST" data-netlify="true">
    <!-- Netlify 連携用の隠しフィールド（必須） -->
    <input type="hidden" name="form-name" value="contact" />

    <div style="margin-bottom: 20px;">
      <label style="display: block; font-weight: bold;">お名前 (必須)</label>
      <input type="text" name="name" required style="width: 100%; padding: 12px; border: 2px solid #000; color: #000 !important; background: #fff !important; font-size: 18px;">
    </div>

    <div style="margin-bottom: 20px;">
      <label style="display: block; font-weight: bold;">メールアドレス (必須)</label>
      <input type="email" name="email" required style="width: 100%; padding: 12px; border: 2px solid #000; color: #000 !important; background: #fff !important; font-size: 18px;">
    </div>

    <div style="margin-bottom: 20px;">
      <label style="display: block; font-weight: bold;">メッセージ (必須)</label>
      <textarea name="message" rows="6" required style="width: 100%; padding: 12px; border: 2px solid #000; color: #000 !important; background: #fff !important; font-size: 18px;"></textarea>
    </div>

    <button type="submit" style="width: 100%; padding: 20px; background: #000; color: #fff; border: none; font-weight: bold; font-size: 18px; cursor: pointer;">送信する</button>
  </form>
</div>
