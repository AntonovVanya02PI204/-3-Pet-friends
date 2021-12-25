# -3-Pet-friends

Задание:
1. Зарегистрироваться: https://petfriends1.herokuapp.com
2. Ознакомиться с документацией API: https://petfriends1.herokuapp.com/apidocs/#/
3. Написать приложение содержащие функции работы с API:
реализовать методы:
GET,
POST,
PUT,
DELETE
4. Написать тесты для функций работы с API
Тесты должны содержать позитивные и негативные сценарии
Необходимо сделать параметризацию
Необходимо использовать фикстуры
5. Запустить тесты и сделать скриншот
6. Создаем файл README.md, с описанием приложения
7. Загружаем файлы на Github

Создание приложения для работы с API
Чтобы написать приложения для работы с API, нам потребуется использовать ряд функций. Все функции, которые были испольхзованы для работы с API содержатся в файлах выше. Для наглядного представления были добавлены скриншоты выполнения всех функций. В работе была использована библиотека pytest

Авторизация и просмотр интерфейса: 

![image](https://user-images.githubusercontent.com/92279258/147342107-ff216790-ba5a-4904-a8ae-c1cfc3a1b5e3.png)

![image](https://user-images.githubusercontent.com/92279258/147342120-09ac0249-1bb2-46d9-9d9e-d4e58e7ffbaa.png)

![image](https://user-images.githubusercontent.com/92279258/147342159-1f7c4a1b-53ad-4f74-8d25-bad8a1c0a908.png)

Скриншоты выполнения всех функций: 

Создание карточки животного без его фото 

![image](https://user-images.githubusercontent.com/92279258/147344092-7b7e66c3-bb4b-4859-8f07-d0cd0d2a8bee.png)

Получение ключа API

![image](https://user-images.githubusercontent.com/92279258/147344220-fa5edae7-57a1-44eb-a3ad-5c124761ad88.png)

Получчения списка животных My_pets

![image](https://user-images.githubusercontent.com/92279258/147344979-7cd29e70-e14e-4a1a-b7e1-62f354f426de.png)

Создание новой карточки животного

![image](https://user-images.githubusercontent.com/92279258/147345095-773847a2-4118-46a0-b475-458f0f846aef.png)

Добавление фото для животного

![image](https://user-images.githubusercontent.com/92279258/147376683-ec6924b2-312b-4d5f-9d36-47229f9387aa.png)


Удаление карточки животного

![image](https://user-images.githubusercontent.com/92279258/147376636-939b8339-8340-4023-97d0-3e3e56288e1c.png)

Обновление информации о животном

![image](https://user-images.githubusercontent.com/92279258/147376745-6f524d02-68c7-4191-9567-1572be00b53b.png)

Как видим, каждая функция работает, следовательно, на сайте отображаются все проделанные действия. Для тестирования функций API, была использована библиотека Pytest. ( как и в лекции). Также в работе были использованы фикстуры и параметризация ( это можно увидеть в исходных файлах с кодом). 

Фикстура

![image](https://user-images.githubusercontent.com/92279258/147376821-671ed9b7-0cbc-4884-a649-64fe6c1241c2.png)

Параметризация

![image](https://user-images.githubusercontent.com/92279258/147376831-03d3f6dc-c09e-4cf5-94af-c12ef2e3278b.png)

 фото питомца

![image](https://user-images.githubusercontent.com/92279258/147376845-eb486fd7-0ab5-4dff-91b6-e8f35bb2b07b.png)

![image](https://user-images.githubusercontent.com/92279258/147376859-e25de771-fe5e-45e1-8726-f62aeda00ada.png)


