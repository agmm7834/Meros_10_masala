# Mavzu: OOP – Meros (Inheritance) va `super()` funksiyasi

---

**1-masala.**
`Animal` sinfi yarating. Uning `name` atributi va `speak()` metodi bo'lsin. `speak()` metodi `"..."` chiqarsin. Shu sinfdan meros olib `Cat` sinfini yarating. `Cat` sinfiga `color` atributini qo'shing. `speak()` metodini qayta yozing: avval `super().speak()` chaqirilsin, keyin `"Miyov!"` chiqarsin.

---

**2-masala.**
`Person` sinfi yarating. Uning `name` va `age` atributlari bo'lsin. `introduce()` metodi `"Mening ismim: Ali"` ko'rinishida chiqarsin. Shu sinfdan meros olib `Student` sinfini yarating. `Student` sinfiga `faculty` atributini qo'shing. `introduce()` metodini qayta yozing: avval `super().introduce()` chaqirilsin, keyin `"Men ... fakultetida o'qiyman"` chiqarsin.

---

**3-masala.**
`Vehicle` sinfi yarating. Uning `brand` va `speed` atributlari bo'lsin. `move()` metodi `"Harakatlanmoqda..."` chiqarsin. Shu sinfdan meros olib `Car` sinfini yarating. `Car` sinfiga `doors` (eshiklar soni) atributini qo'shing. `move()` metodini qayta yozing: avval `super().move()` chaqirilsin, keyin `"Avtomobil ... km/h tezlikda ketmoqda"` chiqarsin.

---

**4-masala.**
`Worker` sinfi yarating. Uning `name` va `salary` atributlari bo'lsin. `info()` metodi ism va oylik maoshni chiqarsin. Shu sinfdan meros olib `Driver` sinfini yarating. `Driver` sinfiga `car_type` atributini qo'shing. `info()` metodini qayta yozing: avval `super().info()` chaqirilsin, keyin haydovchi qaysi turdagi mashina haydashini chiqarsin.

---

**5-masala.**
`Phone` sinfi yarating. Uning `brand` va `model` atributlari bo'lsin. `call()` metodi `"Qo'ng'iroq qilinmoqda..."` chiqarsin. Shu sinfdan meros olib `Smartphone` sinfini yarating. `Smartphone` sinfiga `os` (operatsion tizim) atributini qo'shing. `call()` metodini qayta yozing: avval `super().call()` chaqirilsin, keyin `"... orqali internet qo'ng'irog'i amalga oshirildi"` chiqarsin.

---

**6-masala.**
`Shop` sinfi yarating. Uning `name` va `address` atributlari bo'lsin. `open()` metodi `"Do'kon ochildi"` chiqarsin. Shu sinfdan meros olib `OnlineShop` sinfini yarating. `OnlineShop` sinfiga `website` atributini qo'shing. `open()` metodini qayta yozing: avval `super().open()` chaqirilsin, keyin `"Sayt manzili: ..."` chiqarsin.

---

**7-masala.**
`BankAccount` sinfi yarating. Uning `owner` va `balance` atributlari bo'lsin. `deposit(amount)` metodi berilgan summani balansga qo'shsin va yangi balansni chiqarsin. Shu sinfdan meros olib `SavingsAccount` sinfini yarating. `SavingsAccount` sinfiga `bonus` (foiz, masalan 10%) atributini qo'shing. `deposit()` metodini qayta yozing: avval `super().deposit()` chaqirilsin, keyin bonus foiz ham hisoblab balansga qo'shilsin va yangi balans chiqarilsin.

---

**8-masala.**
`Game` sinfi yarating. Uning `title` va `genre` atributlari bo'lsin. `start()` metodi `"O'yin boshlandi: ..."` chiqarsin. Shu sinfdan meros olib `OnlineGame` sinfini yarating. `OnlineGame` sinfiga `max_players` atributini qo'shing. `start()` metodini qayta yozing: avval `super().start()` chaqirilsin, keyin `"Maksimal o'yinchilar soni: ..."` chiqarsin.

---

**9-masala.**
`Teacher` sinfi yarating. Uning `name` va `subject` atributlari bo'lsin. `teach()` metodi `"... dars o'tmoqda"` chiqarsin. Shu sinfdan meros olib `OnlineTeacher` sinfini yarating. `OnlineTeacher` sinfiga `platform` atributini qo'shing (masalan: YouTube, Udemy). `teach()` metodini qayta yozing: avval `super().teach()` chaqirilsin, keyin `"Dars ... platformasida o'tilmoqda"` chiqarsin.

---

**10-masala.**
`Character` sinfi yarating. Uning `name` va `health` atributlari bo'lsin. `attack()` metodi `"Hujum qilindi!"` chiqarsin. Shu sinfdan meros olib `Warrior` sinfini yarating. `Warrior` sinfiga `weapon` atributini qo'shing. `attack()` metodini qayta yozing: avval `super().attack()` chaqirilsin, keyin `"Warrior ... qurol bilan ... ga zarba berdi!"` chiqarsin.
