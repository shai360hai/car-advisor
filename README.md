# אתר ליווי ברכישת רכב

## מה יש כאן
- `index.html` — האתר (קובץ יחיד, מוכן לעלייה)
- `docs/01-שירותים-ותמחור.md` — מבנה השירות, תמחור, וצ'קליסט הקמה
- `docs/02-שיווק-ותוכן.md` — תוכנית שיווק ו-20 רעיונות לתוכן

## לפני שמעלים — 2 דברים לשנות ב-index.html
1. חפש `CHANGE-ME@example.com` והחלף באימייל (לא במייל העבודה!)
2. ודא שמספר הטלפון נכון (מופיע ב-3 מקומות: nav, tel:, wa.me)

## צפייה מקומית
פשוט פתח את index.html בדפדפן, או:
```
python3 -m http.server 8000
```

## העלאה ל-GitHub Pages
```
git init
git add .
git commit -m "Car buying advisor site"
git branch -M main
git remote add origin https://github.com/USERNAME/REPO.git
git push -u origin main
```
ואז: Settings → Pages → Source: `main` / root → Save
