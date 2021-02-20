# OrderChat
<h3> Notes for orders in the Opencart admin panel (chat in orders) </h3>

<p> This add-on will add a mini-chat to orders (for each order), as well as to order information. This will allow you to take notes for other store employees </p>
<h4> Installation </h4>
<ol>
  <li> You need to copy files to the store root; </li>
  <li> In <a href="https://github.com/Wolflirik/OrderChat/blob/master/chat_for_order.sql"> chat_for_order.sql </a> add prefixes to all occurrences of chat_for_order (if present in other tables , by default there are no prefixes in the file) it should look something like this: <i> <b> oc_ </b> chat_for_order </i>; </li>
  <li> In phpMyAdmin, import the resulting file <a href="https://github.com/Wolflirik/OrderChat/blob/master/chat_for_order.sql"> chat_for_order.sql </a>; </li>
  <li> Replace the server address with your ip and port in the order_chat.xml file on lines
    <a href="https://github.com/Wolflirik/OrderChat/blob/bb90345f7dc249b43d56afacb9e02fa9f4deb690/vqmod/xml/order_chat.xml#L55">
      55 </a> and
    <a href="https://github.com/Wolflirik/OrderChat/blob/bb90345f7dc249b43d56afacb9e02fa9f4deb690/vqmod/xml/order_chat.xml#L209"> 209 </a>;
  </li>
  <li> Launch a command line on the server and enter the following <i> <b> nohup php -f / var / www / STORE ADDRESS / system / bin / chat-server.php> / dev / null 2> & 1 & </ b > </i>. </li>
</ol>
<p> Tested on Opencart 1.5.4.1 </p>
<p> Will work on versions less than 2. If you have questions or suggestions, write to the mail. </p> 
