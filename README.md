# 🌿 יומן שוק ירקות — PWA

אפליקציית מעקב רכישות ירקות בשוק. עובדת במצב אופליין, ניתן להתקין על מסך הבית של האייפון.

## קבצים בפרויקט

```
shuk-pwa/
├── index.html        ← האפליקציה הראשית
├── manifest.json     ← הגדרות PWA
├── sw.js             ← Service Worker (מאפשר אופליין)
└── icons/
    ├── icon-192.png
    ├── icon-512.png
    ├── apple-touch-icon.png
    └── favicon-32.png
```

## פריסה ב-GitHub Pages (חינמי)

### שלב 1 — צור חשבון GitHub
כנס ל-https://github.com וצור חשבון אם אין לך.

### שלב 2 — צור repository חדש
1. לחץ על ״New repository״
2. שם: `shuk-pwa` (או כל שם אחר)
3. סמן ״Public״
4. לחץ ״Create repository״

### שלב 3 — העלה את הקבצים
1. בדף ה-repository לחץ ״uploading an existing file״
2. גרור את כל הקבצים (כולל תיקיית icons)
3. לחץ ״Commit changes״

### שלב 4 — הפעל GitHub Pages
1. כנס ל-Settings של ה-repository
2. בסרגל השמאלי בחר ״Pages״
3. תחת Source בחר ״Deploy from a branch״
4. Branch: main / (root)
5. לחץ Save

### שלב 5 — קבל את הקישור
אחרי כ-2 דקות האפליקציה זמינה בכתובת:
`https://USERNAME.github.io/shuk-pwa`

## הוספה לאייפון

1. פתח את הקישור **ב-Safari** (לא Chrome)
2. לחץ על כפתור השיתוף ⬆️ (בתחתית)
3. בחר ״הוסף למסך הבית״
4. לחץ ״הוסף״

האפליקציה תופיע על מסך הבית עם אייקון ירוק 🌿 ותעבוד גם בלי אינטרנט.
