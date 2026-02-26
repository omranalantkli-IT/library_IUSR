# شرح آلية العمل باستخدام Git

## Branches
- main: النسخة المستقرة
- feature/*: لكل ميزة Branch خاص
  مثال: feature/books-page

## خطوات العمل
1. pull آخر تحديث:
   git pull origin main
2. إنشاء فرع:
   git checkout -b feature/books-page
3. التعديلات ثم commit واضح:
   git add .
   git commit -m "Add books page layout"
4. push:
   git push origin feature/books-page
5. افتح Pull Request على GitHub
6. بعد المراجعة يتم merge إلى main