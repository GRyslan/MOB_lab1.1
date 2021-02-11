ПМС Лаб 1.1
Для вирішення лабораторних робіт було обрано мову Kotlin 

Крок 5(Правильно визначений organization identifier)
package name було записано ,як ua.kpi.comsys.iv8305

Крок 6(Наявність іконки додатка всіх необхідних правильних розмірів)
Для створення іконки було знайдено певне зображення ,та за допомогою Android studio та послідовності File-New-Immage Asset з'явилося вікно ,в якому було змінено стандартний вид програми
![image](https://user-images.githubusercontent.com/45923857/107675672-fa9b9700-6ca0-11eb-80c7-09390f0bdfe0.png)
![image](https://user-images.githubusercontent.com/45923857/107675864-2e76bc80-6ca1-11eb-8f21-a1fb6fd7c1c4.png)

Крок 7(Додаток побудований на основі навігаційної моделі вкладок)
В Android Studio було використано Bottom Navigation Activity при створенні проекту з трьома фрагментами Home ,Dashboards ,Notifications
![image](https://user-images.githubusercontent.com/45923857/107676250-962d0780-6ca1-11eb-8de7-8a01d9bf701e.png)
фрагмент Dashboards був видалений після створення 

Крок 10-11(Наявність правильно налаштованої мітки з персональними даними студента)
Мітка та персональні дані налаштовувалися в фрагменті home(fragment_lab11.xml) . 
Персональні дані були створені за допомогою android:text="Головенець Руслан\nГрупа ІВ-83\nЗК ІВ-8305" з gravity :center  
а також за допомогою supportActionBar?.hide() в MainActivity.kt було приховано верхній надпис програми ,так як при вирівнюванні по центру він не враховувався

![image](https://user-images.githubusercontent.com/45923857/107677371-db9e0480-6ca2-11eb-97bd-b16f07eb04d0.png)

Крок 12 (Вказана назва та визначене зображення для вкладки, що налаштовувалася )
За замовчуванням на першій вкладці стояла назва Home та картина хатинки,що було змінено ,як показано на скріншоті нижче 
![image](https://user-images.githubusercontent.com/45923857/107678285-e016ed00-6ca3-11eb-8b52-ddc8fa88a146.png)
Другий фрагмент залишився незмінним 
![image](https://user-images.githubusercontent.com/45923857/107678460-19e7f380-6ca4-11eb-9d4a-0489626379dc.png)

Крок 13(Проект збирається та запускається)
Проект збирається та запускається на емуляторі ,як показано на скріншоті нижче
![image](https://user-images.githubusercontent.com/45923857/107678643-561b5400-6ca4-11eb-87a3-6ba5ce2b9b44.png)

Крок 14(Наявність .gitignore)
Файли .gitignore були створені автоматично  при створенні new project

