# Library Index

| Template | Task | Variables | Version | Status |
| :--- | :--- | :--- | :--- | :--- |
| IT-Resolve-Ticket | Resolve a support ticket | INPUT_TEXT · LANGUAGE · TONE · MAX_WORDS · FACTS | v1 | Approved |
| IT-Route-Tickets | Route tickets to teams | INPUT_TEXT · LANGUAGE · TONE · MAX_WORDS · FACTS | v1 | Approved |
| IT-Notice-Maintenance | Planned maintenance notice | INPUT_TEXT · LANGUAGE · TONE · MAX_WORDS · FACTS | v1 | Approved |
| IT-Mask-Ticket | Clean a ticket before pasting | INPUT_TEXT · LANGUAGE · MAX_WORDS | v1 | Approved |
| IT-Handoff-Ticket | Senior technician handoff | INPUT_TEXT · LANGUAGE · TONE · MAX_WORDS · FACTS | v1 | Approved |

*ملاحظة: تحولت الحالة إلى Approved بعد تحقيق الدرجات 5/5 و 6/6 و 5/5 في تقرير الاختبارات.*

## الكتل المشتركة (Shared blocks)

- `blocks/IT-Facts-v1_2026_10_15.md`: حقائق مكتب الدعم التقني (7 حقائق).

## ملف القواعد (Rules)

- `rules/IT-Rules-v1_2026_10_15.md`: قواعد السلامة الخمس الثابتة.

## قيم [LANGUAGE] الخمس

| القيمة | المعنى |
| :--- | :--- |
| Arabic | الرد بالعربية فقط |
| English | الرد بالإنجليزية فقط |
| Automated (الافتراضية) | الرد باللغة الرئيسية للمدخل |
| Bilingual | نسختان منفصلتان: العربية ثم الإنجليزية |
| Mixed | رد واحد يمزج العربية والإنجليزية |

## سجل التغييرات (Change log)

- **v1 (2026_10_15):** الإصدار الأول للمكتبة واجتياز جميع القوالب لاختبارات الجودة بنجاح.