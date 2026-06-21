# مندي أبو نورة — صفحة الهبوط (Linktree)

صفحة هبوط بأسلوب Linktree لمطعم **مندي أبو نورة**، تجمع كل الروابط في مكان واحد:
المنيو، خدمة العملاء (واتساب)، موقع الفرع، تحميل التطبيق، وحسابات السوشال ميديا.

- موقع مباشر: https://mandiabonoura.com/lander
- صفحة واحدة ثابتة (HTML/CSS) — بدون أي إطار عمل، خفيفة وسريعة.
- متجاوبة mobile-first، RTL عربي، بهوية البراند (أسود `#161314` / أحمر `#BD2124` / ذهبي `#E8B14C`).
- SEO كامل: Meta + Open Graph + Twitter Cards + JSON-LD (Restaurant) + sitemap + robots.

## البنية
- `index.html` — الصفحة.
- `menu.pdf` — ملف المنيو.
- `assets/` — اللوقو، الأيقونات، صورة المشاركة (OG).
- `vercel.json` — توجيه `/lander` + ترويسات الكاش والأمان.
- `sitemap.xml`, `robots.txt`, `site.webmanifest`.

## التعديل
كل الروابط داخل `index.html` كـ `href`. لتحديث رابط أندرويد أو أي حساب، عدّل الرابط وادفع التغيير — Vercel ينشر تلقائياً.
