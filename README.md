# Laravel_Chat_app_Ajax
This app is a real time chat app with notifications based on php laravel 5.4 framework. For frontend I used Jquery and bootstrap and Ajax for transferring data between frontend and backend. 


<h2> Welcome </h2>

<h2> Installation </h2>
<br>
1- Download chatct.zip and unziped (this the original project folder) and use it as any laravel 5.4 project you have<br>
2- Migrate al the table.<br>
3- Run the server. <br>
<br>
<br>
<h2>Quick app links:</h2>
<br>
 For register:  http://127.0.0.1:8000/register<br>
 For login     :  http://127.0.0.1:8000/login<br>
 Home page :  http://127.0.0.1:8000/home<br>
 Chat Page   :  http://127.0.0.1:8000/chatroom/ {id of the user you want to chat with}<br>
<br>
<br>
<h2>How to use?</h2>
<br>
1- Click  ‘Register’ at top right corner and create least 2 accounts. Or click ‘Login’ if you have already registered. <br>
2- At the right column  ‘users’ , from ‘Your Status’ you can change your status (online, offline, busy). Note: after you close your browser you will be updated offline at all the users  when you open the browser again you will be updated as your last status you set. Your status will be saved in a cookie on your device.<br>
3- At the right column  ‘users’ , click on any user name to start a chat or send a message to.<br>
4- The little circle next to every user name is to show his/her status, green means online, gray means offline and red means busy.<br> 
5- After you click on a username, on the chat page, in the textarea below the ‘chatting with ----’ panel, write your message and click send to send “wow”. Now it’s like a chat.<br>
6- If the other user is offline or not opening the same chat page, he\she will get a notification. The little bell next to your name at the top right of the screen will turn to be red. When he click it he\she will see all his\her notifications once click on a notification will redirect to the chat page to read the message. <br>
Note: the app sends to the server every 30 seconds for updating chat and notifications  and every minute for the users status if you closed your app you will get updated offline after 90 seconds.<br>
7- You can see your old messages by clicking on the chats icon next to your name at the top right corner of the screen.<br>
<br>
<br>
<h2>Technical information</h2>
This app is based on php laravel 5.4 framework. For frontend I used Jquery and bootstrap and Ajax for transferring data between frontend and backend. <br>
The app is working well on my pc using xampp v3.2.2, php 7.0.1 and mysql.<br>
Packages I used, Laravel Authentication and Laravel Notifications (database only).anything else has been built manually. <br>
Eloquent relationships : many to many between chat and User models and one to many between chat and messenger models.<br>
