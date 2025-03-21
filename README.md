1. Loyiha haqida qisqacha tushuntirish
Model kredit arizalarining tasdiqlanishi yoki rad etilishini bashorat qilish uchun qurilgan.
Kaggle platformasidan olingan dataset asosida ishlangan.
SVM (Support Vector Machine) algoritmi ishlatilgan.
2. Foydalanilgan dataset haqida
Manba: Kaggle
Jadval ustunlari:
ApplicantIncome – Kredit oluvchining daromadi
CoapplicantIncome – Qo‘shimcha daromad
LoanAmount – Kredit miqdori
Credit_History – Oldingi kredit tarixining mavjudligi (0 yoki 1)
Loan_Status – Kredit tasdiqlanganmi yoki yo‘q (0 – rad etilgan, 1 – tasdiqlangan)
3. Model yaratish bosqichlari
Ma’lumotlarni tozalash:
object turidagi ustunlar raqamlarga o‘g‘irlandi.
Bo‘sh qiymatlar to‘ldirildi.
Ma’lumotlarni taqsimlash:
Dataset train-test split bilan 80%-20% nisbatda bo‘lindi.
Modelni o‘qitish:
SVM (linear kernel) modeli bilan ishlangan.
Natija:
Trening to‘g‘riligi: ~79.8%
Test to‘g‘riligi: ~83.3%
