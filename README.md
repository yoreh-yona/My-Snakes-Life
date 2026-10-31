# My Snake's Life · החיים של הנחש שלי

יומן צבעוני לילדים שמגדלים נחשים, בעברית ובאנגלית: תעודת זהות לכל נחש, ארוחות, השלות עור, ניקיון, יומן, אלבום תמונות, לוח שנה, ומשימות ועובדות לפי סוג הנחש.

A colorful diary for kids who keep snakes, in Hebrew and English.

## התקנה באנדרואיד
1. בטלפון, ב־Chrome, נכנסים ל־`github.com/yoreh-yona/My-Snakes-Life/releases/latest`.
2. מורידים את `my-snakes-life.apk` ופותחים אותו.
3. בפעם הראשונה הטלפון יבקש לאשר "התקנה ממקורות לא ידועים" עבור Chrome.
4. גרסה חדשה מתקינים באותה דרך, והיא נכנסת מעל הקודמת בלי למחוק נתונים.

## התקנה באייפון
1. ב־Safari נכנסים ל־`https://yoreh-yona.github.io/My-Snakes-Life/`
2. לוחצים על כפתור השיתוף ובוחרים **הוסף למסך הבית**.

## גיבוי
כל הנתונים נשמרים בטלפון עצמו. בתחתית האפליקציה יש **שמור גיבוי** ו**טען גיבוי**.

## איך זה בנוי
- `www/index.html` — האפליקציה. `www/lang-en.js` — הטקסטים באנגלית, לפי המקור בעברית.
- `.github/workflows/android.yml` — בונה APK עם Capacitor בכל עדכון ומפרסם אותו ב־Releases.
- `.github/workflows/pages.yml` — מפרסם את `www/` ב־GitHub Pages לאייפון.
- `android-signing/debug.keystore` — מפתח החתימה. נשמר במאגר כדי שכל גרסה תותקן מעל הקודמת.
- מזהה האפליקציה: `com.yorehyona.mysnakeslife`.
