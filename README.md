# 💬 Wegap Widget for Vue / ویجت ویگپ برای Vue

This repository contains the official Vue version of the Wegap widget.  
این مخزن شامل نسخه رسمی ویجت ویگپ برای برنامه‌های Vue.js است. با استفاده از این ویجت می‌توانید قابلیت‌هایی مانند **چت، تماس صوتی/تصویری، و دانشیار هوش مصنوعی** را به راحتی به اپلیکیشن خود اضافه کنید.

---

## 📦 Installation / نصب

```bash
npm install @wegapnet/widget-vue
# or
yarn add @wegapnet/widget-vue
```

---

## 🚀 Quick Usage / استفاده سریع

```vue
<template>
  <div>
    <h1>اپلیکیشن من</h1>
    <WegapWidget
      authKey="YOUR_AUTH_KEY"
      theme="light"
      position="bottom-right"
      language="fa"
    />
  </div>
</template>

<script>
import WegapWidget from '@wegapnet/widget-vue'

export default {
  components: {
    WegapWidget
  }
}
</script>
```

---

## ⚙️ Config Options / تنظیمات

| Prop Name | Type   | Description EN                                      | توضیح فارسی |
|-----------|--------|------------------------------------------------------|--------------|
| authKey   | string | Your unique authentication key                      | کلید احراز هویت شما |
| theme     | string | Theme mode: `light` or `dark`                       | تم: روشن یا تیره |
| position  | string | Widget position: `bottom-right`, `bottom-left`, etc | موقعیت ویجت |
| language  | string | Default widget language (fa, en, ar, ...)           | زبان پیش‌فرض |

---

## 📄 Documentation / مستندات کامل

- [See full guide in Wegap Wiki](https://wegap.net/wiki/vue/نصب-و-راه-اندازی/راهنمای-ویجت-ویگپ/دانشیار-ویگپ-id-8912)
- مشاهده راهنما در ویکی ویگپ ↑
