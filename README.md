###
 Практическое задание. Тестирование мобильных приложений. 
---

Задача: полноценное тестирование мобильного приложения на платформе Android. Для целей тестирования можете использовать как реальный девайс, так и эмулятор (Android Studio). Приожение TO-DO, сам файл установки вы найдете здесь https://drive.google.com/file/d/1IkqWnm6z293ETG0MdveKTjrsrWd7WQHz/view?usp=sharing 

<p><strong> Задание 1 Android Studio </strong></p>

1. Написать чек-лист для тестирования всех функций приложения и загрузить в гугл-таблицу. 
<li>  <a href="https://docs.google.com/spreadsheets/d/1ah6rQ_NxeTUkWW0cr4LRI8ZjlTqVEa9A/edit?usp=drive_link"> Решение </a>  </li>

2. Для модуля на создание таски, который вы определите, напишите тестовый набор с кейсами в системе QASE  в наборе Mobile App Testing
<li>  <a href="https://drive.google.com/file/d/1s3GsURHqPyA6i47bmFQac7cfdFnJoNsi/view?usp=drive_link"> Решение </a>  </li>

---

<p><strong> Задание 2 Android Studio </strong></p>

1. На основании написанной документации оформите отчеты о дефекте в YouTrack.
<li>  <a href="https://artsiomrusau.youtrack.cloud/issue/FTJ2023-729/Mobile-App-Testing-Anzhelika-Akmatova"> Решение </a>  </li>

2. По результатам тестирования необходимо создать отчет. Используйте только те данные, которые были получены в рамках проведенного тестирования, например, количество запущенных кейсов и их результаты, общее число багов, классификация их по приоритетам и так далее.
<li>  <a href="https://docs.google.com/document/d/1ezuzfcuKC6RjzVdjdHUKyc0HG8MEoz3q/edit?usp=drive_link&ouid=114290927927113588530&rtpof=true&sd=true"> Решение </a>  </li>

---

<p><strong> Задание 3 Charles Proxy </strong></p>

1. Необходимо изменить количество товаров в корзине на уже известном ресурсе http://demowebshop.tricentis.com/cart Например, в запросе отправляется "2 товара", а вы должны вернуть "500".
2. Смоделируйте ситуацию, при которой при обращении к http://demowebshop.tricentis.com/ сервер вернет статус-код 403. Помните, что запросы к другим ресурсам должны работать в штатном режиме
3. Иногда в работе тестировщика необходимо перебрасывать запросы с одного окружения на другой. Например, мы не можем проводить прямое тестирование на проде, а должны стучаться к окружению для тестирования. Предположим, что http://demowebshop.tricentis.com/ это продовская версия, а http://demowebshop.tricentis.com/qa это QA стенд (не обращайте внимание, что этой страницы не существует). Ваша задача перенаправить запрос с Prod на QA
<li>  <a href="https://drive.google.com/drive/folders/1cK0-hnamRLQqzLZT-zAMr5CcQwYf6nfO?usp=drive_link"> Решение </a>  </li>

---

<p><strong> Задание 4 Charles Proxy </strong></p>

1. Вам необходимо удалить товары из корзины на уже известном ресурсе http://demowebshop.tricentis.com/

2. Смоделируйте ситуацию, при которой при обращении к http://demowebshop.tricentis.com/ пользователь увидит в браузере любую картинку

3. Приложите скриншот любого перехваченного HTTPs-запроса с вашего мобильного устройства. В header user-agent должна быть информация о вашем устройстве.
<li>  <a href="https://drive.google.com/drive/folders/1cK0-hnamRLQqzLZT-zAMr5CcQwYf6nfO?usp=drive_link"> Решение </a>  </li>