Kredit Mavqeyini Bashorat Qilish (Loan Status Prediction)
📌 Loyiha haqida
Ushbu loyiha kredit olish arizalarini tasdiqlash yoki rad etishni bashorat qilish uchun mashinani o‘rganish modelidan foydalanadi. Model SVM (Support Vector Machine) algoritmiga asoslangan bo‘lib, u kredit olish bo‘yicha qaror qabul qilish jarayonini avtomatlashtirishga yordam beradi.

📊 Ma’lumotlar to‘plami

Ushbu dataset Kaggle platformasidan olingan.
Kredit oluvchilar haqida turli ma’lumotlarni o‘z ichiga oladi (daromad, ish turi, qarz tarixi va h.k.).
Toza va tayyor ma’lumotlar loan_dataset.csv faylida saqlangan.
🛠 Foydalanilgan texnologiyalar

Dasturlash tili: Python
Ma’lumotlarni tahlil qilish: Pandas, NumPy
Vizualizatsiya: Matplotlib, Seaborn
Mashinalarni o‘rganish: Scikit-learn (SVM modeli)
Ma’lumotlar bazasi: PostgreSQL
📈 Model yaratish bosqichlari

Ma’lumotlarni tayyorlash – Ma’lumotlar tozalanib, kerakli o‘zgaruvchilarga ajratildi.
Kategoriya ustunlarini kodlash – Object tipidagi ustunlar raqamli qiymatlarga o‘tkazildi.
Ma’lumotlarni taqsimlash – train_test_split() orqali modelni o‘qitish va sinash uchun ajratildi.
Modelni o‘qitish – SVM (linear kernel) yordamida model yaratildi va o‘qitildi.
Modelni baholash – Trening va test ma’lumotlari uchun aniqlik baholandi.
🎯 Natijalar

Trening aniqligi: ~79%
Test aniqligi: ~83%
