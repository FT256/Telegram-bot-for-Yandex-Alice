# Telegram-bot-for-Yandex-Alice
При создании навыка для Алисы, в пункте backend укажите URL скрипта webhook_alice.php

Например: https://www.test.ru/webhook_alice.php

Для отправки сообщений Telegram боту/каналу в файле webhook_alice.php измените строки: 

  $tg_bot_token = "Your_telegram_bot_token";  //ваш токен
  
  $tg_user_id = "Your_telegram_chat_id";      //ваш chat id или id канала
