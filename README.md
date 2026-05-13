# תרגיל 2 — Prompt Engineering

## מטרת התרגיל
לכתוב Prompt מקצועי ומדויק, שיגרום לכלי AI לייצר מערכת אמיתית מבוססת קוד לפתרון צורך עסקי/ארגוני.

---

# מה עליכם לעשות

עליכם להשתמש בכלי AI לבחירתכם כדי לייצר מערכת לניהול משגיחים במכללה.

המערכת צריכה להתבסס על:
- קובץ מבחנים
- קובץ משגיחים
- אילוצים וזמינויות
- שיבוץ חכם של משגיחים

---

# מטרת התרגיל האמיתית

המטרה אינה רק "לייצר קוד".

המטרה היא ללמוד:
- איך לכתוב Prompt מקצועי
- איך לתת Context נכון
- איך לפרק מערכת גדולה לדרישות
- איך לבצע Iteration
- איך לעבוד נכון עם AI בתהליך פיתוח

---

# מה למדנו בשיעורים

מהמצגות למדנו על:
- AI Developer Mindset :contentReference[oaicite:0]{index=0}
- Prompt Engineering :contentReference[oaicite:1]{index=1}
- עבודה עם Context
- Role / Goal / Constraints
- Iteration
- Best Practices
- AI Hallucinations :contentReference[oaicite:2]{index=2}

---

# דרישות המערכת

המערכת צריכה לכלול לפחות:

## 1. ניהול מבחנים
- תאריך מבחן
- שעת התחלה/סיום
- חדר
- מספר נבחנים
- מועד א/ב/ג
- התאמות מיוחדות
- חדר שקט
- מבחן מחשבים

---

## 2. ניהול משגיחים
- פרטי משגיח
- זמינות
- אילוצים
- מקסימום שעות עבודה
- יכולת הקראה
- התאמה לחדר שקט
- סטטוס פעיל/לא פעיל

---

## 3. שיבוץ חכם
המערכת צריכה לדעת:
- למנוע חפיפות
- לבדוק זמינות
- למצוא משגיח פנוי
- להציע התאמה אוטומטית
- לזהות בעיות שיבוץ

---

## 4. Dashboard
המערכת צריכה להציג:
- מצב מבחנים
- שיבוצים
- בעיות
- משגיחים חסרים
- פילטרים
- סטטיסטיקות בסיסיות

---

# קבצים לתרגיל

השתמשו בקבצים:
- exams_demo.csv
- invigilators_demo.csv

---

# דרישות Prompt

ה-Prompt שלכם חייב לכלול:

## Role
מי ה-AI אמור להיות

דוגמה:
```text
You are a senior full-stack engineer.
```

---

## Goal
מה המערכת צריכה לעשות

---

## Context
מה הרקע העסקי

---

## Constraints
דרישות טכניות

דוגמאות:
- React
- Tailwind
- Responsive
- Clean UI
- CSV import

---

## Output Format
איך לקבל את התוצאה

דוגמה:
```text
Generate:
- Database schema
- Frontend structure
- Dashboard layout
- API design
```

---

# המלצות לעבודה נכונה

## לעבוד בשלבים
לא לבקש:
```text
Build everything
```

אלא:
1. Build database schema
2. Build dashboard
3. Build assignment engine
4. Improve UI
5. Add validations

---

## לבצע Iteration
לשפר Prompt בהדרגה.

AI לא תמיד ייתן תוצאה טובה בניסיון ראשון.

---

## לבדוק תוצאות
לא לסמוך על AI בצורה עיוורת.

בדקו:
- קוד
- UI
- Logic
- APIs
- התאמות לדרישות

---

# רעיונות לשדרוגים

אפשר להוסיף:
- Email notifications
- WhatsApp integration
- Dark mode
- Calendar view
- Drag & Drop
- AI recommendations
- Authentication
- Mobile support
- Real-time updates

---

# מה להגיש

יש להגיש:

## 1. Prompt מלא
קובץ:
```text
prompt.txt
```

---

## 2. קישור לפרויקט
לדוגמה:
- StackBlitz
- GitHub
- Replit
- Vercel

---

## 3. צילום מסך של המערכת

---

## 4. הסבר קצר
מה הצליח:
- מה AI בנה טוב
- מה היה צריך לתקן
- אילו בעיות היו
- איך שיפרתם את ה-Prompt

---

# דגשים חשובים

## המטרה אינה מושלמות
המטרה היא ללמוד:
- לעבוד נכון עם AI
- לחשוב כמו Software Engineer
- להבין איך לנהל תהליך פיתוח מודרני

---

# בונוס למתקדמים

מי שרוצה יכול להוסיף:
- Auto Scheduling
- Conflict Detection
- Smart Matching Algorithm
- AI Assistant בתוך המערכת
- Role Management
- Audit Logs
- Reports

---

# כלי AI מומלצים

אפשר להשתמש ב:
- ChatGPT
- [Google AI Studio](https://aistudio.google.com?utm_source=chatgpt.com)
- [Cursor](https://www.cursor.com?utm_source=chatgpt.com)
- [StackBlitz](https://stackblitz.com?utm_source=chatgpt.com)
- [Replit](https://replit.com?utm_source=chatgpt.com)
- [GitHub Copilot](https://github.com/features/copilot?utm_source=chatgpt.com)

---

# שקף משופר לתרגיל

## תרגיל 2 — Prompt Engineering

כתבו Prompt מקצועי שיגרום לכלי AI לבנות מערכת אמיתית לניהול משגיחים במכללה.

המטרה:
- עבודה נכונה עם AI
- כתיבת Prompts מקצועיים
- בניית מערכת מבוססת Requirements
- Iteration ושיפור תוצאות

הגישו:
- Prompt מלא
- קישור לפרויקט
- צילום מסך
- הסבר קצר על התהליך
