# Python Sqlite3 connect the example is great

![data](https://github.com/themusharraf/PySqlite3-Lesson/assets/122869450/70c53cf1-6d05-4ebf-924c-bbf9ffa7298c)

Python dasturlash tilida SQLite ma'lumotlar bazasiga malumotlarni yozib berish uchun sqlite3 modulidan foydalanishingiz mumkin.
Quyidagi repository bilan malumot bazasini o'rganib chiqing o'ylaymanki bu sizga foydali buladi:


SQLite - bu alohida server jarayonini talab qilmaydigan engil diskga asoslangan ma'lumotlar bazasini 
ta'minlovchi va SQL so'rovlar tilining nostandart varianti yordamida ma'lumotlar bazasiga kirish 
imkonini beruvchi C kutubxonasi. Ba'zi ilovalar ichki ma'lumotlarni saqlash uchun SQLite dan foydalanishi mumkin.
SQLite yordamida dasturni prototipini yaratish va keyin kodni PostgreSQL yoki Oracle kabi kattaroq maʼlumotlar bazasiga oʻtkazish ham mumkin.

```sql
import sqlite3
con = sqlite3.connect("database.db")

con.commit()
con.close()
```

