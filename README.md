# GSD-Banha
GDG Banha Template-One

## 📁 هيكل المشروع

```
GSD-Banha/
├── assets/
│   ├── css/              # ملفات CSS المترجمة
│   └── images/           # الصور
├── scss/
│   ├── base/            # الأساسيات (reset, container)
│   ├── components/      # المكونات (buttons)
│   ├── layout/          # التخطيط (header, footer, sections)
│   ├── utils/           # الأدوات (variables, mixins)
│   └── main.scss        # الملف الرئيسي
├── index.html
└── README.md
```

## 🚀 كيفية الاستخدام

### تحويل SCSS إلى CSS:

```bash
# باستخدام Live Sass Compiler في VS Code
# أو باستخدام sass من command line:
sass scss/main.scss assets/css/master.css
```

## 📝 الملفات

- **scss/utils/_variables.scss** - المتغيرات العامة
- **scss/utils/_mixins.scss** - الـ mixins القابلة لإعادة الاستخدام
- **scss/base/** - الأنماط الأساسية
- **scss/components/** - مكونات واجهة المستخدم
- **scss/layout/** - تخطيط الصفحة
