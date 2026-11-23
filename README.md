# אבולוציה זו לא מילה גסה – אתר הפודקאסט והספר

אתר סטטי פשוט (HTML + CSS בלבד, בלי בנייה ובלי התקנות). כל קובץ אפשר לערוך ישירות בעורך של GitHub.

## העלאה ל-GitHub Pages
1. צרו repository חדש ב-GitHub והעלו את כל תוכן התיקייה (Add file → Upload files, או `git push`).
2. Settings → Pages → Source: `Deploy from a branch`, Branch: `main`, תיקייה: `/ (root)`.
3. אחרי כדקה האתר יעלה בכתובת `https://<שם-משתמש>.github.io/<שם-הריפו>/`.

## מבנה
| קובץ | תוכן |
|---|---|
| `index.html` | דף הבית |
| `episodes.html` | רשימת הפרקים |
| `episodes/*.html` | דף לכל פרק |
| `about.html` | אודות |
| `book.html` | הספר (placeholder) |
| `logo.html` | הסבר על הלוגו |
| `style.css` | כל העיצוב |
| `assets/` | תמונות |

## החלפת תמונות
- **לוגו:** `assets/logo.jpg`
- **תמונה שלי:** `assets/me.jpg`
להחלפה – העלו קובץ חדש באותו שם בדיוק (אותיות קטנות).

## הוספת פרק
ראו `episodes/_TEMPLATE.html.txt`.

