# Project setup instructions
1- npm create vite@latest my-app --template react-ts
2- cd my-app
3- npm install

# Folder structure explanation
DASHOBARD-PANAL/
├── node_modules/           # مجلد الحزم المثبتة (npm/yarn)
├── public/                 # الملفات العامة مثل الصور والفافيكون
├── src/                    # الكود الأساسي للتطبيق
│   ├── assets/             # الصور والخطوط والملفات الثابتة
│   ├── components/         # مكونات UI العامة والقابلة لإعادة الاستخدام
│   ├── features/           # الوحدات (Features) - كل ميزة مستقلة
│   ├── hooks/              # Custom Hooks الخاصة بالمشروع
│   ├── lib/                # المكتبات (functions/helpers) المشتركة
│   ├── pages/              # الصفحات (Page components)
│   ├── shared/             # الأكواد والمكونات المشتركة بين الميزات
│   ├── styles/             # ملفات CSS/Tailwind styles
│   ├── App.tsx             # الملف الرئيسي للتطبيق (React root component)
│   └── main.tsx            # نقطة الدخول (Entry Point) للتطبيق
├── package.json            # إدارة الحزم والسكريبتات
└── README.md               # توثيق المشروع

