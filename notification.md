Вирішив створити NotificationService за допомогою білдера, тобто new UserBuilder("user", "email") буде надавати нам масив юзерів у яких notifications true та канал email, відповідно змінивши email на inapp ми отримаємо масив юзерів у яких канал  inapp. Так як у завданні було вказано що у майбутньому реалізація для кожного каналу буде різною та сильно відрізнятись одна від одної,  new UserBuilder("user", "email") - цей запис дозволить нам отримати саме ті дані які нам потрібні у зручний спосіб