Qo'lyozma Tanib-Olish Modeli
Ushbu repozitoriy TensorFlow va Keras yordamida yaratilgan qo'lyozma tanib olish modelini o'z ichiga oladi. Model Landlord Handwriting Recognition dataset'ida o'qitilgan bo'lib, qo'lyozma matnlarini tasvirlardan tanib olish uchun Konvolyutsion Neyron Tarmoq (CNN) va Bidireksional LSTM (Long Short-Term Memory) tarmoqlari birlashmasini ishlatadi.

Loyihaning Maqsadi
Ushbu loyiha qo'lyozma tarzida yozilgan ism va familiyalarni tasvirlardan tanib olishni maqsad qiladi. Model tasvirlardan xususiyatlarni olish uchun Konvolyutsion Neyron Tarmoq (CNN) va yozuvlarni (so'zlarni) taxmin qilish uchun Bidireksional LSTM tarmoqlarini ishlatadi. Modelni o'qitishda CTC (Connectionist Temporal Classification) yo'qotish funksiyasi ishlatilgan.

Dataset
Model Landlord Handwriting Recognition dataset'ida o'qitilgan, bu dataset qo'lyozma ism va familiyalarini o'z ichiga oladi. Dataset quyidagi fayllardan tashkil topgan:

written_name_train_v2.csv: O'qitish ma'lumotlari, fayl nomlari va tegishli yorliqlar bilan birga.
written_name_validation_v2.csv: Tasdiqlash ma'lumotlari, fayl nomlari va tegishli yorliqlar bilan birga.
written_name_test_v2.csv: Test ma'lumotlari, fayl nomlari, ularning ustidan taxminlar chiqariladi.
Tasvirlar o'qitish, tasdiqlash va test ma'lumotlari uchun tegishli papkalarda (train, validation, test) joylashgan.
Talablar
Loyihani ishga tushirish uchun quyidagi kutubxonalar talab qilinadi:

Python 3.x
TensorFlow
Keras
OpenCV
Pandas
NumPy
Matplotlib
