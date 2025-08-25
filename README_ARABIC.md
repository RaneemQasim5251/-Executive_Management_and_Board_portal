# 🏢 بوابة الإدارة التنفيذية ومجلس الإدارة | Executive Management Portal

> **أحدث لوحة تحكم للإدارة العليا** - بوابة حديثة ومتطورة مصممة حصرياً للمدراء التنفيذيين وأعضاء مجلس الإدارة.

<div align="center">

[![React](https://img.shields.io/badge/React-18.3.1-blue?logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Refine](https://img.shields.io/badge/Refine-4.0+-purple?logo=refine)](https://refine.dev/)
[![Supabase](https://img.shields.io/badge/Supabase-Ready-green?logo=supabase)](https://supabase.com/)
[![Arabic](https://img.shields.io/badge/Arabic-RTL%20Support-green?logo=google-translate)](https://www.google.com/intl/ar/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

</div>

---

## 🌟 **المميزات الرئيسية | Key Features**

### 🇸🇦 **دعم اللغة العربية الكامل | Full Arabic Support**
- **RTL (من اليمين إلى اليسار)** - تخطيط كامل لدعم العربية
- **ترجمة شاملة** - واجهة باللغة العربية مع إمكانية التبديل للإنجليزية  
- **خطوط عربية** - خطوط Noto Sans Arabic و Cairo المحسّنة
- **تجربة محلية** - مصممة للمستخدمين العرب

### 📊 **لوحة المعلومات التنفيذية | Executive Dashboard**
- **مؤشرات الأداء الرئيسية** - الإيرادات، المشاريع، أداء الفريق
- **الرسوم البيانية التفاعلية** - تصورات بيانات حديثة مع رسوم متحركة
- **تحليلات استراتيجية** - رؤى للإدارة العليا لاتخاذ القرارات
- **تصميم متجاوب** - يعمل بكفاءة على جميع الأجهزة

### 🚀 **الجدول الزمني الاستراتيجي | Strategic Timeline**
- **تصميم متدرج جميل** - من الأزرق الداكن إلى الأزرق الفاتح
- **معالم المشاريع** - تتبع بصري للأحداث الرئيسية
- **أحداث تفاعلية** - انقر للاطلاع على التفاصيل وإضافة التعليقات
- **التخطيط الاستراتيجي** - تصور طويل المدى للمشاريع

### 👥 **إدارة مجلس الإدارة | Board Management**
- **المهام عالية المستوى** - مبادرات الإدارة العليا والمشاريع الاستراتيجية
- **نظام التعليقات** - تعاون تنفيذي مع المرفقات
- **عرض للمراقبة** - مثالي لإشراف مجلس الإدارة
- **السحب والإفلات** - واجهة حديثة لإدارة المهام

### 🔐 **المصادقة التنفيذية | Executive Authentication**
- **دخول الإدارة العليا فقط** - مصادقة آمنة للمدراء التنفيذيين
- **أذونات مبنية على الأدوار** - ضوابط وصول خاصة بأعضاء مجلس الإدارة
- **أمان Supabase** - أمان على مستوى المؤسسات
- **إدارة الجلسات** - انتهاء صلاحية تلقائي وميزات أمان

---

## 🛠️ **التكنولوجيا المستخدمة | Tech Stack**

### **Frontend Framework:**
- ⚛️ **React 18** - أحدث إصدار مع الميزات المتزامنة
- 🏗️ **Refine Framework** - إطار عمل React للتطوير السريع
- 📘 **TypeScript** - أمان كامل للأنواع وتجربة تطوير أفضل

### **UI & Design:**
- 🎨 **Ant Design 5** - مكونات واجهة المستخدم على مستوى المؤسسات
- 🎭 **Framer Motion** - رسوم متحركة وانتقالات سلسة
- 📊 **Recharts** - رسوم بيانية جميلة ومتجاوبة
- 🌐 **RTL Support** - دعم كامل للغة العربية

### **Backend & Database:**
- 🗄️ **Supabase** - قاعدة بيانات PostgreSQL في الوقت الفعلي
- 🔐 **مصادقة Supabase** - مصادقة وتفويض على مستوى المؤسسات
- 🛡️ **Row Level Security** - أمان على مستوى الصفوف
- 📊 **Real-time Updates** - تحديثات فورية للبيانات

### **Development Tools:**
- ⚡ **Vite** - أداة تطوير سريعة البرق
- 🔧 **ESLint** - جودة واتساق الكود
- 🛠️ **TypeScript Config** - محسن للتطوير الحديث

---

## 🚀 **البدء السريع | Quick Start**

### **المتطلبات الأساسية | Prerequisites**
- Node.js 18+
- npm أو yarn
- متصفح حديث
- حساب Supabase (للبيانات الحقيقية)

### **التثبيت | Installation**

```bash
# 1. استنساخ المستودع | Clone the repository
git clone https://github.com/RaneemQasim5251/-Executive_Management_and_Board_portal.git
cd Executive-Management-Portal

# 2. تثبيت التبعيات | Install dependencies  
npm install

# 3. إعداد متغيرات البيئة | Setup environment variables
cp env.example .env.local
# Edit .env.local with your Supabase credentials

# 4. بدء خادم التطوير | Start development server
npm run dev

# 5. افتح المتصفح | Open your browser
# http://localhost:5173
```

### **المتغيرات البيئية | Environment Variables**
قم بإنشاء ملف `.env.local` وتعبئة القيم حسب حاجتك:

```bash
VITE_APP_TITLE=Executive Management Portal
VITE_SUPABASE_URL=your-supabase-url
VITE_SUPABASE_ANON_KEY=your-supabase-anon-key
# Power BI (اختياري)
VITE_POWERBI_TENANT_ID=...
VITE_POWERBI_CLIENT_ID=...
VITE_POWERBI_WORKSPACE_ID=...
VITE_POWERBI_REPORT_ID=...
```

### **بناء وتشغيل | Build & Preview**
```bash
npm run build
npm run preview
```

### **بيانات تسجيل الدخول التجريبية | Demo Login Credentials**
```
📧 Email: board@company.com
🔐 Password: executive2024
```

---

## 🗄️ **إعداد قاعدة البيانات | Database Setup**

### **1. إنشاء مشروع Supabase**
```bash
1. اذهب إلى https://supabase.com  
2. إنشاء مشروع جديد
3. اختر المنطقة (الشرق الأوسط/أوروبا للمستخدمين العرب)
4. سجل عناوين URL والمفاتيح الخاصة بمشروعك
```

### **2. تشغيل مخطط قاعدة البيانات**
```sql
-- انسخ وشغل ملف database-schema.sql بالكامل في محرر SQL الخاص بـ Supabase
-- هذا ينشئ جميع الجداول والسياسات والبيانات النموذجية
```

### **3. تكوين متغيرات البيئة**
```bash
VITE_SUPABASE_URL=https://your-project.supabase.co
VITE_SUPABASE_ANON_KEY=your-supabase-anon-key
```

---

## 🌍 **النشر | Deployment**

### **خيارات النشر السريع | Quick Deployment Options**

#### **1. Vercel (موصى به | Recommended)**
```bash
npm i -g vercel
vercel --prod
```

#### **2. Netlify**
```bash
npm run build
# اسحب وأفلت مجلد 'dist' إلى netlify.com
```

#### **3. Docker**
```bash
docker build -t executive-portal .
docker run -p 80:80 executive-portal  
```

**📖 للحصول على دليل نشر مفصل، راجع [DEPLOYMENT.md](DEPLOYMENT.md)**

---

## 🧱 **هيكل المشروع | Project Structure**

```
Executive-Management-Portal/
├─ src/
│  ├─ api/                  # خادم API خفيف (Express)
│  ├─ components/           # المكونات (المصادقة، الصوت، القياسات الحيوية، التخطيطات)
│  ├─ hooks/                # الخطافات (الصوت، PowerBI)
│  ├─ pages/                # الصفحات (dashboard, reports, secretary workspace, login)
│  ├─ providers/            # مزودو المصادقة (Supabase)
│  ├─ services/             # الخدمات (PowerBI, notifications)
│  ├─ styles/               # الأنماط (minimalist, simplified, world-class)
│  └─ i18n.ts               # ضبط الترجمة (AR/EN)
├─ supabase/functions/      # وظائف Edge (sign/request-signatures)
├─ Dockerfile               # حاوية الواجهة الأمامية
├─ Dockerfile.api           # حاوية API
├─ README-BACKEND.md        # توثيق API الخلفية
└─ README_ARABIC.md         # هذه الوثيقة
```

## 📦 **أوامر npm | NPM Scripts**

- dev: تشغيل الخادم أثناء التطوير
- build: إنشاء إنتاجي
- preview: معاينة البناء محلياً
- lint: فحص الكود

## 📊 **Power BI**

- الأدلة: `POWERBI_SETUP.md`, `POWERBI_WORKSPACE_SETUP.md`, `POWERBI_TOKEN_SETUP.md`, `powerbi-api-guide.md`, `POWERBI_ERROR_FIX.md`
- خدمة الواجهة الأمامية: `src/services/powerBIService.ts` والخطاف `src/hooks/usePowerBI.ts`
- تأكد من إعداد تطبيق Azure AD والصلاحيات والرموز المضمنة حسب الأدلة.

## 🔐 **المصادقة والقياسات الحيوية | Authentication & Biometric**

- مزود Supabase: `src/providers/supabaseAuthProvider.ts`
- صفحات الدخول: `src/pages/login`
- WebAuthn/القياسات الحيوية: المكوّن `src/components/BiometricAuth.tsx` وخدمة API في `src/api/services/webAuthnService.ts`
- راجع: `BIOMETRIC_AUTHENTICATION_GUIDE.md`

## 🌐 **التدويل | Internationalization**

- الضبط في `src/i18n.ts` مع دعم العربية RTL والإنجليزية
- وثيقة عربية موسعة: `README_ARABIC.md`

## 🎨 **التخطيطات والسمات | Layouts & Theming**

- التخطيطات: `MinimalistLayout`, `SimplifiedLayout`, `MainLayout` ضمن `src/components/layout`
- أداة التبديل بين السمات والعلامة التجارية: راجع `ThemeSwitcher.tsx`, `ThemeSettings.tsx`
- ألوان العلامة: الأزرق الفدرالي، الأسود، الأزرق المصري، الأحمر، الأزرق السماوي

## 🎨 **فلسفة التصميم | Design Philosophy**

### **تصميم يركز على الإدارة العليا | Executive-First Design**
- واجهة نظيفة وغير مزدحمة
- التركيز على المعلومات الاستراتيجية  
- نظام ألوان مهني
- تنقل بديهي للمدراء التنفيذيين المشغولين

### **حديث ومتجاوب | Modern & Responsive**
- تصميم متوافق مع الهواتف المحمولة
- أوقات تحميل سريعة
- رسوم متحركة سلسة
- متوافق مع إمكانية الوصول

### **دعم العربية الكامل | Full Arabic Support**
- تخطيط RTL تلقائي
- خطوط عربية محسّنة
- ترجمات مهنية
- تجربة مستخدم محلية

---

## 📊 **قاعدة البيانات | Database Schema**

### **الجداول الرئيسية | Main Tables**
- **👥 users** - المستخدمون والأدوار
- **🎯 projects** - المشاريع الاستراتيجية  
- **✅ tasks** - المهام والمبادرات
- **📅 timeline_events** - أحداث الجدول الزمني
- **💬 comments** - التعليقات والتعاون
- **📊 kpis** - مؤشرات الأداء الرئيسية

### **الميزات المتقدمة | Advanced Features**
- **🛡️ Row Level Security** - أمان على مستوى الصفوف
- **⚡ Real-time Updates** - تحديثات فورية
- **🔄 Automatic Timestamps** - طوابع زمنية تلقائية
- **📈 Performance Indexes** - فهارس محسّنة للأداء

---

<div align="center">

**🏢 مبني بـ ❤️ للتميز التنفيذي | Built with ❤️ for Executive Excellence**

*هذه البوابة تقدم القوة الاستراتيجية بدون فوضى تشغيلية - بالضبط ما تحتاجه الإدارة العليا.*

*This portal delivers strategic power without operational clutter - exactly what C-level executives need.*

**المؤلف | Author: Raneem Althaqafi (@RaneemQasim5251)**

</div>