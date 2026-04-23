# 📝 تعليمات رفع سياسة الخصوصية على GitHub
# Setup Instructions for Privacy Policy on GitHub

---

## 🚀 الخطوات - Steps

### 1. إنشاء المستودع - Create Repository

أنشئ مستودع جديد على GitHub:

```
https://github.com/salehbagomri/tamm-app-privacy.git
```

---

### 2. نقل الملفات - Move Files

انسخ محتويات هذا المجلد إلى مجلد المستودع المحلي:

```
tamm-app-privacy/
├── README.md
├── PRIVACY_POLICY.md
├── index.html
└── SETUP_INSTRUCTIONS.md
```

---

### 3. رفع الملفات على GitHub - Upload Files

```bash
cd path/to/tamm-app-privacy
git init
git add .
git commit -m "Add privacy policy for Tamm App"
git remote add origin https://github.com/salehbagomri/tamm-app-privacy.git
git branch -M main
git push -u origin main
```

---

### 4. تفعيل GitHub Pages - Enable GitHub Pages

1. اذهب إلى: `https://github.com/salehbagomri/tamm-app-privacy`
2. اضغط **Settings** → **Pages**
3. **Source**: Branch `main`, Folder `/ (root)` → **Save**
4. انتظر دقيقة، الرابط سيكون:

```
https://salehbagomri.github.io/tamm-app-privacy/
```

---

### 5. استخدام الرابط في Google Play Store

في Play Console → **Store Listing** → **Privacy Policy**:

```
https://salehbagomri.github.io/tamm-app-privacy/
```

---

## 🔄 تحديث السياسة مستقبلاً

```bash
git add .
git commit -m "Update privacy policy"
git push origin main
```

---

## ✅ الرابط النهائي

**https://salehbagomri.github.io/tamm-app-privacy/**

يُستخدم في: Google Play Console، Firebase Console، التطبيق نفسه.

---

💙 **تمّ — خدمات التكييف والطاقة الشمسية**
