# 🌍 Global Health Indicators Dashboard | Power BI Project

**المشروع ده بيقدم تحليل تفاعلي** لبيانات الصحة العالمية، بهدف كشف الروابط بين الإنفاق الحكومي على الصحة (Health Expenditure) ومؤشرات جودة الحياة زي معدل عمر الفرد (Life Expectancy) ومعدلات الوفيات.

---

### 🎥 Project Demo (فيديو عرض المشروع)

> **ملاحظة:** الفيديو بيوضح سلاسة التنقل بين الصفحات وتفاعل الـ Dynamic Cards مع الفلتر.

![Project Video](./2026-03-03 04-41-52.mp4)

---

### 🚀 المميزات التقنية (Technical Highlights)

**خلال بناء الـ Dashboard دي، ركزت على تقديم تجربة مستخدم (UX) احترافية:**

* **Dynamic Measures (DAX):** * استخدمت دوال `SELECTEDVALUE` و `HASONEVALUE` لعمل Dynamic Titles و Cards تتفاعل بذكاء مع الـ Slicers.
    * عملت Measure خاص بالألوان (Conditional Formatting) عشان الـ Visuals تتلون تلقائياً حسب الأداء.
* **Deep-Dive Analysis:** * خاصية الـ **Drill-Through** عشان تقدر تروح من نظرة عامة لتقرير تفصيلي عن دولة معينة بضغطة واحدة.
    * استخدام الـ **Scatter Plot** لتحليل الـ ROI (العائد على الاستثمار) بين الإنفاق الصحي والنتائج الملموسة.
* **Data Governance:** * تطبيق الـ **Row-Level Security (RLS)** لضمان إن كل مسؤول يشوف فقط بيانات المنطقة الجغرافية الخاصة به.
* **Visual Variety:** * استخدام Gauge Charts، Map Visuals، و Custom Tooltips لتبسيط البيانات المعقدة.

---

### 📊 هيكل البيانات (Dataset Structure)

البيانات المستخدمة بتغطي الفترة من **2000 إلى 2020** وتشمل:
* **Health Exp:** الإنفاق الصحي كنسبة من الناتج المحلي.
* **Life Expectancy:** متوسط العمر المتوقع عند الولادة.
* **Mortality Rates:** معدلات وفيات الأمهات والأطفال (Under 5, Infant, Neonatal).
* **Disease Prevalence:** معدلات انتشار HIV و Tuberculosis.

---

### 🛠️ الأدوات المستخدمة (Tools Used)

* **Power BI Desktop:** للتصميم وبناء الـ Data Model.
* **DAX:** للعمليات الحسابية المتقدمة.
* **Power Query (M):** لتنظيف وتجهيز البيانات (ETL).
* **GitHub:** لتوثيق المشروع (Documentation).

---

### 📁 محتويات المستودع (Repository Contents)

1.  **`Global_Health_Data.pbix`**: ملف الـ Power BI الأصلي.
2.  **`world_health_data.csv`**: قاعدة البيانات المستخدمة.
3.  **`Project_Video.mp4`**: فيديو شرح تفاعلي للمشروع.

---

**حابب أسمع رأيكم!** لو عندك أي استفسار عن الـ DAX Logic اللي استخدمته، متترددش تبعتلي.
