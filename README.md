# OrderChat
<h3>Заметки для заказов в админку Opencart (чат в заказах)</h3>

<p>Данное дополнение добавит в заказы мини-чат (к каждому заказу), а так-же в информацию о заказе. Это позволит делать заметки для других сотрудников магазина</p>
<h4>Установка</h4>
<ol>
  <li>Необходимо скопировать файлы в корень магазина;</li>
  <li>Заменить адрес сервера на свой ip и порт в файле order_chat.xml на строках
    <a href="https://github.com/Wolflirik/OrderChat/blob/bb90345f7dc249b43d56afacb9e02fa9f4deb690/vqmod/xml/order_chat.xml#L55">
      55</a> и 
    <a href="https://github.com/Wolflirik/OrderChat/blob/bb90345f7dc249b43d56afacb9e02fa9f4deb690/vqmod/xml/order_chat.xml#L209">209</a>;
  </li>
  <li>Запустить командную строку на сервере и ввести следующее <b>nohup php -f /var/www/lightphotos/data/www/АДРЕС МАГАЗИНА/system/bin/chat-server.php > /dev/null 2>&1 &</b>.</li>
</ol>
<p>Проверялось на Opencart 1.5.4.1</p>
<p>Будет работать на версиях меньше 2</p>
