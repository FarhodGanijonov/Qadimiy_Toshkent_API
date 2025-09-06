Qadimiy_Toshkent_API

Historical Site — bu Toshkent shahridagi tarixiy obidalar haqidagi ma’lumotlarni jamlagan platforma.
Loyiha 1000+ tarixiy obyektni o‘z ichiga oladi va foydalanuvchilarga tezkor qidiruv imkoniyatini taqdim etadi.


1. Loyihaning asosiy vazifalari

  Toshkentdagi tarixiy obidalar ma’lumot bazasi yaratish.
  
  Foydalanuvchilarga obyektlar bo‘yicha tezkor qidiruv funksiyasini taqdim etish.
  
  Shahar tarixiy resurslarini bir joyga jamlab, onlayn platforma ko‘rinishida taqdim etish.

2. Foydalanilgan texnologiyalar

  Python (Django)
  
  Django REST Framework (DRF)
  
  PostgreSQL — asosiy ma’lumotlar bazasi
  
  Docker — containerized deployment


3. Swagger’dan foydalanish

  API hujjatlari Swagger UI orqali taqdim etilgan.
  Swagger sahifasiga kirish uchun quyidagiga havolaga o‘ting:
  
  http://subdomain.eskitoshkent.uz/swagger/
  
  Swagger sahifasida:
  
  Barcha endpoint’lar ro‘yxatini ko‘rishingiz mumkin.
  
  Parametrlar va javob misollari bilan tanishish mumkin.
  
  “Try it out” tugmasi orqali API’ni bevosita sinab ko‘rish mumkin.


4. Ishga tushirish (Docker orqali)
  git clone https://github.com/FarhodGanijonov/Qadimiy_Toshkent_API.git
  cd Qadimiy_Toshkent_API
  "docker compose up --build"
  
  
  Server ishga tushgandan so‘ng:
  
  API: http://localhost:8000/api/
  
  Swagger: http://localhost:8000/swagger/

👨‍💻 Muallif

Farhod Ganijonov
Backend Developer (Python/Django, DRF, PostgreSQL, Docker)
